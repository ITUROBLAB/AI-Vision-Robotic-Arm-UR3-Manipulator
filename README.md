# AI Vision Robotic Arm

### Download and *catkin_build* the workspace from the following google drive link:

[https://drive.google.com/drive/folders/1_fm-76ssSWaek-zHXyguayZRqjlS_V-i?usp=sharing](https://drive.google.com/drive/folders/1_fm-76ssSWaek-zHXyguayZRqjlS_V-i?usp=sharing)

Any dependency can be installed from [synaptic package manager](https://itsfoss.com/synaptic-package-manager/).

To launch Gazebo:

```bash
roslaunch ur3_gazebo ur_gripper_85_cubes.launch grasp_plugin:=1
```

To launch RViz:

```bash
roslaunch ur_gripper_85_moveit_config start_moveit.launch
```

To launch the perception node:

```bash
roslaunch simple_grasping basic_perception_dbg.launch
```

### References

1) [GitHub - cambel/ur3: ROS-based UR3/UR3e controller with simulation in Gazebo. Adaptable to other UR robots](https://github.com/cambel/ur3)

2) [GitHub - UniversalRobots/Universal_Robots_ROS_Driver: Universal Robots ROS driver supporting CB3 and e-Series](https://github.com/UniversalRobots/Universal_Robots_ROS_Driver)

3) [GitHub - ros-industrial/universal_robot at melodic-devel](https://github.com/ros-industrial/universal_robot/tree/melodic-devel)

4) [Getting Started with a Universal Robot and ROS-Industrial](http://wiki.ros.org/universal_robot/Tutorials/Getting%20Started%20with%20a%20Universal%20Robot%20and%20ROS-Industrial)

5) [GitHub - trabelsim/UR3_with_Robotiq_gripper_85: This project has been developed with the goal of creating a system to control the cobot. Here the Cobot UR3 Series with the attached gripper can be controlled from Rviz as as well from the terminal by using scripts written in python.](https://github.com/trabelsim/UR3_with_Robotiq_gripper_85)

### Notes:

The first reference listed above is the most important since it has a map that shows where the important nodes should be located.

For any enquiry you can mail us at [LinkedIn](https://www.linkedin.com/in/samer-raed-a-068133ab/).

### Research paper:

[KON4902E_Final.pdf](AI%20Vision%20Robotic%20Arm/KON4902E_Final.pdf)

### Simulations:

Found in the [Powerpoint file](https://ituedutr-my.sharepoint.com/:p:/g/personal/hassaneinm18_itu_edu_tr/EYlx56oSNS1Hhd5pFUdge34B76VQJorgT_WdJFdxJziscA?e=S8ihE1).

## *Made by Samer Raed Aldabbas and Moustafa Hassanein.*
