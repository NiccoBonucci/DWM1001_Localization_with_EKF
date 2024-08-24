# Introduction to the project
This repository contains all the files needed for:
- Pose estimation of a robot using DWM1001 Ultra-WideBand Localization devices
- Application of an Extended Kalman Filter to improve the pose estimation accuracy
- Comparison with ground truth values taken from the Optitrack localization system
The whole system has been tried and works on Ubuntu 20.04 with the Noetic Ninjemys version of ROS. The robot model used for this project is a unicycle, the simulation in the real environment is done with Turtlebot 2. 

# Setup of the work environment
To properly setup your work environment to be able to use the localization system, you will need the following packages:
1) ros-dwm1001-uwb-localization-master
2) vrpn_client_ros

