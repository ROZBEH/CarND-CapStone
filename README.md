# CarND-Path-Capstone-Project

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)



<p align="center">
<img src="mygif.gif" width = "600" />
</p>


Overview
---


I this project vehicle drives in a simulation environment autonomously without human intervention. Plus, the vehicle has to stop on the traffic signals. The fundamental codes used in this project is based on Capstone project walkthrough at Udacity Self Driving Cars online course.


Pipeline
---


*The overall pipeline along with the results will be described here!*

<br>

I. Base of the source code that I've used for this project is inspired by the walkthrough session hosted by Aaron and Steven.


</br>


II. The main source codes are inside```CarND-CapStone/ros/src/``` folder. Most of the blocks and parts have been provided by Udacity and we just had to fill up specific functionalities and make sure that the car can go around route and stop at the traffic signals. The codes that has been modified and added in this project incude: 
- ```CarND-CapStone/ros/src/waypoint_updater/waypoint_updater.py```
- ```CarND-CapStone/ros/src/twist_controller/twist_controller.py```
- ```CarND-CapStone/ros/src/```
- ```CarND-CapStone/ros/src/tl_detector/tl_detector.py```
- ```CarND-CapStone/ros/src/tl_detector/light_classification/tl_classifier.py```
- ```CarND-CapStone/train.py```


include other codes according to the walk through
add train.py
talk about where is tensorflow model
talk about setting up the right directory inside the tl_classifier
Consider the notes on the A4 paper


</br>

III. In 


IV. Here I try to talk about some of the important variables that were used in the code.

- ```too_close``` is a boolean variable that

- ```turn_right``` and ```turn_left``` are t

- ```right_side``` and ```left_side``` are  

- ```margine_left``` ```margine_center``` ```margine_right``` . 

IV. Make sure include the ```dbw_mkz_msgs``` folder inside ```src``` folder when you are running the code. It is provided by Udacity as part of the project.

V. Lastly, be sure for your system to have at least a 5 core cpu and a good GPU specially when you turn on the camera on the simulator. The car runs smoothly around the block in autonomous mode without camera turned on. But when you turn on the camera, the car might steer off the road if you're system hardware are not strong enough.  

</br>
<br></br>