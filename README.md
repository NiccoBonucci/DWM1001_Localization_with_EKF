# Introduction to the project
This repository contains all the files needed for:
- Pose estimation of a robot using DWM1001 Ultra-WideBand Localization devices
- Application of an Extended Kalman Filter to improve the pose estimation accuracy
- Comparison with ground truth values taken from the Optitrack localization system
The whole system has been tried and works on Ubuntu 20.04 with the Noetic Ninjemys version of ROS. The robot model used for this project is a unicycle, the simulation in the real environment is done with Turtlebot 2. 

# Setup of the work environment
The following steps describe how to properly setup your work environment to be able to use the localization system:
1) Clone the GitHub link in the "src" folder of your catkin workspace:
git clone https://github.com/NiccoBonucci/ROS_DWM1001_Localization_with_EKF.git
2) Compile with "catkin_make"
3) 

