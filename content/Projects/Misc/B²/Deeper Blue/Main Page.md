---
title: Deeper Blue Main Page
tags:
  - Incomplete
  - B²
---
Deeper Blue is part of a larger project referred to as [[Projects/Misc/B²/Main Page|B².]] It is also a revival of an old project that was known as "Deep Blue." 

Designed as a ~3 lb sumo battlebot, it is one of the designs created for B². Internally the electronics and mechanical assembly & manufacturing is rather straightforward.

## Mechanical

The frame (the stuff that needs to be manufactured) consists of four main components. The main chassis, motor mount clamps, a lid that doubles as a battery mount, and a front mounting space for a plow or other weapon variants.

The entire Fusion360 files [can be accessed here](https://mylsu1602.autodesk360.com/g/projects/20240917805728881/data/dXJuOmFkc2sud2lwcHJvZDpmcy5mb2xkZXI6Y28ua1ZBUHBtUU1URjJvTktVXzNSM0ZuQQ).

## Electrical

The [L298N Motor Driver](https://www.handsontec.com/dataspecs/L298N%20Motor%20Driver.pdf) is used to control two [FingerTech Silver Spark](https://www.fingertechrobotics.com/proddetail.php?prod=ft-Sspark16) motors that drive the wheels.

An ESP32 is used as the microcontroller that takes input & send data to the motor driver.

A DualShock 4 (ps4 controller) is paired via Bluetooth to the ESP32

## Code

Code for Deeper Blue can be found [at its repository](https://github.com/BengalBots-LSU/Deeper-Blue)