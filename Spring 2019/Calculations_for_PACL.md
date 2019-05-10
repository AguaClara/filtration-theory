## Stars Filter Theory PaCl Calculations

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

#stock concentration in the lab now, may change as new stock is created
stock_concentration=70.28 *u.g/u.l
#We went with 2 mg/L because that is what was in our ProCoDa
final_concentration=2 *u.mg/u.l
final_volume=1* u.l
#Volume_stock=Volume_Final*Concentration_Final/Concentation_stock
#We wanted units of microliters
stock_volume=(final_concentration*final_volume/stock_concentration).to(u.microl)
print(stock_volume)
#Volume is: 28.46 microliters
# Now we can calculate volume needed in the future if the stock concentration changes

```
