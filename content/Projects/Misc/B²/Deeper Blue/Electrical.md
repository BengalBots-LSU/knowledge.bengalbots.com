---
title: Electrical Page
tags:
  - B²
  - Deeper_Blue
  - Incomplete
authors: []
---
### Microcontroller

An [ESP32-C3-Supermini](https://dl.artronshop.co.th/ESP32-C3%20SuperMini%20datasheet.pdf) is used to receive inputs from a DualShock 4 controller via Bluetooth. We have created a small circuit board to be able to plug the dev board into and have connections for power and the data pins to the motor driver easily accessible

![[PCB.png]]

### Motor Driver

For the motor driver, we've opted to use an [L298N](https://www.handsontec.com/dataspecs/L298N%20Motor%20Driver.pdf) motor driver module. This decision was made mainly due to the fact that we had many on hand, and this project was done with the intent to get a version out and optimize in the future.

![[L298N Motor Driver.png]]