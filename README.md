# Color Sorter Robotic Arm
3DOF Robotic Arm Color Sorter (project under developement)

![2](https://github.com/adnanO999/RoboticArm/assets/88556508/4bd8b7b2-96a7-4d38-b446-cdbc11732405)


# Aim of The project
This project aims to utilize robotics principles such as manipulator design, kinematics (forward and inverse), path planing and other concepts.
Moreover incorporating computer vison using OpenCV and Pillow libraries along with using external camera to detect objects with different colors.
The overall architectrue will be developed using ROS noetic 

The project can be devided into several steps:
* Modeling of the arm on solidworks (the model is already available online but I made some modifications)
* 3D printing the model along with assembly
* Use of forward and inverce kinematics equations to move the arm
* Use matlab to validate and control the arm (along with simscape where the solidworls model will be used)
* Motion generation
* Color detection
* Pick and Place objects

![WhatsApp Image 2023-05-25 at 19 11 50](https://github.com/adnanO999/RoboticArm/assets/88556508/6b4055a9-60af-48ee-a999-4717e7d7c0bd)

# Digital Twin
I generated the URDF file of the arm and used it to create a visualization for the robot in Rviz and Gazebo. The robotic arm was also configured using moveit and a hardware interface with arduino was developed.

# demo
https://github.com/adnanO999/RoboticArm/assets/88556508/9d7d52b3-75fa-45aa-a246-c30f5f9f99bc




