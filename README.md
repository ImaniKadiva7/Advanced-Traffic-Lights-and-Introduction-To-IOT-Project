# Advanced-Traffic-Lights-and-Introduction-To-IOT-Project

The purpose of this project is to demonstrate my experience in,

- Extending the functionality of the Arduino/ESP8266 bus abitrator.
- Setting up the ESP8266 as an Accesss-point (AP) with Webserver.
- Building a Web-based front-end to drive and monitor a physical system.

The overall objective of this project is to design and implement a multi-functional 
traffic lights system that can be controlled and monitored using a WiFi-enabled device 
such as a laptop or a cell-phone.

Modules that are running concurrently for the Arduino implemented in this project are
- Bus Arbitrator finite state machine project(FSM).
- A traffic lights/pelican crossing controller
- A thermometer and tilt sensor based on the MPU6050.
- A switch-debounce modules.
- A counter module.
- A simple command interpreter.

Modules that are running concurrently implemented in the ESP8266 in this project are,
- A bus arbitrator finite state machine (FSM)
- Module for sending commands / requests to the Arduino to control the traffic lights 
system and to obtain status information.
- Web-based interface for driving the controller and displaying the current status of the physical system.

Traffic Lights Module.

Certain Operations will be configurable via a command set in the traffic lights system. These Operations are as follows,
- Traffic Lights Controller.
- Maintenance Mode.
- Pelican Crossing.
