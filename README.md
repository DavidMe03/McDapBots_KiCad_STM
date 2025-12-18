# McDap Bots Pedagogical Robot

This project was created as a capstone project for the University of Virginia Department of Electrical and Computer Engineering. Our goal was to create a small robot which could be programmed by students, for use as a teaching aide in an embedded systems course. This repository contains the software component of this, both drivers and application code.

**Authors**
- Colby Wise
- Pratik Pandit
- Austen Yun 
- David Merino
- Marc Rosenthal

**Advisors**: Todd DeLong and Adam Barnes 

**Features at a glance**
- 2 motors (PWM controlled), OLED screen (I2C), reflectance sensor (I2C), bump switches (GPIO), Bluetooth (UART), and infrared sensors (ADC)
- battery charging port and battery voltage display (press button to enable)
- support for TI and STM microcontrollers

## What is contained here
STM32 adapter board for the McDap pedalogical robot. Used to reroute the pins of the main board to the STM Nucleo-G071RB

**Bill of Materials Files**

BOM.xlsx contains a list of all the parts needed for to add the reflectance sensor as a feature to the robot.
Digikey_Parts_List.xlsx can be uploaded to Digikey to select the parts needed for one copy of this board.

## How to use this repository
1. Copy the repository locally to your computer
2. Using KiCad 8.0 (or higher version) open the file `AdapterBoard_McDap.kicad_pro`
3. Generate necessary gerber files and orde components
4. Follow the provided construction guide to build the robot
