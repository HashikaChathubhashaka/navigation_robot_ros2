# ROS2 Navigation Simulation Robot

## Overview

This project is a ROS2-based simulation of a navigation robot. The robot is designed to navigate through an environment using the ROS Navigation Stack.

## Prerequisites

Before you can run this simulation, make sure you have the following installed:

- ROS2: Follow the [official installation instructions](https://index.ros.org/doc/ros2/Installation/) to install ROS2 on your system.
- Gazebo: Install Gazebo, the simulation environment used in this project. You can follow the installation instructions on the [Gazebo website](http://gazebosim.org/install).

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. Build the workspace:

    ```bash
    colcon build
    ```

3. Source the workspace:

    ```bash
    source install/setup.bash
    ```

4. Launch the simulation[navigation though premade map - map is already saved]:

    ```bash
    ros2 launch my_robot_bringup my_robot_gazebo.launch.xml
    ```

## Usage

- To control the robot manually, you can use the ROS2 `teleop_twist_keyboard` package:

    ```bash
    ros2 run teleop_twist_keyboard teleop_twist_keyboard
    ```


## After Runing the Launch file 


## License



## Acknowledgments

- nav2
- xacro
- slam_toolbox



## Issues





## Acknowledgments


