---
layout: default
title: SSTuino II Basics
nav_order: 0
parent: SSTuino II Sec 1 Tutorials
has_children: true
has_toc: false
---

# SSTuino II Basics

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

> **Note:** Please do not plug in the SSTuino II and/or its components to your learning device or any power source first. We will get to it very soon. Yes, very soon. :)

In this tutorial, we will talk about the SSTuino II and the SSTuino II Explorer Board. We will then explain the components that we have provided inside the SSTuino Innovator's Kit v2. 

Afterwards, we will explain about some circuit theory and electronics, before moving on to creating our first circuit with TinkerCAD - an online circuit simulation platform that we use.

## But first, let us light it up!

The one thing you have been waiting for... connecting the SSTuino II to power! Please connect the USB C-C cable to your learning device as shown:

You should see this!

## The story of the various SSTuino generations...

The SSTuino Classic started out its life as a SPEEEduino, a WiFi enabled version of the Arduino Uno. It was used in lessons at Singapore Polytechnic when we studied there. Ziyue modified the design of the board for SST and that was how the SSTuino Classic came about. The SSTuino Classic shared many components as the Arduino Uno, with the main difference being that the ATMEGA328 being the main microcontroller (master), and the ESP-01 as the wireless interface (slave) despite the ESP-01 being more powerdul than the ATMEGA328.

The first version of the SSTuino Classic was not used as there were issues with the traces connected on the PCB. This meant that the circuit was not connected properly and users would not be able to transfer their code from their Learning Device onto the SSTuino. There was a revsion made to it and was used in the 2018 batch of SST Students as the SSTuino Rev B.

In 2018 and 2019, we had time to go down to SST and observe the lessons conducted. We noticed some issues when the students were integrating the SSTuino into their projects in the ChangeMakers program. Some of their projects were designed to be small or wearable, and the SSTuino Classic was simply too big for them to integrate into their projects.

We held a discussion with the teachers in SST, and came out with some sketches for the next iteration of the SSTuino. At that point of time, we wanted to move away from 8-bit microcontrollers like the Arduino Uno as they had limted processing capability and essentially a "lower ceiling". However, if we made the change to ARM, there would have been no compatible simulation platform to test the code and circuit. This would result in an increased difficulty in starting out, which may turn away more users who are trying to learn programming and tinkering with no prior knowledge and experience.

There was also a consideration to use the WiFi chip (ESP-32) as the main microcontroller as it was much more powerful than the usual 8-bit microcontrollers on the Arduino Uno, and it would have reduced the complexity of the board design too. We also met with the same issue as there was a lack of support for simulation and visualisation.

At the end, we decided that 

ARM and then the COVID and then the supply chain issues...

## Up next...

Let us go into how the SSTuino Innovator's Kit works and start tinkering!

[Basic circuit theory and electronics](page2.md)