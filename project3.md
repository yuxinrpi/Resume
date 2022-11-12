# Duckiebot Auto Parking system
## Intro
---
This project is a class project of **CSCI-4480/MANE-4480 Robotics I** @ RPI. For other Robotics class projects, see [this page](https://www.yuxinhu.ga/project4.html) also.\
Yuxin was the **team leader**, and was in charge of Computer Vision.

> Automatic parking is a feature of growing interest that has been implemented in an increasing number of vehicles. It has the potential to be very useful to many different people and if implemented properly could be beneficial in small ways like stopping superficial nicks and scratches to large ways like preventing major costly damage to the driver’s vehicle and others.

>Our goal was to utilize the sensor provided with the [duckiebot](https://www.duckietown.org/) to obtain imagery of the surrounding area, process these images to locate a parking spot, and then implement a control system to navigate the duckiebot to the parking space and park on top of it. This report discusses our implementation and results.

## Setup
---
The duckiebot is a 2 wheel differential robot controlled by Raspberry Pi. The wheels on the side can be controlled to rotate independently, and hence the duckiebot can control the speed and angular speed.
<img src="/project3/duckie.png" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

To achieve the auto-parking goal, the system was divided into two halves, where Yuxin was in charge of the Computer Vision processing.
<img src="/project3/structure.png" style="width:70%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

The image was captured by the camera located on the duckiebot, and then it was transferred to the remote computer for further processing. The main goal is to locate the parking box, and find the relative distance and angle using perspective-to-perspective algorithms.
<img src="/project3/CV.png" style="width:100%">

Then a map was reconstructed to help visualize the process. It marks the duckiebot's position and the location of the parking space.
<img src="/project3/map.png" style="width:30%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

An simple user interface was made to connect the Computer Vision component with the motion control subsystem.
<img src="/project3/UI.png" style="width:100%">
<img src="/project3/demo.gif" style="width:100%">

## Demo
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/X_UbM8Cd_Lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
