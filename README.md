# RBE 500 - Foundation of Robotics Final Project

This repository contains the **final project** for **RBE 500 - Foundation of Robotics**. The project focuses on motion planning and control for the **OpenManipulatorX robotic arm** using **ROS 2**.

## Project Overview
This project consists of three main assignments:

1. **Part 1: Forward and Inverse Kinematics**
   - Implement forward kinematics to compute the end-effector pose based on joint values.
   - Implement inverse kinematics as a service to compute joint angles for a given end-effector pose.
   - Test the implementation with ROS 2 service calls and topic publishing.

2. **Part 2: Motion Control in Cartesian Space**
   - Implement velocity-level kinematics for converting joint velocities to end-effector velocities and vice versa.
   - Develop an incremental position reference node to update joint positions iteratively.
   - Execute a straight-line motion in the **+y direction** using velocity transformations.

3. **Part 3: PD Controller for Joint Actuation**
   - Implement a **custom PD controller** for **Actuator 4** (before the gripper).
   - Switch the actuator mode to **current (effort) control** while keeping others in position mode.
   - Tune the PD gains and evaluate the response.
   - Record joint trajectories and analyze controller performance.


