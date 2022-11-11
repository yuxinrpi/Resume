# Robotics Class Demo Collection
## Intro
---
This page collects the demo of Robotics I class mini projects. You can also view the project at [My GitHub Page](https://github.com/yuxinrpi/Robotics-I-Class-Project)\
All class mini projects are done by me alone.

<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>

## Project 1 - Simple Path Planning
---
The project aims at developing a program that finds a path for the robot to reach its destination without colliding with any barrier.
<img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-1/path.jpg" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

## Project 2 - 2D Inverse Kinematics
---
The project aims at developing a inverse kinematics algorithm with both geometric and jacobian control method for a 2D n-link robot to track a curve. Though the inverse kinematics is already implement in the robotics toolbox, the project required to implement the whole methods from scratch.

<div class="row">
  <div class="column">
    <img src="/project4/3link.gif" style="width:100%">
    <p style="margin: 0px;">3 Link Robot - Geometric</p>
  </div>
  <div class="column">
    <img src="/project4/10link.gif" style="width:100%">
    <p style="margin: 0px;">10 Link Robot - Jacobian</p>
  </div>
  <div class="column">
    <img src="/project4/100link.gif" style="width:100%">
    <p style="margin: 0px;">100 Link Robot - Jacobian</p>
  </div>
</div>


## Project 3 - Projection & 3D Geometric Inverse Kinematics
---
The project expands the project 2 from 2D space to 3D space. The S curve was projected onto a sphere surface, and a 3D inverse kinematics geometric method was implemented. The ABB IRB1200 robot was chosen as the model to track the curve on the surface. Though the inverse kinematics is already implement in the robotics toolbox, the project required to implement the whole method from scratch.

<img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-3/S_curve.jpg" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<p style="margin: 0px;" align="middle">S curve on sphere</p>

<img src="/project4/irb1200.gif" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<p style="margin: 0px;" align="middle">IRB1200 tracking the curve</p>

## Project 4 - 3D Jacobian Inverse Kinematics
---
Compared to Project 3, the project 4 implements the jacobian inverse kinematics method, and the effects of singularities are evaluated and discussed.
<img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-4/jacmotion.jpg" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<p style="margin: 0px;" align="middle">Jacobian Inv-kinematics tracking</p>

<img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-4/singularvalue.jpg" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<p style="margin: 0px;" align="middle">Singular Value of Robot - No singularities</p>

## Project 5 - Camera Calibration
---
The projects implemented a virtual camera using mathematical projections. And a camera fixed at the tip of a robot was simulated, where it's intrinsic and extrinsic parameters were found using calibration methods.

<div class="row">
  <div class="column">
    <img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-5/xc2.5_Sphere.png" style="width:100%">
    <p style="margin: 0px;">Camera's View of the S curve</p>
  </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-5/image.png" style="width:100%">
    <p style="margin: 0px;">2D Reprojection After Calibration</p>
  </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-5/reprojection.png" style="width:100%">
    <p style="margin: 0px;">3D Reprojection After Calibration</p>
  </div>
</div>

## Project 6 - PID Tuning & Gravity Compensation
---
The project applies PID tuning method for the Robot to track the S curve using Simulink. Each part of the robot was added with gravity and friction, and then then gravity compensation algorithm was implemented to counteract the effect of gravity.

<div class="row">
  <div class="column">
    <img src="/project4/no_friction.gif" style="width:100%">
    <p style="margin: 0px;">Camera's View of the S curve</p>
  </div>
  <div class="column">
    <img src="/project4/friction.gif" style="width:100%">
    <p style="margin: 0px;">2D Reprojection After Calibration</p>
  </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-5/reprojection.png" style="width:100%">
    <p style="margin: 0px;">3D Reprojection After Calibration</p>
  </div>
</div>
