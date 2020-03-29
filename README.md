# Drobo (Disaster Robo)
Rocker-bogie based disaster assistant robot using ROS Kinetic 

Drobo (BE Project)
------------------------------------------------------------------------------
Setting up ROS Environment

1. source /opt/ros/kinetic/setup.bash

2. cd catkin_ws

3. source devel/setup.bash

4. echo src/drobo
   /home/$YOUR_PC_NAME/catkin_ws/src:/opt/ros/kinetic/share
------------------------------------------------------------------------------
Drobo Teleoperation:-

1. roslaunch drobo_bringup gazebo.launch

2. roslaunch drobo_bringup view_robot.launch

3. roslaunch drobo_bringup drobo_teleop_key.launch

-------------------------------------------------------------------------------
Drobo Mapping (gmapping) :-

1. roslaunch drobo_bringup gazebo.launch

2. roslaunch drobo_gazebo gmapping_demo.launch

3. roslaunch drobo_bringup view_navigation.launch /
   rosrun rviz rviz

4. roslaunch drobo_bringup drobo_teleop_key.launch

---------------------------------------------------------------------------------
Drobo Localization (amcl) :-

1. roslaunch drobo_bringup gazebo.launch

2. roslaunch drobo_gazebo amcl_demo.launch

3. roslaunch drobo_bringup view_navigation.launch /
   rosrun rviz rviz
--------------------------------------------------------------------------------


