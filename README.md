## Turtle Robot Package

A two wheeled robot with camera and Li-DAR that is powered by ROS2 on a Raspberry Pi and Arduino.

source launch/setup.bash in dev_ws needs to be run before any command such as:
colcon build --symlink-install
ros2 launch my_bot launch_sim.launch.py
