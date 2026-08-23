# System Architecture

## Research Platform

The initial system targets a low-speed ROS2 autonomous mobile robot operating in restricted campus environments.

## High-Level Pipeline

Sensors
-> Perception
-> Localization
-> Global Planning
-> Local Planning
-> Motion Control
-> Safety Supervisor
-> Vehicle Platform

## ROS2 Baseline

Initial software stack:

- ROS2
- Nav2
- Gazebo
- SLAM Toolbox
- robot_localization

## Planned Sensor Inputs

- 2D or 3D LiDAR
- RGB / RGB-D camera
- IMU
- wheel encoder
- GNSS / RTK-GNSS

## Localization

Initial baseline:

- wheel odometry
- IMU fusion
- LiDAR localization or SLAM

Outdoor GNSS fusion will be introduced after the simulation and restricted-area baseline is stable.

## Planning

Nav2-supported planners will establish baseline performance first.

RRT / RRT* or other sampling-based algorithms will be evaluated only when they address a measurable limitation in the baseline.

## Safety Supervisor

The safety layer must be capable of overriding autonomous navigation.

Trigger conditions include:

- localization failure
- communication loss
- obstacle proximity violation
- critical sensor failure
- manual emergency stop
