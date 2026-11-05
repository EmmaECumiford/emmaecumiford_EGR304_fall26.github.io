---
title: Emma Cumiford's 304 Contributions
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

Project SBWB is a self-balancing work bench that keeps its work surface level automatically. Sensing subsystems measure the bench's position, and the actuation subsystem physically adjusts the bench in response. My subsystem provides that motion: it receives signals from my teammates' boards, such as the distance-sensing subsystem, and drives a 6 V linear actuator to move the bench into balance. For a full overview of the project, including every team member's subsystem, see our [team report](https://asu-egr304-2026-f-208.github.io/).

### My Contribution

My role on the team covers two main areas:

* **Actuation board:** designing the hardware that physically adjusts the bench, built around a 12 V linear actuator
* **Motor control:** using an H-bridge motor driver to let a PIC18F57Q43 Curiosity Nano control the actuator's direction and speed through PWM.

To help navigate this datasheet:

* For an overview of how the subsystem's components connect, see the [Block Diagram](https://emmaecumiford.github.io/emmaecumiford_EGR304_fall26.github.io/01-Block-Diagram/Block-Diagram/) section.
* For the reasoning behind part choices such as the actuator, see the [Component Selection](https://emmaecumiford.github.io/emmaecumiford_EGR304_fall26.github.io/02-Component-Selection/Component-Selection/) section.
* For the materials used to build the subsystem, see the ["BOM"](https://emmaecumiford.github.io/emmaecumiford_EGR304_fall26.github.io/03-BOM/BOM/) section.
* For the electrical design, see the [Schematic](https://emmaecumiford.github.io/emmaecumiford_EGR304_fall26.github.io/04-Schematic/schematic/) section.
* For how power will be distributed, see the [Power Budget](https://emmaecumiford.github.io/emmaecumiford_EGR304_fall26.github.io/05-Power-Budget/Power-Budget/) section.