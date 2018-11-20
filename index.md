# Speed Tracker
## November 20th - Hardware 
### Current Progress

### Problems and opportunities

### Financial Status
Since I have gotten all of my items for the project my finacial status is good and on track, nothing to be worried about.

## November 13th - Hardware
### Current Progress
My current progress for this project is that I am on track as I was able to power up my PCB board with my Raspberry Pi and try out some code to get the sensor working. I was able to do the soldering at home as I have a soldering iron at home, I was able to solder the vias and the stackable header pins to the PCB board. I found some code for my Adafruit 9-DOF Accel/Mag/Gyro+Temp Breakout Board - LSM9DS0 sensor on the adafruit website which can be viewed below to test out the connections for my PCB board. I was able to get the Adafruit 9-DOF Accel/Mag/Gyro+Temp Breakout Board - LSM9DS0 to read some data in m/s^2 along the X,Y and Z axis. 

### Problems and opportunities
I only had 2 problems during this weeks milestone, the first problem I had which I was able to solve was that my original PCB board design had a couple of shorts on the board, so I had to redesign the part of the board where the shorts were and get it sent to the prototype lab to be made again. Once it got made, I was able to solder the connections that needed to be soldered. The second problem that occured to me for this weeks milestone was trying to get my Adafruit Ultimate GPS FeatherWing to read from the code, this is more of a problem with the code as the code I got from Adafruit, the problem with the code is that the pins RX and TX which the GPS uses to input and output data wasn't an attribute for the board import, which I found weird, but I got to find a way to solve this problem before the project is due at the end of the semester.

### Financial Status
Since I have gotten all of my items for the project my finacial status is good and on track, nothing to be worried about.

### Links to the adafruit code that was used:
#### Adafruit 9-DOF Accel/Mag/Gyro+temp Breakout Board - LSM9DS0
https://learn.adafruit.com/adafruit-lsm9ds0-accelerometer-gyro-magnetometer-9-dof-breakouts/python-circuitpython

#### Adafruit Ultimate GPS FeatherWing
https://learn.adafruit.com/adafruit-ultimate-gps-featherwing/circuitpython-library

### Pictures of board 

## November 6th - Hardware
### Current Progress
My current progress for this project is that I am a little behind due ot the fact that I do not have the stackable header pins that were needed for this weeks milestone, but today I did get my PCB board that I design last week and I was able to solder in the vias that I put into the design. I need to clean up my PCB board with all the wire that was hard to take out from the solder with a better wire cutter, so it will be cleaner and easier to use. 

### Problems and opportunities
Other than not having the stackable header pins, I did not have many problems for this weeks milestone, as I was able to do some soldering today. 

### Financial Status
For my finacial status, for the most part I have everything I have for my project, but the only thing I need to get for my project is the stackable male to female header pins that would be needed to connect the my PCB board with my sensor and Raspberry Pi. This would take to get because I need to purchase it and receive the stackable header pins. 

### PCB Soldering 
![front](https://raw.githubusercontent.com/Zhillp/SpeedTracker/master/Documentations/Breadboard/20181106_131355.jpg)
![back](https://raw.githubusercontent.com/Zhillp/SpeedTracker/master/Documentations/Breadboard/20181106_131358.jpg)

## October 30th - PCB Design 
### Current Progress
My current progress is that I am still on track with my project schedule, as I finished off and emailed the prototype lab the gerber files for my PCB board design. 

### Problems and Opportunities 
I only had a few problems that occured for this part of the schedule, but were easily solved. The first problem during the process of making the design, I had 2 lines that were crossing and would create a short so I had to put a via on one of the lines so it would not cross and short the board. The second problem that occured was that, when I emailed the gerber files, I got a email back saying I had shorts on the board, so I fixed up all the shorts and emailed the gerber files again.

### Financial Status 
Since I have gotten all of my items for the project my finacial status is good and on track, nothing to be worried about.

## October 23rd - Breadboard Milestone
### Soldering 
For the Breadboarding milestone, both the adafruit 9-DOF Accel/Mag/Gyro+Temp Breakout Board - LSM9DS0 and the Adafruit Ultimate GPS FeatherWing I had to solder it with the pins. Soldering both the sensors was pretty easy due to the fact that I had prior knowledge of soldering from the school project I did when I was in high school. 

### Breadboarding 
Once I finished soldering my sensors to the pins I plugged them both into the breadboard I have in my Humber parts kit. I looked at the datasheet/Pinout layout for both my sensors, which will be linked below. I also looked the Pinout layouts for the Raspberry Pi 3 and made my following connections for the circuit. Once I finished breadboarding I went on fritzing and made the same connections on the application.

### Adafruit 9-DOF Accel/Mag/Gyro+Temp Breakout Board - LSM9DS0 Pinout Layout
https://learn.adafruit.com/adafruit-lsm9ds0-accelerometer-gyro-magnetometer-9-dof-breakouts/python-circuitpython

### Adafruit Ultimate GPS Featherwing Pinout Layout
https://learn.adafruit.com/adafruit-ultimate-gps-featherwing/pinouts

### Breadboard picture 
![Breadboard](https://raw.githubusercontent.com/Zhillp/SpeedTracker/master/Documentations/Breadboard/20181023_125810.jpg)

### I2C Address 
The I2C address for my sensor is 
![I2C](https://raw.githubusercontent.com/Zhillp/SpeedTracker/master/Documentations/Breadboard/2018-10-23-190644_1824x984_scrot.png)

## October 9th - 16th - Bring in Purchases/Raspberry Pi Setup 
During this time period, I gathered all of the purchases I needed for the project. I got my Raspberry Pi Kit first and then Adafruit 9-DOF Accel/Mag/Gyro+Temp Breakout Board - LSM9DS0 a few days later. I got my last purchase which was the Adafruit Ultimate GPS FeatherWing a week later. Also after I got my Raspberry Pi, I decided to set it up during the fall study days. I installed the rasbian OS from the class site and followed the instructions on the StudentSenseHat github page.

## October 2nd - Proof of Purchase
### Raspberry Pi Kit
![Raspberry Pi](https://raw.githubusercontent.com/Zhillp/SpeedTracker/master/Documentations/Invoice/pi.PNG)

### Adafruit 9-DOF Accel/Mag/Gyro+Temp Breakout Board - LSM9DS0
![Accel/Mag/Gyro+Temp board](https://raw.githubusercontent.com/Zhillp/SpeedTracker/master/Documentations/Invoice/Sensor.PNG)

### Adafruit Ultimate GPS FeatherWing
![GPS](https://raw.githubusercontent.com/Zhillp/SpeedTracker/master/Documentations/Invoice/gps.PNG)

## September 25th - Budget
The budget can be viewed [here](https://github.com/Zhillp/SpeedTracker/blob/master/Documentations/Purchases.xlsx)

## September 18th - Project Schedule 
The project schedule can be viewed [here](https://github.com/Zhillp/SpeedTracker/blob/master/Documentations/Project1.mpp)

## September 11th - Proposal  
The proposal can be viewed [here]()
