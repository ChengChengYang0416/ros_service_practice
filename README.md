# Sensing and Intelligent Systems : LAB4
1. service server and client practice in ROS
2. Using .launch file to execute nodes together

## Service
1. Git clone and build this project.
	```
	$ git clone https://github.com/ChengChengYang1997/ros_service_practice.git
	$ cd <your workspace>
	$ catkin_make
	```
2. Run the usb_cam_node.
	```
	$ roscore
	$ rosrun usb_cam usb_cam_node _pixel_format:=mjpeg
	```

3. Make sure your image is normal by rviz.
	```
	$ rviz
	```
	in rviz, click 'ADD'->'By Topic'->'Image'. If you see your image in rviz, then you can turn off window of rivz.

4. Run service_server as a server of this service.
	```
	$ rosrun ros_service_practice service_server
	```

5. Run client_call as a client of this service.
	```
	$ rosrun ros_service_practice client_call
	```

## Launch file
```
$ roscore
$ roslaunch ros_service_practice face_detection_server.launch
```
