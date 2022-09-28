# Haptic Wand Robotic Arm
## Project Overview
This repository builds a 3-dof robotic arms from scratch. With the help of HTC-vive devices, the user can move freely in the VR environment and touch the virtual wall as if it's a real wall.
 
## Core Modulus
- `readFromUnity` - set up the VR environment with wall and the communication with Arduino
- `WhiteboardDemo` - deal with forward/inverse kinematics and sensor fusion

NOTE: This code runs using both the ODrive Arduino Library and the Eigen Library, so ensure those are installed before use as explained above.
