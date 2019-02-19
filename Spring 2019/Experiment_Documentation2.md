## Stars Filter Theory Experimental Documentation

```python
import aguaclara
import aguaclara.core.physchem as pc
from aguaclara.core.units import unit_registry as u
import numpy as np
from aide_design.play import*

filter_D=.25 * u.inch
filter_A=pc.area_circle(filter_D)
print(filter_A)
Length= 20 * u.cm
temp=20 * u.degC
Nu=pc.viscosity_kinematic(temp)
PipeRough=0 *u.mm
KMinor= 1
head_loss_by_velocity=[]
velocity=np.arange(29)
for x in range(1,30):
  backwash_v=x * u.mm / u.s
  velocity = backwash_v/6
  flow_rate=(velocity*filter_A).to(u.ml / u.sec)
  #print(flow_rate)

  head_loss=pc.headloss(flow_rate, filter_D, Length, Nu, PipeRough, KMinor)
  head_loss_by_velocity= np.append(head_loss_by_velocity,head_loss)

plt.plot(velocity+1,head_loss_by_velocity,'-',label = "Headloss by Velocity")
plt.xlabel('Velocity (mm/s)')
plt.ylabel('Headloss')
plt.title('Headloss by Velocity')

plt.minorticks_on()
plt.grid(which = 'major')
plt.grid(which = 'minor')
plt.legend(loc = 'lower right', ncol = 1)
plt.tight_layout()
plt.show()
# This was working now its not. Graph is linear.

```
