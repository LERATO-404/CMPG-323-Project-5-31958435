# Reporting and Monitoring 
Connected Office Initiative (COI) encapsulates the use of IoT devices
within the network placed over the office building, to collecte and share
data that these devices gather. In this project I create a Report in Power BIwith three pages:
* High-level Metrics - contains the important metrics of the data such as the number of devices in a category/zone
* Device Monitoring - contains the granula details about all the devices or the device drilled from the high-level metric 
* Device Registration - contains details details about all the registered devices or the a sigle device drilled from the high-level metric 

These pages showcase the data that these devices share.  The report can be shared with 
different stakeholders to see important information about the status of the IoT devices 
registration on verious platform.

### Table of Contents
1. [Header](#h)
2. [High-level Metrics](#hlm) <br>
2.1 [drill-through](#drillF) <br>
2.2 [drill-down](#drillB) <br>
3. [Device Monitoring](#dm)
4. [Device Registration](#dr)

<a name="h"></a>      
#### 1. Header <br>
The Header will be visible in all the three reports and it shows:
* Slicers for  device platforms, categories, sub-categories, and zones,
* Total number of online devices, and
* Total number of all the device, categories, sub-categories, and zones.

<img src="Img/Report_Header.png" width=200>>

<a name="hlm"></a>      
#### 1. High-level Metrics <br>
The high-level metric page shows the importance business metrics such as:
* The total number of devices in a specific category/device
* The total number of online and offline devices.

<img src="Img/High_level_Metric.png" width=200>>


<a name="drillF"></a>      
#### 1.1 Drill-Through <br>
For each of the device in the bar chart when clicked a user can drill through (jump to another page) by right clicking the device and easily choose the page the want to navigate to.

<img src="Img/drill_through.png" width=200>>

<a name="drillB"></a>      
#### 1.2 Drill-Down <br>
To drill down (jump back to the high-level metric) easily click on the drill down button shown below

<img src="Img/back_to_hlm.png" width=200>>



<a name="dm"></a>      
#### 2. Device Monitoring <br>
Device monitoring page shows all the registered devices with the status and whether the device is active or not.
* Slicers for status if the device and whether the device is active or not  can be used to filter the data
* When the drill-through is used in the high-level metric to the monitoring page, the page will only show data of the drilled device, and 
* The drill-down button can be used at the bottom left corner to move back to the high-level metric

<img src="Img/Device_Monitoring.png" width=200>>


<a name="dr"></a>      
#### 3. Device Registration <br>
Device registration page all the registered devices with the date the device was installed.
* The line chart shows the total number of devices installed by year
* The metric show the actual date the device was installed

<img src="Img/Device_Registration.png" width=200>>

#### Help and Support<br>
---
 * marijkec
 * JacquiM