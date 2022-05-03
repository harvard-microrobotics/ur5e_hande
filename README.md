# ur5e_hande
ROS configurations for a UR5e with a Robotiq Hand-E Gripper

## Usage

Bring up the moveit/gazebo demo
```bash
roslaunch ur5e_hande_moveit_config demo_gazebo.launch moveit_controller_manager:=ros_control
```

**_Coming Soon:_**
- Example for opening only moveit without the rviz interface (for planning via python)
- Simple grasp planning (pick and place)