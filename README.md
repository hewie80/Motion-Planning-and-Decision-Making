## Project Overview
In this project, two of the main components of a traditional hierarchical planner: The Behavior Planner and the Motion Planner are implemented. Both will work in unison to be able to avoid static objects, avoid crashing with these vehicles and Track the centerline on the traveling lane.
## Implemented
1. Behavioral planning logic using Finite State Machines - FSM
2. Static objects collision checking.
3. Path and trajectory generation using cubic spirals
4. Best trajectory selection though a cost function evaluation. 
## Code overview
 - behavior_planner_FSM.cpp
 - cost_functions.cpp
 - motion_planner.cpp
 - velocity_profile_generator.cpp
 - planning_params.h
## Simulation result
Ego car passed other car
![屏幕截图 2022-05-10 101439](https://user-images.githubusercontent.com/99339837/167533852-ba675362-a98b-4455-8c99-d85d220d7c8a.png)

Ego car stopped before line
![屏幕截图 2022-05-10 101554](https://user-images.githubusercontent.com/99339837/167533858-8602fdee-e9a3-4f0c-ba0e-f9f255539c56.png)
