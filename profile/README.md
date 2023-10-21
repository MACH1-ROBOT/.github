# Mach1 Robot Project

## Project Overview

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

The **Mach1 Robot Project** is the central hub for all things related to the Mach1 Project which including the robotics and programming aspects. It serves as a platform for learning, experimentation, and development while showcasing my proficiency in designing, building, and programming a versatile and intelligent robot.

In addition to the robotics and software components, a web development side of the project is in the works. This web development aspect aims to complement the Mach1 Project by providing a web-based interface or additional functionalities.

For detailed instructions on setting up the Mach1 robot, including software installations, hardware setup, and valuable references, you can refer to the [Mach1 Robot Manual](https://docs.google.com/document/d/1Pno_UG_DZj2e02880ajYniiNrQvAm-NTgAf_Zc9F8Js/edit#heading=h.6lbqthww4bvw). Please note that the manual is a work in progress, and I'm actively working on gathering all the information to provide a comprehensive guide for configuring the robot.

## ROS Packages

The Mach1 Robot Project includes the following ROS packages, each tailored to fulfill specific roles. These packages can be found under the [`Mach1 Robot Project ROS Packages`](https://github.com/MACH1-ROBOT/mach1_code) repository, which houses all the ROS-related code.

### Mach1 Bringup Package
- **Overview**: Responsible for configuring and setting up the Mach1 robot, this package contains the necessary files and configurations required to initialize the robot within the ROS environment.
- **Author & Maintainer**: Julian Rendon (julianrendon514@gmail.com)
- **Repository**: [Mach1 Bringup Package](https://github.com/jrendon102/mach1_bringup)

### Mach1 Hardware Package
- **Overview**: Designed to control the Yahboom 4WD expansion board for the Mach1 robot, this package serves as a communication and control interface for managing the hardware components of the robot.
- **Author & Maintainer**: Julian Rendon (julianrendon514@gmail.com)
- **Repository**: [Mach1 Hardware Package](https://github.com/jrendon102/mach1_hardware)
- **Sub-Packages**:
  1. [Camera Driver](https://github.com/jrendon102/camera_driver): A C++ library for interacting with standard cameras.
  2. [gpiozero_plus](https://github.com/jrendon102/gpiozero_plus): A Python library for controlling hardware components.

### Mach1 Msgs Package
- **Overview**: This package contains custom message (msg), service (srv), and action (action) files for the Mach1 robot. These custom definitions are kept in a separate package for independent compilation and importation into other packages as needed.
- **Author & Maintainer**: Julian Rendon (julianrendon514@gmail.com)
- **Repository**: [Mach1 Msgs Package](https://github.com/jrendon102/mach1_msgs)

### Mach1 Navigation Package
- **Overview**: Provides navigation logic for the Yahboom G1 Tank mobile robot. It includes ROS nodes to control the robot's motion based on various inputs such as joystick controllers, sensor data, and environment maps.
- **Author & Maintainer**: Julian Rendon (julianrendon514@gmail.com)
- **Repository**: [Mach1 Navigation Package](https://github.com/jrendon102/mach1_navigation)

### Mach1 Simulation ROS Package
- **Overview**: Offers a comprehensive simulation environment for the Mach1 robot, including a 3D model of the robot, configuration files, and launch files for visualization and simulation within the ROS framework.
- **Author & Maintainer**: Julian Rendon (julianrendon514@gmail.com)
- **Repository**: [Mach1 Simulation ROS Package](https://github.com/jrendon102/mach1_simulation)

### ROS Utils Package
- **Overview**: A C++ library designed to simplify ROS development by providing utility functions for common ROS tasks, a versatile template class for message handling, and custom exception classes for improved error handling.
- **Author & Maintainer**: Julian Rendon (julianrendon514@gmail.com)
- **Repository**: [ROS Utils Package](https://github.com/jrendon102/ros_utils)

## Mach1 Robot Docker Configuration

This project also integrates a Docker configuration repository tailored for the Mach1 Robot Project. This repository, [Mach1 Robot Project - Docker Configuration](https://github.com/jrendon102/mach1_docker), provides the necessary Docker configuration files and scripts to set up Docker containers for the Mach1 Robot Project. The Docker containers facilitate the deployment of various robot software components, ensuring portability and ease of use across different environments.

For specific instructions on using this repository, please refer to the [Mach1 Robot Project - Docker Configuration README](https://github.com/jrendon102/mach1_docker#readme).

## License

All the ROS packages in this project are released under various licenses, including the MIT License. Please check the specific package's README or LICENSE file for more details on licensing.

## Author & Maintainer

This personal project is authored and maintained by me, Julian Rendon. If you have questions, require support, or need further information about any of the packages, you can reach out to me via email at julianrendon514@gmail.com.
