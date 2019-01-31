# SBBot

## A Self-Balancing Robot based on ROS


1. `cd catkin_ws/src`
2. `catkin_create_pkg sbbot_pkg rospy rviz controller_manager gazebo_ros joint_state_publisher robot_state_publisher urdf`
3. `catkin_make`
4. Clone this repository in this package
5. `cd catkin_ws`
6. `source ./devel/setup.bash`

To view the urdf model in RVIZ :
`roslaunch sbbot_pkg urdf_rviz_view.launch`

To spawn the model in Gazebo :
`roslaunch sbbot_pkg urdf_gazebo_view.launch`

