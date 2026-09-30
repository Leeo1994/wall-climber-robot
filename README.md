# Wall Climbing Robot

University of Bristol group project. A magnetic tracked robot that climbs walls, with a Raspberry Pi host for sensing and an Arduino Micro for motor control.

## Mechanical
- 16-segment chain containing 32 magnets (4:4:3 mm dimensions, 70 g load each)
- Chain load capacity of 2.4 kg, with a final robot weight of 1.25 kg (1.15 kg spare for extra equipment)
- Integrated barrier within the gears keeps the chain trapped
- Two gear types: motorized (keyhole) and free-running on bearings

## Electronics
- Raspberry Pi 4 (host) connected to a Pi camera (CSI) and a lidar (USB)
- Arduino Micro (peripheral), connected to the Pi over serial
- Arduino sends PWM signals to a motor driver, which adjusts the speed of the two motors

## Stakeholders
Albion Dock and SS Brunel gave input as potential stakeholders and said they could be interested in a robot like this. We did not pursue this further.
