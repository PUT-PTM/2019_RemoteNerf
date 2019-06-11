# 2019_RemoteNerf

## Overview
RemoteNerf is a device that allows to control a Nefr Gun attached to a frame.

## Description
Project includes two STM devices: STM Discovery to control rotation of the gun and STM Disco for trigger control. Rotation is accomplished by two servomechanisms controled by potentiometers: one for horizontal and one for vertical movement. Electric trigger of the gun is controled by a relay. Gun used in the build is Nerf Elite HyperFire. System allows to rotate the gun and fire from it at any moment.

## Tools
Hardware
* STM32F407G-DISC1 board
* STM32L100C-DISCO board
* TowerPro SG-5010 servomechanism
* PowerHD AR-3606HB servomechanism 
* Nerf Elite HyperFire
* 2 relay module
* Potentiometer 
* Wodden frame 

Software: 
* STM32CubeMX
* System Workbench for STM32
* STMStudio
* C language and HAL Libraries 

## How to run 
TO_DO

## How to compile 
Ordinary project build and compilation in System Workbench for STM32. 

## Future improvements 
* Stronger servomechanisms with higher torque
* Communication with external controler via WI-FI module ESP8266

## License
Based on MIT license

## Credits
Created by Artur Bałczyński & Szymon Wasilewski 

The project was conducted during the Microprocessor Lab course held by the Institute of Control and Information Engineering, Poznan University of Technology. Supervisor: Tomasz Mańkowski
