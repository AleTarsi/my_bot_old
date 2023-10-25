## Robot Package Template

This is a GitHub repository created following the tutorial present in [this link](https://articulatedrobotics.xyz/mobile-robot-12-ros2-control/) up to lesson 3.

The goal of this code is creating your own urdf specifying links and joints. Having a launch file which open up Gazebo, spawn the robot you created and create the node "robot_descriptor". Use the gazebo plugin _diff_driv_ to transform velocity command coming from `/cmd_vel`into transformation of the robot’s wheels published into the topic `/tf`.

