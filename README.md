# 2019_RemoteNerf

## Overview 
RemoteNerf is a device that allows to control a Nefr Gun attached to a frame. 

## Description
Project includes two STM devices: STM Discovery to control rotation of the gun and STM Disco for trigger control. Rotation is accomplished by two servomechanisms controled by potentiometers: one for horizontal and one for vertical movement. Electric trigger of the gun is controled by reallay. Used gun is Nerf Elite HyperFire. System allows to rotate the gun and fire from it at any moment. 

## Tools
Hardware
* STM32F4407VG Discovery Microcontroller
* STM32L100CDISCOVERY Disco Microcontroller
* Tower Pro SG-5010 Servomechanism
* AR-360 6HB Servomechanism 
* Nerf Elite HyperFire
* Rellay 
* Potentiometer 
* Wodden frame 

Software: 
* STM32 CubeMX
* STM Studio
* System Workbench for STM32
* C language and HAL Libraries 

## How to run 
TO_DO

## How to compile 
Oridinary project build and compilation in System Workbench for STM32. 

## Future improvements 
* Stronger servomechanisms with higher torque
* Communication with external controler via WI-FI module ESP8266

## License
Based on MIT license

## Credits
Created by Artur Bałczyński & Szymon Wasilewski 

The project was conducted during the Microprocessor Lab course held by the Institute of Control and Information Engineering, Poznan University of Technology. Supervisor: Tomasz Mańkowski
