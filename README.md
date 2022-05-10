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

Ego car stopped before line
