# EduCar
Code for RM Edu Car from Crowd Supply.  For use with CircuitPython.

## Usage

Place the `robohateducar.py` library file into the `libs/` folder on your Robo HAT MM1 CIRCUITPY drive.  Then use as per the example.

## Example
Place the following code into `code.py` on the CIRCUITPY drive.  Please edit as required.

``` Python
import board
import time
from robohateducar import *

car = RoboHatEduCar()

# drive the car forwards 1 metre
car.drive(RoboHatEduCar.CMD_DRV_FORWARD, 1)

# stop the car
car.stop()
```

## Freeze Module
Only required when using older CircuitPython boards
``` bash
git submodule add https://github.com/peterpanstechland/RoboticsMasters_educar.git frozen/RoboticsMasters_educar
```
