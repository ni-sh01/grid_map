# Sensor Data Fusion - Grid Mapping using ROS2

## Project Overview
This project implements probabilistic grid mapping using LaserScan data in ROS2. The sensor data fusion approach helps in visualizing occupancy grids and detecting obstacles based on LiDAR sensor readings.

1.Generation of a chess board as grid map 
2.Generation and Visualization of a gridmap based on a laser scanner sample 
3.Generation and Visualization of a gridmap based on a laser measurement (from rosbag)

## Part 1
Clone the Repository


Build the Package

```
cd ~/dev_ws
colcon build --packages-select sensor_data_fusion
source install/setup.bash

```

