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


## Project 3 - Projection & 3D Inverse Kinematics
---
The project expands the project 2 from 2D space to 3D space. The S curve was projected onto a sphere surface, and a 3D inverse kinematics geometric method was implemented. The ABB IRB1200 robot was chosen as the model to track the curve on the surface. Though the inverse kinematics is already implement in the robotics toolbox, the project required to implement the whole method from scratch.

<img src="https://raw.githubusercontent.com/yuxinrpi/Robotics-I-Class-Project/main/Proj-3/S_curve.jpg" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<p style="margin: 0px;" align="middle">S curve on sphere</p>

<img src="/project4/irb1200.gif" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<p style="margin: 0px;" align="middle">IRB1200 tracking the curve</p>
