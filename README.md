# Smart Farm Application
Creating a simple web application for managing farm motors remotely, allowing farmer to turn them on and off, this app also fetches weekly weather predictions from open APIs and provides real-time weather information from sensors deployed on the farm.

# Project Update: Preliminary Implementation
The project is currently in the initial stages of implementation. Please review the solution idea and architecture details. Check back in one week for the latest updates on the project's progress. Thank you for your interest
## Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation and Usage](#installation-and-usage)
- [Issues and Path for Rev2](#Issues-and-Path-for-Rev2)
- [Conclusion](#conclusion)

## Introduction

**Problem:**  
The farmer faces difficulties in managing a 20-acre farm due to the manual operation of motors that control water distribution across various sections of the land. Furthermore, there is a lack of timely information regarding weather changes when crops are harvested and exposed in the field, leading to uncertainties about potential rain. This lack of real-time control and weather monitoring and predictions adversely affects the overall effectiveness and productivity of the farming processes.

**Solution:**  
Developing a web application to control multiple motors on the farm. The application will provide weekly weather predictions and real-time field data from sensors.  
As part of future development, the plan is to historical data over past 40 years of nearby weather station to generate weekly predictions. Additionally, the system will issue alerts if there is a probability of rain within the next 3 hours based on predictions for decision making.  

**Tech Stack**
- Controller: Master- Raspberry Pi Slave- ESP32
- App development: Python and Python frameworks (yet to update)
- Cloud: AWS

**Architecture:**  
![Architecture](https://github.com/nithishravella10/smart-farm-app/blob/main/smartFarmAppArchRev0.png)
