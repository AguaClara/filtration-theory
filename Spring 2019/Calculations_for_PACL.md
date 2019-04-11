## Stars Filter Theory PaCl Calculations

```python
import aguaclara
import aguaclara.core.physchem as pc
from aguaclara.core.units import unit_registry as u
import numpy as np
from aide_design.play import*

stock_concentration=70.28 *u.g/u.l
final_concentration=2 *u.mg/u.l
#We went with 2 mg/L because that is what was in our ProCoDa
final_volume=1* u.l
stock_volume=(final_concentration*final_volume/stock_concentration).to(u.microl)
print(stock_volume)
#Value is: 28.46 microliters

```
