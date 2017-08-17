# robot_self_filter
Added Indigo devel


## Installing dependencies
Place this repo under your src/ catkin workspace. Navigate to your catkin_ws/src folder then run:
````
rosdep install --from-paths robot_self_filter/ --ignore-src --rosdistro=${ROS_DISTRO} -y
````
Then build your catkin workspace

## Running
````
roslaunch robot_self_filter robot_self_filter.launch
````

This launch file was taken from: https://gist.github.com/mmurooka/e01deaf8a5b4d873977a