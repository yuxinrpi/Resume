# Sleep Aid Device
## Intro
---
This project is a class project of MANE-4220 Inventor Studio II taught @ RPI.
Yuxin is the team leader, and was in charge of the hardware design and microprocessor programming.
---
Sleep Aid Device (SAD) is a circadian rhythm monitoring and adjusting system that helps the user get prepared for sleeping. The system uses IoT technology to collect data and analyze it with Machine Learning on the cloud. Once the user is at the sleepiest moment, the system will suggest the user go to bed, and automatically turn off all electronic devices that may stimulate the user. Using such a device allows people to fix their sleeping schedule and be aware of how important good sleeping can help them to keep healthy.
## Hardware Design
---
<img align="left" src="/project1/design_assem.png" width="500">
<img align="left" src="/project1/design_real.png" width="500">

## Software Design
---
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
<div class="row">
  <div class="column">
    <img src="/project1/soft_1.png" alt="Time page" style="width:100%">
  </div>
  <div class="column">
    <img src="/project1/soft_2.png" alt="Body temperature" style="width:100%">
  </div>
  <div class="column">
    <img src="/project1/soft_3.png" alt="Sleepiness Level" style="width:100%">
  </div>
</div>
<div class="row">
  <div class="column">
    <img src="/project1/soft_4.png" alt="Heart Rate" style="width:100%">
  </div>
  <div class="column">
    <img src="/project1/soft_5.png" alt="Blood Oxygen" style="width:100%">
  </div>
  <div class="column">
  <p>Five info screens</p>
  <p>1. Network Time Clock</p>
  <p>2. Body Temperature</p>
  <p>3. Sleepiness Level</p>
  <p>4. Heart Rate Monitor</p>
  <p>5. Blood Oxygen Monitor</p>
  <p>Results can be plotted as below</p>
  </div>
</div>
<img src="/project1/soft_6.gif" alt="Heart Rate Monitor" style="width:100%">
