# SBBot

## A Self-Balancing Robot which is based on ROS

Clone this repository in your **catkin_ws/src**

1. `cd catkin_ws/`
2. `catkin_make`
3. `source ./devel/setup.bash`

To view the urdf model in RVIZ :
`roslaunch sbbot_pkg urdf_rviz_view.launch`

To spawn the model in Gazebo :
 1. Launch a empty world : `roslaunch gazebo_ros empty_world.launch`
 2. Spawn the model : `roslaunch sbbot_pkg urdf_gazebo_spawn.launch`

