# ROS Package for Interactive Cleanup

This project is ROS package for the Interactive Cleanup task of the RoboCup@Home Simulation.

See also [wiki page](https://github.com/RoboCupatHomeSim/interactive-cleanup-ros/wiki).


## Prerequisites

- OS: Ubuntu 18.04
- ROS distribution: Melodic Morenia

## How to Install

### Install Rosbridge Server

Please see below.  
http://wiki.ros.org/rosbridge_suite

### Install SIGVerse Rosbridge Server

Please see below.  
https://github.com/SIGVerse/ros_package/tree/master/sigverse_ros_bridge

### Install ROS Package of Interactive Cleanup

```bash:
$ cd ~/catkin_ws/src
$ git clone https://github.com/RoboCupatHomeSim/interactive-cleanup-ros.git
$ cd ..
$ catkin_make
```

## How to Execute

### How to Execute Sample ROS Node

It is a simple ROS node that communicates with the Interactive Cleanup application.

```bash:
$ roslaunch interactive_cleanup sample.launch
```

### How to Execute Teleoperation Tool

You can operate HSR with keyboard operation.  
It is for debugging.

```bash:
$ roslaunch interactive_cleanup teleop_key.launch
```

## License

This project is licensed under the SIGVerse License - see the LICENSE.txt file for details.
