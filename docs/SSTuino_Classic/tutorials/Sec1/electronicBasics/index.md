---
layout: default
title: Electronics Basics
nav_order: 0
parent: SSTuino Classic Sec 1 Tutorials
has_children: true
has_toc: false
---

# How to not *burn* your LEDs!
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

Before we go into electronics, here is what will happen when if you do not handle them well.

![sparkfunGIF](https://cdn.sparkfun.com/assets/b/9/b/8/5/51f1e90dce395fba20000002.gif)

## Some essentials...

In your SSTunino kit, we have provided some components for you to use, and is listed inside the [parts list page](https://d3lta-v.github.io/SSTuino/tutorials/partsList.html). 

**Note:** If there are any components missing from the kit when you first recieve it, please approach your ICT teachers.

This tutorial will cover the details of the components that are included in the SSTuino Kit, along with some theory behind electronics to help you to build your first circuit in the meantime. This tutorial page is very useful as you can reference to the components in the event you forget what it is.

## SSTuino Board

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/a000066_front_1_1_1.jpg" width="300" />
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/Image%20Assets/SSTuino.png" width="300" /> 
</p>

*Notice any difference?*

For students who are familliar with the Arduino UNO, you would realise that it looks pretty simillar to the SSTuino. This is because that the SSTuino is an adapted design from the Arduino UNO. This device shares a lot of similarities as the UNO such as:

- Coding compatability
- Shield compatability as the SSTuino shares the same I/O Pins as the Arduino Uno
- Sharing the most of the same components

The major design difference with this board is that it has a extended board footprint to accept a WiFi chip, resulting the SSTuino to be an Internet-Of-Things (IoT) enabled product. This means that the SSTuino can connect to the internet to send/recieve data!

## USB C to Micro USB Cable

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/usb-type-c-2-0-to-micro-usb-cable-also-known-as-usb-type-c-1159-800x800.jpg" width="300" />
</p>

The USB C to Micro USB Cable is a unique cable that helps you connect your USB C Mac to the CP2102 MicroUSB Serial Converter. As this type of cable is less commonly seen in the market, please take good care of this wire as it is not easy to obtain one.

## NEU (New Enhanced UART) CP2102

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/CP2102_NEU.jpeg" width="300" />
</p>

The CP2102 MicroUSB Serial Converter is a very important device to have as it is the communication tool between the computer and the microcontroller (SSTuino). We designed SSTuino to have a external Serial Converter as not only is it modular, where you could change the chip in the event it is spoilt, you could also use the CP2102 to communicate with other serial devices such as the ATTiny85 or the Raspberry Pi.

This is where you would use your USB C to Micro USB cable to plug into this chip for uploading of code from your computer to the SSTuino.

The NEU (New Enhanced UART) is a custom designed serial converter designed by Pan Ziyue for the SSTuino Innovator's Kit, and is designed to work with your Mac and SSTuino. As there are limited production quantities in each run, please refrain from losing the chip. Moreover each chip is expensive to manufacture so again please take good care of the chip.

## ESP01S WiFi Chip

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/esp-8266-01.jpg" width="300" />
</p>

The ESP01S WiFi Chip is what sets the SSTuino different from the Arduino UNO. It allows the SSTuino to be able to connect to the internet, allowing the SSTuino to have smart home, automation and internet connected sensor abilities.

Our team is developing more content to help you get started in developing IoT products, so do watch this space for more details.

## Next Chapter
[Resistors and LEDs](page2.md)