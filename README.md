# ur5e_hande
ROS/MoveIt! configurations for a UR5e with a Robotiq Hand-E Gripper. This configuration was created by following [this tutorial on roboticscasual.com](https://roboticscasual.com/ros-tutorial-how-to-create-a-moveit-config-for-the-ur5-and-a-gripper/).

## Usage

Bring up the moveit/gazebo demo
```bash
roslaunch ur5e_hande_moveit_config demo_gazebo.launch moveit_controller_manager:=ros_control
```

**_Coming Soon:_**
- Example for opening only moveit without the rviz interface (for planning via python)
- Simple grasp planning (pick and place)
