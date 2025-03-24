# VehicleControlModel
Vehicle Control Simulation model, designed for control algorithm development and testing.

----
It's divided into four parts, that will build a total virtual simulation system.
- vehicle plant model 
- controller 
- driver
- enviroments
<div align= "center">
 <img src="https://github.com/clark-ye/VehicleControlModel/blob/main/Documents/Pictures/VehicleModelMainConcept.png" alt="VehModelMainConcept" height="300" >
</div>

The main components modules are as below:
<div align= "center">
 <img src="https://github.com/clark-ye/VehicleControlModel/blob/main/Documents/Pictures/VehicelModelComponents.png" alt="VehModelComponents" height="400" align= "center">
</div>

## The project development phase planning
This project is from the very beginning,we plan to develop the vehicle control model from zero and step by step.

everyone who wants to join is welcome and helpful.

It will develop most based on matlab/simulink, and compiled to run without Matlab.

### phase 1： minimum system
goal: create the model topology and first run.it may contain:

      1) 1-Dof Vehicle model ( longitudinal movement)
      2) Longitudinal control system
      3) Basic road

### phase 2: 3-Dof vehicle model with 2D animation. 
it may contain:

      1) bicycle model, with x,y movement and z-axis rotaion
      2) Longitudinal and lateral control system;
      3) 2-D map and animation

### phase 3:Multi-body vehicle model.
      1) Multi-body consist of interconnencted rigid bodies
      2) suspension plant model, wheels and body;
      3) support for suspention control

### phase 4: still under planning
