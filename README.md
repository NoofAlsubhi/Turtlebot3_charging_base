# Turtlebot3_charging_base
## task3
- First step: run this code:
 ```
 export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_gazebo turtlebot3_world.launch
 ```

 - Second step: open a new terminal tap, and run navigation node:
 ```
 export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_navigation turtlebot3_navigation.launch 
 ```
 - 
![T3](https://user-images.githubusercontent.com/85634146/129982248-0412a93b-8a8b-4f8f-8885-1954ddb7ed06.jpeg)

 - third step: to control, open a new terminal and run this code:
 ```
 export TURTLEBOT3_MODEL=burger
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
 ```
 - 
 ![T33](https://user-images.githubusercontent.com/85634146/129982250-0a793fc8-4caa-4099-833d-a980a026dbbb.jpeg)
