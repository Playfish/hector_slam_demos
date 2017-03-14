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

### R200 Demo
Just use following command for run r200 demo.

``` 
$ roslaunch hector_slam_demos r200_demo.launch
```

### Astra Demo
Just use following command for run astra demo.

``` 
$ roslaunch hector_slam_demos astra_demo.launch 
```


### Kinect Demo
Just use following command for run kinect demo.

``` 
$ roslaunch hector_slam_demos kinect_demo.launch 
```
