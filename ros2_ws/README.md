# ROS2 Workspace

## Target Environment

Primary development target:

- Ubuntu 24.04
- ROS 2 Jazzy
- Nav2
- Gazebo Harmonic

macOS is used for repository management and general development, while ROS2 simulation and integration should run inside an Ubuntu environment.

## Workspace

```bash
cd ros2_ws
colcon build
source install/setup.bash
Initial Milestone
Spawn the robot model.
Publish TF.
Add differential-drive simulation.
Add LiDAR.
Launch Nav2.
Run waypoint navigation.
Record baseline metrics.
