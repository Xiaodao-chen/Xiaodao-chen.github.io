---
title: "Fly-Pig: Quadrotor Flight Control Starting from PCB"
excerpt: "There are currently numerous types of flight controllers for drones, such as Kakute, among others. However, from the perspective of computer architecture, a simple flight control system encapsulates all the essential components of a computer system. Although small, it is comprehensive, incorporating sensor data acquisition, context switching, kernel porting, and operating system customization. For beginners just starting with embedded systems, it demonstrates a highly task-driven approach. This project begins with PCB design, integrates a unified board, and ultimately realizes the full flight of a quadrotor.

<br/>
<br/>
<img src='/images/pcb.jpg' width='500'>
"

collection: portfolio
---

* PCB Design and Hardware Subsystem Construction: Selecting appropriate components and integrating them into a unified board design.
* RTOS Migration (uCOSII to CM4 Kernel): Migrating the RTOS from uCOSII to the CM4 kernel, which includes bootloader development, task scheduling, and context switching. Assembly language is used to manipulate registers, enabling efficient context switching.
* Peripheral Driver Development: Creating drivers for peripherals such as I2C, USART, ADC, TIM, SPI, and sensor interfaces.
* Algorithm Implementation: Developing and optimizing algorithms for IMU bias analysis and elimination, data filtering, pose estimation (using EKF, Madgwick Orientation Filter, and Mahony Orientation Filter), and PID control.
<br/>
<br/>
<!-- <img src='/images/avp-slam.gif' width='500'>
<img src='/images/avp.gif' width='500'>
<img src='/images/avp-planning.gif' width='500'> -->
 <a href="https://github.com/Xiaodao-chen/fly-pig"><img alt="Code" src="https://img.shields.io/github/stars/Xiaodao-chen/fly-pig" /></a>
