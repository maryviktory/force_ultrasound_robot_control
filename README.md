# force_ultrasound_phasesymmetry_robot_control
In this project robot was scanning the surface of human spine phantom to capture Ultrasound images and respective robot coordinates for further 3D reconstruction.

Robotic control for two cases:
1) (Force control) Robot moves along pre-recorded trajectory and applies force control to assure that it always applies constant preasure to the phantom's skin.

2) (Force-Image control) Same force control as in the previous case, but the image controlled based on the **phase symmetry** is added. Robot's first and last points are assigned at the beguinning and at the end of the spine. From first to the last point robot moves applying the constant force and adjust the positions so that the spine is in the center of the ultrasound image 

The **Force control part** of the work was presented at IRC2019 named "3D Ultrasound Imaging of Scoliosis with Force-Sensitive Robotic Scanning", [publication website](https://ieeexplore.ieee.org/document/8675657).

The **Force-Image part** of the work was presented at IROS2019 workshop, the video of the work presentationis presented here, **[video](https://www.youtube.com/watch?v=ccLseg5XS0w&ab_channel=Grow2Gather)** "Robotic Ultrasound Navigation for Scoliosis Diagnostic and Facet Joint Injections"

# How to use the code
**Force control**
File to launch: *Move_force_trajectory.py*


**Force-Image control**

File to launch: *Image_force_control_UR5.py*
Method example of center of spine detection for further navigation can be seen
at *Examples/Center_spine_detection_Max_Mean_point.py*

![Alt text](https://github.com/maryviktory/force_ultrasound_phasesymmetry_robot_control/blob/master/Navigation_robotic_Polyu/GUI/Setup.png "Setup")



![GitHub Logo](https://github.com/maryviktory/force_ultrasound_phasesymmetry_robot_control/blob/master/Navigation_robotic_Polyu/GUI/Capture.JPG)
