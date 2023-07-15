# VEHICLE

### The following project contains two subtasks:

#### Subtask 1: 
You are given the classes Vehicle, Car, and F1. Complete the driver code of each of these classes.
#### Subtask 2: 
You are given the interface WaterVehicle. 
Construct a new class Boat (with exactly the same and member variables as given below).


_The details of the classes that constitute the project are:_

#### Vehicle: name, currentSpeed, currentDirection
1. constructor: given the name of the vehicle, initialize speed and direction as 0.
2. move(speed, direction): set the current speed and direction
3. steer(direction): Add direction to the currentDirection
4. stop(): Stop the car by setting current speed to 0

#### Car: extends Vehicle
1. constructor: initialize the variables using parameters and set currentGear as 1.
2. changeGear(newGear): set the current gear to newGear parameter.
3. changeSpeed(newSpeed, newDirection): set the speed and direction using move().

#### F1: extends Car
accelerate(rate): add rate to the current speed and change the gear accordingly

#### Boat: implements WaterVehicle interface
1. Has following member variables: a. name : of String type b. capacity : of int type
2. Return name and capacity in getVehicleName and getVehicleCapacity respectively.

**Note:** Make sure that the class names are exactly the same.