# **Project Portfolio**

# **USpeed**

**Table of Contents**

1. [Introduction](introduction)

1. [Project Requirements](project-requirments)

1. [Design Decisions](design-decisions)

1. [Diagrams](diagrams)

## **Introduction**
---
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTKs7RSUFDZYTFxcqV2flxoJa9r-w5vJbFKMw&usqp=CAU"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStO-flYDzXFhrKSiv7PpvVL_RQl_c8Rtm0Ng&usqp=CAU" style="width: 50%">

This was a senior capstone project taking advantage of a Raspberry Pi as well as a SenseHat in order to monitor speed and location for users to monitor and view.

## **Project Requirements**
---
- [x] RestApi Backend for user modules

- [x] RestApi Backend for routing modules

- [x] Multi-Threaded Functionality for the raspberry pi

- [x] Simple user experience

- [x] User controlled toggle for tracking services

- [x] Connecting to back-end api from the raspberry pi

- [x] Visable Display for speed on the raspberry pi

- [x] Raspberry Pi runs self contained(I.e on battery power)

- [x] Previously taken routes can be viewed on a google map

## **Design Decisions**
---

| Technology | Reasoning |
| :-------: | :-------: |
| RaspberryPi 4B | This was chosen to avoid any memory issues you could find with an arduino. |
| SenseHat | This was used for the integrated accelerometer and other sensors that can be used in the future. | 
| Adafruit Ultimate GPS | This was chosen as it has a high accuracy rating and has a integrated antena | 
| Spring Boot | Spring boot was the back end of choice for this project as it is a widly used and highly advantagous framework with plenty of features to build on. |
| Python3 | Python was used for the operation script as it works well with embedded systems and is a great scripting language. |
| VNC Viewer | VNC Viewer was used to connect to the raspberry pi to develop on it. This allowed for the pi to remain headless. | 
| Google Api | The google api is used to display the routes and is free up to a certain amount of marks | 
<details>
    <summary><b>Design Decisions Summary</b></summary>
    The technology chosen was all to help compliment eachother and were all technologies that worked well when paired togther. The RaspberryPi SenseHat was specifically designed to work on the Pi 4B and Python has libraries for the operation of the said hat. The Adafruit Ultimate GPS also was specifically made to operate with the raspberry pi, as they have another model that used pin outs instead of a standard usb connection, making the integration much simpler. Raspbian(The default OS on the pi) also has a VNC integration that makes it easy to connect to from all your machines. Spring Boot was used to create the api back end for the web site because it is an excellent framework that supports rest api creation as well as offers great security features. Lastly the google api was used for the map creation as it is simple and cheap to use. It is standard javascript and free credits are received every month so it allows for the application to run cheaply.
</details>

---
## **Diagrams**







