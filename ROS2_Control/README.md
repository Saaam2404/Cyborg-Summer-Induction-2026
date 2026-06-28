# ROS 2 Control Reference Package

## Overview

This package is provided **only as a reference** to help you understand the integration of the **ROS 2 Control** framework with a mobile robot. It demonstrates how to configure:

* ROS 2 Control plugins
* Controller configuration (YAML)
* `<ros2_control>` tags in the URDF
* Gazebo ROS 2 Control plugin
* Launch files for loading and managing controllers

## Important

> **Do not use this package directly for the mini task.**

You are expected to integrate **ROS 2 Control** into **your own line-following robot** developed in the previous task. The objective is **not** to reuse this robot model, but to understand the complete workflow involved in configuring ROS 2 Control.

## Learning Objectives

By studying this package, you should understand:

* How to define hardware interfaces using the `<ros2_control>` tag.
* How to configure controllers in a YAML file.
* How to integrate the Gazebo ROS 2 Control plugin.
* How to load controllers using the `controller_manager`.
* How to bridge Gazebo and ROS 2 using `ros_gz_bridge`.
* How to launch and manage controllers through a launch file.
* How to switch between different controllers at runtime.

## Expected Outcome

After understanding this reference package, you should be able to integrate ROS 2 Control into **your own line-following robot** and configure different controllers such as the Diff Drive Controller or Forward Velocity Controller without modifying the robot's hardware description.

> **The primary objective of this reference package is to help you understand the configuration of ROS 2 Control plugins, controllers, YAML files, and launch files—not to serve as the solution for the mini task.**
