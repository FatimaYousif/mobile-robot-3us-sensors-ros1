A Gazebo simulation setup for testing 3 ultrasonic sensors (mounted in front of the robot approx 50 cm apart) on a mobile robot around in ROS 1 Noetic. The testing is done with static obstacles (dynamic obstacles or humans yet to be included)

### How to run

1. After cloning this repo, build and source the workspace.

2. Then, to launch the robot simulation in Gazebo, use the following command:

```bash
roslaunch fb_gazebo fb.launch
```

3. For moving the robot, in another terminal:

```bash
rostopic pub /cmd_vel geometry_msgs/Twist 
```

(Then press tab for auto completeing the linear(x) and angular velocity (z) controller components)
