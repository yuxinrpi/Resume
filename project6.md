# Transportation Challenge
## Intro
---
This project is a class project of **ENGR-2050 Intro to Engineering Design** @ RPI. For other Inventor Studio class projects, see [this page](https://www.yuxinhu.ga/project5.html) also.\
Yuxin was the **team leader**, and was in charge of the mathematical model.
Please note that the class was taken during the Summer 2020 semester, and due to the impact of COVID-19 outbreak, the class was conducted online, and the project was a virtual project (Only design was required, a functional prototype was not necessary).\

# Problem
---
> In light of COVID-19, more N95 masks and Hamilton C3 ventilators are needed in affected areas now more than ever. A transportation company needed to carry a load of these medical supplies via truck from the Port of San Diego to Albany Medical Center (2441 Miles).  The transportation company wanted to minimize travel time and maximize supplies delivered. It was important to transport these medical supplies efficiently because various medical companies, hospitals, and state and local governments need them to protect against COVID-19.  For this trip the weather, driver needs, and Trucking Rules and Regulations were ignored. It was expected that the amount of ventilators and masks transported would be maximized between the Ford T150 and an attached U-Haul trailer.

# Vehicle Selection
---
In the problem statement, a Ford T150 van, and a U-Haul trailer was given. And their specifications are shown below.
<img src="/project6/vehicle.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

# Fuel Consumption Modeling
---
To model the Fuel Consumption of the vehicle and thus make sure the vehicle arrives without adding gas in halfway, the mathematical model below were introduced.
<img src="/project6/model1.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<img src="/project6/model2.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

And since the Ford T150 van uses a gasoline engine, the engine efficiency varys under different conditions and cannot be simply determined. To solve this problem, the team researched on the thermal efficiency, and luckily a test source was found. As shown below, the vehicle operates at maximum thermal efficiency @ 60-80 MPH.
<img src="/project6/model4.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

After pluging in the weight and engine efficiency to our model, suprisingly we found the actual experimental data was very close to our prediction. (Error < 5%)
<img src="/project6/model3.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

# Cargo Arrangement
---
The problem statement asks for maximum amount of cargo to be carried. The team decided to find a solution that maximizes both the cargo weight and cargo volume. The optimal solution was found to be 30% masks and 70% ventilators by weight.\
Using some tools, the arrangement in the van cabin and trailer is shown below.
<img src="/project6/cargo1.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
<img src="/project6/cargo2.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

# Results
---
With the vehicle MPG model and cargo arrangement above, the model shows that the vehicle is able to travel @72MPH with 3869lb payload at maximum speed. If the speed lowers to 54MPH, the maximum payload is 4015lb.
<img src="/project6/model5.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
