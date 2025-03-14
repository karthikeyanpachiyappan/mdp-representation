# MDP REPRESENTATION
# NAME: KARTHIKEYAN P
# REG NO: 212223230102
## AIM:
To Mapping a Real-World Problem to a Reinforcement Learning Problem

## PROBLEM STATEMENT:

### Problem Description
The problem of autonomous drone delivery can be formulated as a Reinforcement Learning (RL) problem. With the growing demand for fast
and efcient deliveries, drones can be used to transport packages while avoiding obstacles, optimizing routes, and minimizing energy
consumption. The goal is to develop an RL-based system that allows drones to navigate urban environments efciently and deliver packages in
the shortest time possible

### State Space
The state space represents the current conditions of the delivery system, including:

Drone’s current position (GPS coordinates).
Destination location.
Wind speed and direction.
Battery level of the drone.
Presence of obstacles (e.g., buildings, birds, restricted airspaces)
### Sample State
A possible state representation:

Drone Position: (Latitude: 37.7749, Longitude: -122.4194).
Destination: (Latitude: 37.7849, Longitude: -122.4094).
Wind Speed: 10 km/h, Direction: North.
Battery Level: 80%.
Obstacles Nearby: High-rise buildings at (37.7799, -122.4144).
Trafc Conditions: Moderate congestion in drop-off area.
### Action Space
The action space consists of different drone control options:

Adjust altitude (increase/decrease height to avoid obstacles).
Change direction (move north, south, east, or west).
Increase or decrease speed based on battery efciency.
Hover in place if no safe route is available.
Return to base if the battery is too low to continue the mission.
### Sample Action
A possible action could be:

Increase altitude by 10 meters to avoid a high-rise building in the drone’s path.
### Reward Function
The reward function incentivizes optimal package delivery while considering efciency and safety:

Positive Rewards:

Successfully reaching the destination (+10 reward).
Taking the shortest route (+5 reward for minimizing distance).
Conserving battery power (+3 reward for efcient energy use).

Negative Rewards:

Collision with obstacles (-10 penalty for crashes).
Deviating too far from the optimal route (-5 penalty).
Excessive battery consumption (-3 penalty for inefcient fying).
Hovering unnecessarily (-2 penalty for wasting time).
### Graphical Representation
![WhatsApp Image 2025-03-14 at 14 35 18_ace3fd46](https://github.com/user-attachments/assets/dfbe0e5e-cd1c-4a04-bcde-0406e38be490)


## PYTHON REPRESENTATION:
![Screenshot 2025-03-14 140436](https://github.com/user-attachments/assets/bbb08ed5-0c1f-4866-b77a-065ba356bfcc)

## OUTPUT:

![Screenshot 2025-03-14 140521](https://github.com/user-attachments/assets/797b937e-c1eb-4fc7-9fb2-d8284133b203)

## RESULT:
Thus, the given real-world problem of choosing the autonomous drone delivery is successfully represented in MDP form.
