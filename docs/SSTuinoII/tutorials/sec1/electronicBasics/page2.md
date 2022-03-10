---
layout: default
title: Basic circuit theory and electronics
nav_order: 0
parent: SSTuino II Basics
has_children: true
has_toc: false
---

# Basic circuit theory and electronics

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

> **Note:** As we will be progressing towards tinkering and creating a circuit, a very important rule of thumb is to **not connect the circuit/project to power** before completing it. This helps to lower the risk of a component failing due to a improperly constructed circuit.

## How does circuits work?

A basic electrical circuit has 3 items:

1. Power Source (Battery, Wall Plug, etc.)
2. Wires/Conductors
3. Consumer (e.g. Light bulb, Speaker, Servo, etc.)

The power source provides the electrical energy required by the consumer by travelling through the wires. For example, the battery in this circuit provides energy to the LED.

To prevent too much energy from travelling through the circuit to the consumer, we "limit" it by using resistors. Now we go into Ohm's Law.

## Ohms Law

In a basic circuit, there are 3 variables we need to consider:

1. Voltage
2. Current
3. Resistance

Voltage is the potential difference measured across the component. For example, the potential difference measured across this AA battery is 1.5V. Unit is V.

Current is the rate of which the electricity flows throughout the circuit and is measured in Amperes. Unit is A.

The resistance resists the flow of electricity, to prevent the consumer from being damaged due to too much current flowing through it. Here are 2 examples, the one with resistor to the left, the one without on the right.

(insert TinkerCAD picture inside)

To keep it simple for learning, we have 2 main resistors provided in the SSTuino Innovator's Kit v2 that would be just nice for the other components provided.

Below is a simple example of a circuit with a resistor.

<p align="center">
  <img src="https://cdn.sparkfun.com/assets/6/e/8/3/c/51f93d85757b7f2049270817.png" width="300" />
</p>

## What does the components in my kit do?

We have included very cool components inside this kit for you to try out and integrate into your projects! Here are the brief functions of them:

### SSTuino II

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuinoII/tutorials/sec1/electronicBasics/assets/sstuinoii.png" width="300" />
</p>

The SSTuino II is the main microcontroller (or brain) for the kit. It has a Wi-Fi chip on it for use with the Internet of Things (IoT). It has a small footprint to easily integrate the board into projects.

### SSTuino II Explorer Board

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuinoII/tutorials/sec1/electronicBasics/assets/explorer.png" width="300" />
</p>

The SSTuino II Explorer Board adapts the SSTuino II to a more familiar Arduino Uno form factor. It also includes LEDs to help visualise the usage of the pinouts.

### USB-C Cable

<p align="center">
  <img src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/MLL82?wid=1144&hei=1144&fmt=jpeg&qlt=95&.v=1575503793499" width="300" />
</p>

The USB-C Cable connects the SSTuino II to your Learning Device. It is also used to upload code from the Arduino IDE to the SSTuino II.

### Breadboard

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuinoII/tutorials/sec1/electronicBasics/assets/breadboard.jpeg" width="300" />
</p>

The breadboard is very simple to use for you to set up and test your circuits! In your lessons, your teacher will teach you how to connect up the circuits on the breadboard. You will also be using circuit simulation to test out your circuit virtually before implementing it! *So fingers crossed, no magic smoke!*

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/Breadboard-Circuit-Example.jpg" width="300" />
</p>

Here is the layout of the breadboard:

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/horizontal-rows.png" width="300" />
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/verticalpower.png" width="300" /> 
</p>

### Dupont Cables (Wires)

The wires are one of the most essential components of the circuit! Without them, the electricity would not flow and the circuit would not work. In the kit, we have provided 2 types of wires; Male - Male, and Male - Female. These would help you to connect to all the components in the kit.

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuinoII/tutorials/sec1/electronicBasics/assets/mmwire.jpg" width="300" />
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuinoII/tutorials/sec1/electronicBasics/assets/mfwire.jpeg" width="300" /> 
</p>

Male - Male wires on the left, Male - Female wires on the right.
{: .text-center }

### Bag of LEDs

LEDs are great for almost everything! It is a very good source of light while also being very energy efficient. LEDs are found in a large variety of everyday items - Mobile phones, headlamps of a car, flashlights and interior lights to name a few.

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/LED.jpeg" width="300" />
</p>

### Polarity is important

As LEDs are essentially diodes, it will only allow current flow in one direction. This is why for the LEDs provided in the kit, one of the leg is shorter than the other. The legs are specifically manufactured like this so that you can identify the polarity of the LED easily.

The longer leg of the LED is the **positive** leg and is called the **anode**. The shorter leg of the LED is the **negative** leg and is the **cathode**.

*But what if you just nice happen to connect it the wrong way? Would it explode?*

The LED would not light up, so not to worry. You can just simply reverse the polarity of the LED (i.e flip the thing around) and it will work again!

### Buzzer

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/146-2.jpg" width="300" />
</p>

This buzzer is a Piezo Buzzer. If you try to open up the buzzer, you would see that there are a few embedded components inside the buzzer. What happens when you connect it to power is that it is converted to an oscilating signal, which is amplified and applied to the piezo disc. This causes the material to expand and contract rapidly, which results in sound waves being produced. 

**Note:** The sound from the Piezo buzzer can be quite sharp and loud. Do be careful when using these components.

### Push Button

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/PushButton.jpg" width="300" />
</p>

The push button is a very simple example of a switch. But before you connect this push button into your house's mains supply, please do not do so as it is meant for low power electronics. :)

When the push button is pressed down, the circuit is closed and current would flow through the two terminals of the button. Likewise, when the push button is not pressed down, the circuit will be open and current would not flow through the two terminals of the button. One good example would be the keyboard on your Learning Device. As you depress the key, the circuit is closed and the computer can detect if the key is depressed.

### Potentiometer (10K Ohm)

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/10KPot.jpg" width="300" />
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/resistor-pot3.gif" width="300" />
</p>

The potentiometer is a variable resistor, with an adjustable knob. The resistance changes when the knob turns from one side to the other.

Potentiometers are used for controlling devices - the brightness of lights, speed of motor and loudness of speaker to name a few.

### Light Dependent Resistor

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/LDR.jpeg" width="300" />
</p>

As the name suggests, the Light Depedant Resistor (or Photoresistor) is a component that changes resistance when the light intensity changes. For the LDR that is provided in the kit, the resistance of the LDR **decreases** when the light intensity **increases**.

Like a normal resistor, there is no polarity for the LDR and can be connected in both sides.

### TMP36 Temperature Sensor

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/TMP36GZ_PinOut.png" width="300" />
</p>

The TMP36 is a rather accurate and simple to use temperature sensor for its low cost. For more information, visit the [Adafruit Website](https://learn.adafruit.com/tmp36-temperature-sensor/overview).

**Note:** You may notice that this package may resemble that of other components such as transistors. **Please do not mix them up and read the respective manuals carefully.** The component model would be marked out on the **flat** side of the component for this package. Use the model number to search for the pinouts for you to make sure you are connecting the component the right way.

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/TO92%20Pinout%20Transistor.jpeg" height="300" />
</p>

The TMP36 uses the TO-92 Package, which is cheap and simple to manufacture.

### Ultrasonic Sensor

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/Ultrasonic.jpg" width="300" />
</p>

The ultrasonic sensor is a device that measures distance by emitting ultrasonic waves, waits for the wave the bounce back and then measure the time taken. It is commonly found on cars for their reverse sensors.

### PIR Proximity Sensor

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/PIR.jpg" width="300" />
</p>

PIR (Passive Infra-Red) sensors are low-power, inexpensive and easy to deploy devices that detect if a person is in range of the sensor. A common use would be the light sensor installed in toilets that automatically turns on the lights when someone steps into the toilet.

To find out more about how it works, check out this detailed explanation from Adafruit: [https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor/how-pirs-work](https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor/how-pirs-work)

### Servo

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/servo.jpg" width="300" />
</p>

This Micro Servo has a lot of cool uses! It has precise control from 0 to 180º and is a very good component for prototyping.

### RGB LED

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/RGB.jpg" width="300" />
</p>

The RGB LED is a more complex version of the conventional coloured LED. It combines 3 LEDs (Red, Green and Blue) into one package. By configuring the intensity of the various LEDs, you can create lots of different colours from this LED.

There is also an RGB LED on the SSTuino II too!

### 330Ohm and 10KOhm resistor reel

For generic resistors, there is generally two types of resistors: Carbon Composite Resistor or Film Type Resistor. Carbon resistors are popular due to their extremely low cost and good accuracy with low enough tolerance (usually about ± 5%). Film Type Resistor, while being slightly costlier, provide closer tolerances (up to ±1%) from the rated resistance.

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/CarbonR.jpg" width="300" />
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/MetalR.jpg" width="300" /> 
</p>

*Carbon Film Resistors (left) and metal oxide resistors (right).*

The resistors provided in the kit are Carbon Composite resistors and have values of 330 Ohm and 10K Ohm. You can read the values of the resistor from the colour band on the component.

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/330-ohm.jpg" width="300" />
</p>

This is a **330 Ohm** resistor.

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/330-ohm.jpg" width="300" />
</p>

This is a **10K Ohm** resistor.

Refer to the infographic below on how to read the values of resistors:

![resistorChart](https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/electronicBasics/imageAssets/Resistors.png)

## What if I need more components?

Content coming soon... :)

## Let us put it into practice!

Next, we will be simulating what we had learnt in this tutorial. We use TinkerCAD as the simulation platform for the SSTuino Innovator's Kit v2.

[Circuit Simulation](page3.md)
