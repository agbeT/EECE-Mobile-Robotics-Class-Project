# EECE-Mobile-Robotics-Class-Project
## On both turtlebot and remote PC.
1. Clone repository into ```catkin_ws/src```.
2. Go to ```catkin_ws``` and ```catkin_make```.

## On remote PC
1. SSH into turtlebot and run ```roslaunch turtlebot3_explore bebop.launch```
2. Open new terminal tab and run ```roslaunch turtlebot3_explore turtlebot3_auto_explore```
3. In new terminal tab, ```rosrun turtlebot3_explore april_detections.py```
