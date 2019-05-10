## Stars Filter Theory Experimental Documentation

```python
#importing aguaclara packages needed for calculations
import aguaclara
#pyschem contains useful functions for calculations
import aguaclara.core.physchem as pc
#units package helps us convert to useful untis
from aguaclara.core.units import unit_registry as u
#math packages
import numpy as np
from aide_design.play import*

#Constraints:
# Filter diameter = 1 inch
# Backwash Velocity = 11 mm/s
# Filter Column length = 20 cm (old filters were 40cm)
# Temperature = 20 degrees Celsius
# Pipe Roughness = 0
# KMinor (constant) = 1

#Solving for:
# Filter Area, Nu (Viscosity Kinematic), Velocity (during filtering), headloss
# Filter Area and Nu are needed for headloss calculation

filter_D=1 * u.inch
filter_A=pc.area_circle(filter_D)
print(filter_A)
backwash_v=11 * u.mm / u.s
Length= 20 * u.cm
velocity = backwash_v/6
flow_rate=(velocity*filter_A).to(u.ml / u.sec)

#Using this help function we determined that this function returns total head loss, major and minor
help(pc.headloss)

print(flow_rate)
temp=20 * u.degC
Nu=pc.viscosity_kinematic(temp)
PipeRough=0 * u.mm
KMinor= 1

#Returns total headloss
head_loss=pc.headloss(flow_rate, filter_D, Length, Nu, PipeRough, KMinor)
print(head_loss)
#Headloss was negligible
#Fun fact: Python is no longer running for me in atom since I updated my sync settings so I'll update this code with exact values later

```
