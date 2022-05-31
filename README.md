# ur5e_hande
ROS/MoveIt! configurations for a UR5e with a Robotiq Hand-E Gripper. This configuration was created by following [this tutorial](https://roboticscasual.com/ros-tutorial-how-to-create-a-moveit-config-for-the-ur5-and-a-gripper/) from Robotics Casual.

## Installation
1. Install campbel's [robotiq](https://github.com/cambel/robotiq/tree/noetic-devel) package.
2. Install fmauch's [universal_robot](https://github.com/fmauch/universal_robot/tree/calibration_devel) package.

```bash
git clone -b noetic-devel https://github.com/cambel/robotiq.git
git clone -b calibration_devel https://github.com/fmauch/universal_robot.git
```

## Usage

Bring up the moveit/gazebo demo
```bash
roslaunch ur5e_hande_moveit_config demo_gazebo.launch moveit_controller_manager:=ros_control
```

**_Coming Soon:_**
- Example for opening only moveit without the rviz interface (for planning via python)
- Simple grasp planning (pick and place)
