# ROS_tutorial

### Create workspace directory
```
mkdir ~/ros_tutorial
mkdir ~/ros_tutorial/src
cd ~/ros_tutorial/src
catkin_init_workspace
```

### Download source file
```
cd ~/ros_tutorial/src
git clone git@github.com:moevm/ROS_tutorial.git
```

### Compile
```
cd ~/ros_tutorial
catkin_make
```

### Execution

**Assumes that roscore is already running**

**Run robot_node**
```
cd ~/ros_tutorial
source devel/setup.bash
rosrun ros_tutorial robot_node
```
**Run wasd_node**
```
cd ~/ros_tutorial
source devel/setup.bash
rosrun ros_tutorial wasd_node
```
