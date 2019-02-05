# SBBot

## A Self-Balancing Robot based on ROS


- `cd catkin_ws/src`
- `catkin_create_pkg sbbot_pkg rospy rviz controller_manager gazebo_ros joint_state_publisher robot_state_publisher urdf`
-  Clone this repo here and replace the files in sbbot_pkg
- `cd ..` (Go back to catkin_ws/)
- `mv src/rosarm_pkg/rosarm_moveit_config src`
- `catkin_make`
- `source ./devel/setup.bash`

To view the urdf model in RVIZ :
`roslaunch sbbot_pkg urdf_rviz_view.launch`

To spawn the model in Gazebo :
`roslaunch sbbot_pkg urdf_gazebo_view.launch`

