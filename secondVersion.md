# Portenta Board Micropython Examples


## Abstract
_Micropython is a relatively new technology in the fields of IoT and Robotics. It accelerates projects prototyping. In this project, a new set of examples will be written for beginners and for those who are new to robotics. In addition providing various examples for many libs. supported by Arduino to make it well documented in Micropython world._

## Technical Details

_Micropython examples can be divided into 5 main categories (Basics - Communication Protocols - IoT - Robotics) in each category a set of examples will be provided_

#### **Basics Examples**
_consists of intro to upython as a language and basic operation can be made by the board_

#### Communication Protocols & Various Sensors Examples
_consists of examples for communication protocols (UART - I2C - SPI) and sensors that uses this protocols like (Magnetometer - IMU - Barometer - External ADC - SD Card)_

#### Robotics Category
_Consists of examples related to robotics like (PID control - Line following robot - ROS communication)_

#### IoT Examples
_consists of examples related to IoT like (HTTP web server - MQTT Server - WiFi communication - fire base)_

|  Basics Examples |Communication Protocols & Sensors | Robotics Examples| IoT Examples  |
|------------------|----------------------------------|------------------|---------------|
|Print Hello world   |UART Example (serial input)|RC car Prototype|  	WiFi communication|
| Led examples|Uart to communicate with another arduino|wall follower Prototype|HTTP server/client|
|Get input from Console|I2C sensors examples (variety of i2c devices like bmp180 - pcf8574 - pca9685)|line follower Prototype|Fire base DB|
|Digital input|spi devices examples (sd card)|ROS examples (topics - msgs - srv)|Use online services like (weather services - sending sms - etc)|
|analog write/read|Display Screen (LCD - tft touch screen - etc.)|interfacing ROS with rc car prototype||
|os module (files i/o - create directories)||||

### Project Hub Examples
_Robots made in Robotics category will be made as Hardware prototypes (RC car - Wall follower - Line follower)_

## Schedule of Deliverable

_As mentioned in the technical details section deliverable can be divided into different phases_
### First Phase
_in this milestone First set of examples (Board Basics) will be delivered and it's estimated to be delivered in a week_

### Second Phase
_in this milestone the Second set of examples (Communication & Sensors Examples) will be delivered and it's estimated to be delivered in (~ 3 : 4 weeks) depends on the the sensors available for me to interface and if it has a micropython libs. available or i have to write it from scratch

### Third Phase
_In the third milestone the third set of examples (Robotics examples) & the Hardware prototypes will be delivered and  it's estimated to be delivered in (~ 2:3 weeks) 

### Fourth Phase
In the Final milestone the last set of examples (IoT & Internet Examples) _will be delivered and  it's estimated to be delivered in a Month_

### Bounce Phase
_In this milestone i will provide a set of tensorflow lite examples but this depends on tensorflow docs to use with micropython. The other milestones if libs. are't available i can implement it but in tensorflow i can't :(_

## Development Experience

In my github there are several examples written by micropython and several libs In addition to  general microcontroller projects in C 
 -  HTTP webserver 
 - uRos (ros implementation to run in micropython **not finished yet**
 - feedback system written in micropython  for ROV (remotely operated vechial) that saves logs from motors and other sensors in json format in SD-card and display samples pf them in a live stream Server (TCP Server - QT GUI)
 - several projects related to ARM development (Tiva-c)
 - Many Robots ( RC car - Line follower - Wall follower ) implemented in Arduino 

## Other Experiences

 - i  was an organizer & Technical Support Head Team in a robotics competition held my faculty (Ain Shams University - Faculty of engineering)
 - ROV software member in Ain shams University Racing Team (we were participating in mate Competition this year but unfortunately it was canceled due to COVID-19 virus)



## Why this project?

_I chose this project as i am very passionate with micropython as it helps non engineering students and hopiests to create and innovate_

## Do you have any other commitments during the GSoC period?

_No i am completely free during this period (5 days a week  8 hours a day)_