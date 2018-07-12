# turtlebot_exploration
Contains launch files that launch the Turtlebot (both for master and host pc) for Frontier Exploration and RRT Exploration. 

To conveniently install this package along with the source code of RRT Exploration and Frontier Exploration, follow these instructions:

1. Make sure that wstool is installed

```sudo apt install python-wstool```

2. Create a new catkin_workspace

```
mkdir ~/exploration_ws
cd ~/exploration_ws
```

3. Use wstool to install the packages

```
wstool init src https://raw.githubusercontent.com/nfopma/turtlebot_exploration/master/turtlebot_exploration.rosinstall
```

4. Compile and source the workspace

```
catkin_make
source devel/setup.bash
```




