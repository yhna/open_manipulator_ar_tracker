# open_manipulator_ar_tracker uinsg astra pro

## Download
```
$ cd ~/catkin_ws/src
$ git clone https://github.com/orbbec/ros_astra_camera.git
$ git clone https://github.com/yhna/ros_astra_launch.git
$ git clone https://github.com/yhna/open_manipulator_ar_tracker.git
```

## Installation
```
$ sudo apt-get install ros-kinetic-rgbd-launch ros-kinetic-libuvc-camera ros-kinetic-ar-track-alvar
$ cd ~/catkin_ws && catkin_make
$ roscd astra_camera && ./scripts/create_udev_rules
```
## Execution
```
$ roslaunch astra_launch astrapro.launch
$ roslaunch open_manipulator_ar_tracker open_manipulator_ar_tracker.launch
```
