---
layout: page
title: 'Embedded Systems Assignment 3: Mini Project'
---

## Overview
System uses robotic arm built with designed by us 3D printed parts, two Dynamixel AX-12A servomotors and the camera. Everything is connected to the Ultra96-V2 board which is the brain of the whole system.
Workflow which should be achieved can be split to 4 stages:
* Area scan using servomotor and camera
* AI based nut or bolt detection
* Computer Vision based calculation of tool orientation and nut position
* Arm and tool alignment to be able to potentially screw the bolt (ROS2)

Bottom part of the 3D stand consists of a bracket which guarantees stability but what turned out needs to be removed from camera feed. To the bracket, tower was attached to be able to adjust how high the camera is (it wasn't used but it is always nice to have more options). Next we printed arm motor mount. To attach arm and the tool motor plus the camera we used additional parts from the kit and another 3D prints. It is important that the camera's lens are mounted on the same radius like tool axis.

## Institution
University of Southern Denmark

## Report

<iframe
  src="/assets/projects/embedded-systems/ES_MiniProject.pdf"
  type="application/pdf"
  width="100%"
  height="1000px">
</iframe>

## GitHub

- [main used for the MiniProject](https://github.com/Lpopvil/MiniProject_ES)
- [nodes and scripts used for task connected with computer vision](https://github.com/u000000/ES_images)
- [motor operations](https://github.com/lucasrj/embedded-systems-ros-motor)
- [custom ros2bag tools](https://github.com/u000000/ros2bag_tools)