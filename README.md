# package_name

## Purpose of this software
This ROS2 Foxy template package is used to create new publisher / subscriber packages. It's used to avoid blank page problems.

## Disclaimer
This project is under developpement and may change according to my ideas.

## Installation & Contribute
To run this package you will need ROS 2 Foxy installed on your system. You may clone this repo into your `src/` workspace's folder.

```bash
source /opt/ros/foxy/setup.bash

cd ~
mkdir -p dev_ws/src
cd dev_ws/src
git clone https://github.com/aiRCS-Lab/ros2-foxy-pubsub-template.git
cd ../
colcon build --symlink-install
source install/setup.bash

ros2 run package_name talker
ros2 run package_name listener
```

## How to use

You should modify `package_name` in CMakeLists.txt and in package.xml.