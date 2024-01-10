# FritzRobot
## Description
A autonomated mecnum-wheeled robot. 

https://github.com/Utschie/FritzRobot_control/assets/33782458/aa32b7f8-7650-4b97-a6c7-4735f200c06d

- Host computer: Nvidia Jetson nano

- Slave computer: STM32F427IIH6

- Environment: Ubuntu 20.04, ROS Noetic, Docker  

- Sensor: RGBD camera

This project consists of the following packages

+ [`FritzRobot_description`](https://github.com/Utschie/FritzRobot_description): The robot's model files and visualization configs, etc.

+ [`FritzRobot_control`](https://github.com/Utschie/FritzRobot_control): The robot's moving control nodes(automated and manual), including the maps and move_base's configuration, etc.

+ [`FritzRobot_firmware`](https://github.com/Utschie/FritzRobot_firmware): The robot's underlying control components based on STM32F427IIH6 and HAL library. 

+ [`FritzRobot_serial`](https://github.com/Utschie/FritzRobot_serial): The communiction nodes on the host computer and orientation estimation(Extended Kalman Filter) nodes.

+ [`FritzRobot_docker`](https://github.com/Utschie/FritzRobot_docker): The dockerfiles, entrypoint files, and docker-compose configurations.

to be continued......
