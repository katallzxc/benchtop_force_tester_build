# Benchtop linear shear force test apparatus
### Hatton Lab @ the University of Toronto
This repository contains CAD/hardware and circuit-related files for the benchtop linear force tester used in the Hatton Lab (Bio-Inspired Materials and Design Laboratory) at the University of Toronto. The code for the force tester is documented in another repository ([benchtop_force_tester_code](https://github.com/katallzxc/benchtop_force_tester_code)).

![Picture of shear force test setup from above, showing motor controller and driver, linear actuator with stepper motor and moving force gauge, and stationary test platform.](/assets/shear_test_overview_clean.png)

## Repository structure
 - The **assets** folder contains images of the shear force tester and diagrams showing its functionality.
 - The **electrical** folder contains (partial, soon to be updated) circuit diagrams for the motor control system.
 - The **hardware** folder contains 3D CAD models for custom printed or machined parts, 2D drawings for laser cut parts, and images of individual parts/CAD models.

## Tester overview
I used the shear force tester to measure the effective coefficient of friction of active robotic grip surfaces (as shown in the schematic below). For this application, the force gauge was connected to a target object held by the gripper, then the force gauge was moved away from the grip surfaces to pull the object from the gripper. The force required to pull the gripped object was recorded and used to analyze shear (frictional) force behaviour.

![Schematic of components of shear force tester.](/assets/shear_test_schematic.png)
