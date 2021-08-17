# Turtlebot3_charging_base
## task3
- First step: run this code:
 ```
 export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_gazebo turtlebot3_world.launch
 ```
 - pic
 - Second step: open a new terminal tap, and run navigation node:
 ```
 export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_navigation turtlebot3_navigation.launch 
 ```
 - pic
 - third step: to control, open a new terminal and run this code:
 ```
 export TURTLEBOT3_MODEL=burger
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
 ```
 - pic
