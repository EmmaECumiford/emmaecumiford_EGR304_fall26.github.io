---
title: Welcome Friends!! :D <3
tags:
- tag1
- tag2
---
<center>
<font size= "6">Emma Cumiford Datasheet</font><br>
as part of<br>
<font size= "8"> Project SBWB</font><br>
for<br>
<font size= "5"> Team 208 </font><br>

Submission: October 28, 2026

## Introduction

This datasheet documents the design process for the actuation and motor control portion of Project SBWB's Self-Balancing Work Bench.

### Project Summary

Project SBWB is a self-balancing work bench that keeps its work surface level automatically. Sensing subsystems measure the bench's position, and the actuation subsystem physically adjusts the bench in response. My subsystem provides that motion: it receives signals from my teammates' boards, such as the distance-sensing subsystem, and drives a 12 V linear actuator to move the bench into balance. For a full overview of the project, including every team member's subsystem, see our [team report](https://embedded-systems-design.github.io/EGR304TeamTemplate/).

### My Contribution

My role on the team covers three main areas:

* **Actuation board:** designing the hardware that physically adjusts the bench, built around a 12 V linear actuator
* **Motor control:** using an H-bridge motor driver to let a PIC18F57Q43 Curiosity Nano control the actuator's direction and speed through PWM
* **Coding:** writing the microcontroller firmware that reads incoming signals from teammates' boards and translates them into motor commands

To help navigate this datasheet:

* For an overview of how the subsystem's components connect, see the [Block Diagram](LINK) section.
* For the reasoning behind part choices such as the actuator, see the [Component Selection](LINK) section.
* For the materials used to build the subsystem, see the ["BOM"](https://embedded-systems-design.github.io/EGR304DataSheetTemplate/03-BOM/BOM/) section.
* For the electrical design, see the [Schematic](LINK) section.
* For the firmware, see the [Software](LINK) section.