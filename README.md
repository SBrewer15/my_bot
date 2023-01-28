## Turtle Robot Package

A two wheeled robot with camera and Li-DAR that is powered by ROS2 on a Raspberry Pi and Arduino.

source install/setup.bash in dev_ws needs to be run before any command such as:
colcon build --symlink-install
ros2 launch my_bot launch_sim.launch.py world:=./src/my_bot/worlds/obstacles.world
ros2 run teleop_twist_keyboard teleop_twist_keyboard
rviz2
ros2 run teleop_twist_joy --teleop_node
ros2 run teleop_twist_joy --joy_node