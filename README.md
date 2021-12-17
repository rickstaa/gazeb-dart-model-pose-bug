# gazebo-bug-reproduce

Small example repository I use to reproduce bugs I find in Gazebo 11. This repository contains a simple stick robot that can be launched using the `roslaunch gazebo_dart_model_pose_bug stick.launch`
. See the launch file for the available arguments. This robot uses a modified version of the [DefaultRobotHWSim](https://github.com/ros-simulation/gazebo_ros_pkgs) to which a gravity compensator was added. This gravity compensator can be disabled by setting the `gravity_compensation` ROS parameter.
