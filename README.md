# Smart-Health-Monitoring-System-Using-IBM-Cloud

# Introduction

Creating Smart Health Monitoring System Using IOT. The
Internet of Things (IOT) is how we describe the digitally connected universe of everyday
physical devices. These devices are embedded with internet connectivity, sensors and other hardware that allow communication and control via the web.



## File contains:- 

### 1.(Project2) Code.py

This python file contain the main code of the project which includes IBM Cloud IOT service with device credentials.Here in this code we are generating randoms values for temperature and pulse value.In real time we were using microprocessor to detects real time readings from sensor.along with this, fast2sms service is used to send the notification at an emergency case to anyone.


### 2.Node-Red Flow.json

This json code contain Node-Red flow connections used for this project.Basically this is used for (web application). Node-Red is the service given by the IBM Cloud platform. Here this service fetching the data from the cloud. 

### 3.smart_Health Monitoring.apk
MIT app inventor is an online platform through which we can build our Mobile app.
For the end user we cannot provide the IBM IOT Credentials. So for that we need to develop an application where we can see our data. the data is being updated from Node-Red application. 

## Working:- 

The code generates the real time sensor reading which will be send to the cloud with the help of IBM IOT platform and will get IBM Watson Device credentials which are used in code for sending the data in IBM cloud.Then we created Node-red application service from IBM software and make connection through nodes to fetch the sensor data from the code and also use Dashboard node for creating UI (Web App). Now with help of HTTP node data are to store in URL. Through Node-red and this data will useful for fetching data for mobile app through MIT APP inventor. After that we can see the real time readings anywhere in mobile app.  

Please go through the file for more detail:-

 
