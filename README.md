# Haptic Wand Robotic Arm
## Project Overview
This repository builds a 3-dof robotic arms from scratch. With the help of HTC-vive devices, the user can move freely in the VR environment and touch the virtual wall as if it's a real wall.

## Core Functions
- `readFromUnity` - set up the VR environment with wall and the communication with Arduino
- `WhiteboardDemo` - deal with forward/inverse kinematics and sensor fusion
![微信图片_20220928190925](https://user-images.githubusercontent.com/85860671/192868311-8eade77b-f3fc-491f-a0eb-82c5af31082f.jpg)
NOTE: This code runs using both the ODrive Arduino Library and the Eigen Library, so ensure those are installed before use as explained above.
