# hector_slam_demos

## How to use hector_slam_demos

Download this demos from ```github``` use following command:
```
$ cd <your_catkin_workspace>/src
$ git clone http://github.com/Playfish/hector_slam_demos.git
$ #checkout depends whether install or not
$ rosdep install --from-paths src --ignore-src --rosdistro indigo -y 
$ catkin_make
```

After installing dependency package you can run r200_demo.launch, and also at first you have install ```hector_slam``` package.

``` $ roslaunch hector_slam_demos r200_demos.launch ```
