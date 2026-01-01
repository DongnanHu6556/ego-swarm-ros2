# ego-swarm-ros2
The repository comes from https://github.com/legubiao/ego-swarm-ros2, I revised the "qos" in grid_map.cpp and add my own ego planner launch files.
```
mkdir -p ego_ws/src
cd ego_ws/src
git clone https://github.com/DongnanHu6556/ego-swarm-ros2.git
cd ..
colcon build
```
Then you can launch the planner:
```
source install/setup.bash
ros2 launch ego_planner single_uav_gazebo.launch.py
```
Launch rviz:
```
ros2 launch ego_planner rviz.launch.py 
```
