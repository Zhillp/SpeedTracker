# SpeedTracker Build Instructions
#### note pictures will be added later 

## Introduction
The SpeedTracker is a project that allow users to get the acceleration on the x,y and z axis along with the gyroscope position on these axises, also with the acceleration and gyroscope the SpeedTracker will also gather the location information using the GPS it has. The SpeedTracker project is meant to gather the results of the acceleration and gyroscope sensor and calculate the total acceleration and the gyroscope position of the sensor. This will be a tutorial on how to make and set up this SpeedTracker project. 

## System Diagram
The System diagram of how the SpeedTracker will work alongside the database that will be operational in the near future:


## What you will need
These are the all materials and tools you will need to successfully complete this project:
Breadboard 
Jumper wires
Raspberry Pi 3
Adafruit LSM9DS0 Acc/Gyro/Mag 9-DOF breakout board
Adafruit Ultimate GPS featherwing 
Soldering iron
Solder
Safety goggles
Stackable header pins 
MicroSD to USB converter

These are helpful skills that can come in handy for this project:
Raspberry Pi knowledge 
Breadboarding and wiring knowledge 
Soldering 

## Cost of Materials 


## Time Commitment
The SpeedTracker project does not take that much time to complete the whole project assuming you get all of the materials on time. The project can take a day or two to complete depending on how well you understand the code and the set up of the project. The bulk of this assignment will come from the assembly of the case and the PCB design. 



## Raspberry Pi setup
To help with setup the raspberry pi, you will need a monitor that works with an HDMI cable, a wired USB and mouse to work on the raspberry pi:

#### Step 1 
On your own PC download the latest version of the raspberry pi Raspbian operating system from the Raspberry pi website. The link of the website of the raspbian operating system below
https://www.raspberrypi.org/downloads/raspbian/

#### Step 2
Format the microSD card by putting it into a microSD card to USB converter and plug it into your PC then format with the Raspbian operating system using a application like Rufus
https://rufus.ie/en_IE.html

#### Step 3 
Put the microSD card into the microSD card slot in the raspberry pi and start up the raspberry pi and connect the HDMI cable to a monitor, the mouse and keyboard to with the raspberry pi

#### Step 4
After the initial start up of the raspberry pi, we would need to enable the I2C and VNC interfaces, we do this by going on the start menu, then preferences then raspberry pi configurations then interfaces and check VNC and I2C to enabled. 

## Hardware Assembly
Once you gained the the sensors, in the package the sensors come in, there will be these headers pins that will be able to fit into the sensor. You solder those pins to the sensors then when they are all soldered on you can plug them into a breadboard and wire it up to the raspberry pi. On the raspberry pi, you can do the command ```sudo i2cdetect -y 1``` to show if the raspberry pi can detect the accelerometer sensor. Once the connections are fine and working you can move on to the PCB design. 

## PCB 
The application that can help make the PCB design is fritzing, the application download can be viewed below. Since the application does not have the library for that my sensor, I had to google the library and import it into fritzing. From there I inputted the sensors into the design and added the vias for the board. I made the connections with the raspberry pi and the sensors. Once the board has been made, I stripped a wire and soldered it on the vias and then I soldered the stackable header pins for the pins for the raspberry pi and the sensors. 
http://fritzing.org/download/

## Case 
For the case part of the project, you can do two things to make the case more accomodating for the raspberry pi with the PCB board on. The first thing you can do to make the case is find a case on thingiverse and 3d printed, I found a case on thingiverse that can be viewed below. The other thing that be done to make the case, is to use the application CorelDraw to design a case and acrylic. 
https://www.thingiverse.com/thing:2962525/files

## Testing
It will be useful to test the hardware before you get to the software part of the project. After soldering on the header pins to the sensors, you can test the connections by wiring it up with a breadboard. You can get some test code from the adafruit website, it is also good to test the hardware again after the PCB soldering and connection to the raspberry pi, use the same test code from adafruit to make sure the code still works with the hardware. The test code from adafruit is written in python. The test code can be found here: 
https://learn.adafruit.com/adafruit-ultimate-gps-featherwing/circuitpython-library
https://learn.adafruit.com/adafruit-lsm9ds0-accelerometer-gyro-magnetometer-9-dof-breakouts/python-circuitpython


