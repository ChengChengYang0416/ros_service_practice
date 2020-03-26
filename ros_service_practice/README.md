# Sensing and Intelligent Systems : LAB4
1. service practice in ROS
2. Apriltag practice in rviz

## Service Practice in ROS
```
$ git clone https://github.com/ChengChengYang1997/ros_service_practice.git
$ cd ros_topic_practice/bag/
$ roscore
$ rosrun usb_cam usb_cam_node _pixel_format:=mjpeg
$ rosrun ros_service_practice service_server
$ rosrun ros_service_practice client_call
```

```
$ git clone https://github.com/ChengChengYang1997/ros_service_practice.git
$ cd ros_topic_practice/bag/
$ roscore
$ roslaunch ros_service_practice face_detection_server.launch
```

## Apriltag Practice in rviz
```
$ git clone https://github.com/ChengChengYang1997/ros_service_practice.git
$ cd ros_topic_practice/rviz/
$ roscore
$ rosrun ros_topic_practice transform
$ rviz -d tf.rviz
$ rosrun tf tf_echo /B /F
```
