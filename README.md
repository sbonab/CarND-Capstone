# Capstone Project
This project implements core functionality of an autonomous vehicle system using ROS. This architecture includes traffic light detection, control, waypoint following, and a drive by wire node.

The following is a system architecture diagram showing the ROS nodes and topics used in the project. 
![image](/imgs/ros-graph.png)


### Usage

1. Clone the project repository
```bash
git clone https://github.com/udacity/CarND-Capstone.git
```

2. Install python dependencies
```bash
cd CarND-Capstone
pip install -r requirements.txt
```
3. Make and run styx
```bash
cd ros
catkin_make
source devel/setup.sh
roslaunch launch/styx.launch
```
4. Run the simulator
