# BlueROV ROS

# Installation


## Dependencies

## ROS dependencies
```bash
sudo apt install ros-DISTRO-mavros*
```

## Geographic Dependencies
Clone the mavros ros packages
```bash
https://github.com/mavlink/mavros.git
```

Install the geographic dependencies:
```bash
cd mavros/mavros/scripts
./install_geographiclib_datasets.sh
```


## Install this package

```bash
cd ~/catkin_ws/src
git clone https://github.com/USYD-RowBot/bluerov_ros.git
cd ..
catkin_make
```


# Run Mavros

```bash
cd ~/catkin_ws
source devel/setup.bash
roslaunch bluerov_ros bluerov_px4.launch
```



