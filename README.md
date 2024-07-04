# Smart Vaccuum Cleaner

The Smart Vaccuum Cleaner that can navigate a room and clean surfaces autonomously. The vacuum cleaner uses sensors to detect objects using ultrasonic, a motor system to move and clean, and a microcontroller (Arduino) to process data and control the operations.

Requirements

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Requirements](#requirements)
- [Hardware Requirements](#hardware-requirements)
- [Circuit Diagram](#circuit-diagram)
- [Usage](#usage)
- [Features](#features)


## Prerequisities

Before you begin, ensure you have met the following requirements
- Arduino IDE 
```
# Use the below link to install Arduino IDE
https://www.arduino.cc/en/software
```

## Installation

Type or copy the below code in your terminal to pull the repo files to your computer 

```bash
# Clone the repository
git clone https://github.com/Shivanisuvatheka/Smart-Vaccuum-Cleaner.git

# Change directory to the Smart-Vaccuum-Cleaner directory
cd Smart-Vaccuum-Cleaner
```

## Requirements

The required libraries for working of the code are 
```
- AFMotor.h
- NewPing.h
- Servo.h

Note : All of the above mentional libraries should be installed inside Arduino IDE via Library Manager (Sketch > Include Library > Manage Libraries) or in the form of zip files.
```

## Hardware Requirements

The Hardware required for working of the code include
```
- Arduino Board (UNO, Mega, or any other)
- Arduino Motor Shield
- Servo Motor
- Ultrasonic Sensor
- 6v Motor
- Lithium-ion Battery Cell
- Wheel
- Breadboard
- Jumper Wires
```

## Circuit Diagram
![Circuit Diagram](https://github.com/Shivanisuvatheka/Smart-Vaccuum-Cleaner/blob/main/Circuit%20Diagram.png)


## Usage

To use the project follow the steps given below

```
1. Install Arduino IDE as per the prerequisites
2. Install the required libraries
3. Connect the hardware components using the above circuit diagram
4. Either Download the code and make the required changes as stated inside the code with the help or comments or copy paste the code in your Arduino IDE and make required changes
5. Compile and upload the code to Arduino Board

```

## Features

The features of the project are as follows
- Autonomous
- Cost Efficient
- Smart Cleaning
