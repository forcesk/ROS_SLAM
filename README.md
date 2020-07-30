# ROS_SLAM

* roslaunch turtlebot_gazebo turtlebot_world.launch
* rosrun gmapping slam_gmapping
* roslaunch turtlebot_teleop keyboard_teleop.launch
* rostopic echo -n 1 /map
* rosrun map_server map_saver -f mymap
