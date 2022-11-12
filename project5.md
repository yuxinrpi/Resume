<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 50%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>

# Wellness system
## Intro
---
This project is a class project of **ENGR-2050 Intro to Engineering Design** @ RPI. For other Engineering Design class projects, see [this page](https://www.yuxinhu.ga/project6.html) also.\
Yuxin was a **member**, and was in charge of the **Central Controlling System (Electronics)**.\
Please note that the class was taken during the Summer 2020 semester, and due to the impact of COVID-19 outbreak, the class was conducted online, and the project was a virtual project (Only design was required, a functional prototype was not necessary).
> The wellness System is a system that monitors the living condition of indoor environment, and optimizes the environment when necessary. It was designed for typical college students at their dorms suffering from bad air quality, insufficient lighting, and etc.The Wellness System will not only revolutionize how the average college student experiences his or her dorm room at a very stressful point in life, but this product will spark mental health awareness around the globe.

## System Structure
---
The Wellness System incorporates the six components: humidity, air filtration, container, central controlling system, lighting system, and wristband interactivity.  Using these six components, an extremely unique and inventive design was created in order to solve a problem that no companies or designers have paid much attention to.

<img src="/project5/system.png" style="width:40%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

## Central Controlling subsystem
---
Among the six major subsystems, Yuxin was in charge of the **Central Controlling System (Electronics)**. The subsystem design uses an arduino microprocessor.
<img src="/project5/arduino.png" style="width:70%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
The system has multiple sensors to collect the data from ambient environment, including temperature, humidity, air quality, light intensity, and the human detection. Using all the data collected, the current condition can be interpreted, and if it is needed, actions will be made to optimize the condition, for example starting the air purifier, turning on the light, turning on the AC, etc.\
A WiFi module is also installed, and so thus the data flow can be syncronized with the cloud server, allowing the user to view the stats and control the system from the client software.

## UI design
---
An UI was made to help visualize the system status on the device. The pictures below shows the view of the screen installed on the machine. It integrated a Real Time Clock (RTC) which is syncronized with the internet. Also it can display the four sensor data including temperature, humidity, light intensity, and air quality.

<div class="row">
  <div class="column">
    <img src="/project5/screen1.jpg" style="width:100%">
    <p style="margin: 0px;">Time Screen</p>
  </div>
  <div class="column">
    <img src="/project5/screen2.jpg" style="width:100%">
    <p style="margin: 0px;">Calibration Selection</p>
  </div>
</div>
<div class="row">
  <div class="column">
    <img src="/project5/screen3.jpg" style="width:100%">
    <p style="margin: 0px;">Calibration Screen</p>
  </div>
  <div class="column">
    <img src="/project5/screen4.png" style="width:100%">
    <p style="margin: 0px;">Client Software</p>
  </div>
</div>
