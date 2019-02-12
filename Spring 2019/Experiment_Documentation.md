## Stars Filter Theory Experimental Documentation

```python
import aguaclara
import aguaclara.core.physchem as pc
from aguaclara.core.units import unit_registry as u
import numpy as np

filter_D=.25 * u.inch
filter_A=pc.area_circle(filter_D)
print(filter_A)
backwash_v=11 * u.mm / u.s
Length= 20 * u.cm
velocity = backwash_v/6
flow_rate=(velocity*filter_A).to(u.ml / u.sec)

print(flow_rate)
temp=20 * u.degC

Nu=pc.viscosity_kinematic(temp)
PipeRough=0 *u.ml
KMinor= 1

head_loss=pc.headloss(flow_rate, filter_D, Length, Nu, PipeRough, KMinor)

```
