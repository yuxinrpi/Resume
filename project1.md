# Sleep Aid Device
## Intro
---
This project is a class project of **MANE-4220 Inventor Studio II** @ RPI. For other Inventor Studio class projects, see [this page](https://www.yuxinhu.ga/project2.html) also.\
Yuxin was the **team leader**, and was in charge of the hardware design and microprocessor programming.
> Sleep Aid Device (SAD) is a circadian rhythm monitoring and adjusting system that helps the user get prepared for sleeping. The system uses IoT technology to collect data and analyze it with Machine Learning on the cloud. Once the user is at the sleepiest moment, the system will suggest the user go to bed, and automatically turn off all electronic devices that may stimulate the user. Using such a device allows people to fix their sleeping schedule and be aware of how important good sleeping can help them to keep healthy.

## Hardware Design
---
<img align="left" src="/project1/design_assem.png" width="500">
<img align="left" src="/project1/design_real.png" width="500" style="margin-bottom: 40px;">

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
    <p style="margin: 0px;">1. Network Time Clock</p>
  </div>
  <div class="column">
    <img src="/project1/soft_2.png" alt="Body temperature" style="width:100%">
    <p style="margin: 0px;">2. Body Temperature</p>
  </div>
  <div class="column">
    <img src="/project1/soft_3.png" alt="Sleepiness Level" style="width:100%">
    <p style="margin: 0px;">3. Sleepiness Level</p>
  </div>
</div>

<div class="row">
  <div class="column">
    <img src="/project1/soft_4.png" alt="Heart Rate" style="width:100%">
    <p style="margin: 0px;">4. Heart Rate</p>
  </div>
  <div class="column">
    <img src="/project1/soft_5.png" alt="Blood Oxygen" style="width:100%">
    <p style="margin: 0px;">5. Blood Oxygen</p>
  </div>
  <div class="column">

  </div>
</div>

<img src="/project1/soft_6.gif" alt="Heart Rate Monitor" style="width:66%" align="top">
<img src="/project1/app.png" alt="Mobile phone app" style="width:33%" align="top">
