---
layout: default
title: More Components
nav_order: 1
parent: Electronics Basics
has_toc: false
---

# More Components

## Breadboard

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/21025-dscn3816.jpeg" width="300" />
</p>

So you happened to see a retangular shaped block with holes in it and wondered what it was? This block is called a **breadboard** or **prototyping board**. The breadboard is a very important part of your prototype when you develop new things!

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/Breadboard-Circuit-Example.jpg" width="300" />
</p>

In your ICT lessons, your teacher would go through with you on how to connect up your circuit. Moreover, you would be using TinkerCAD to simulate and view your *virtual* circuit before actually building it, preventing any (touch wood) *magic smoke*.

The layout of the breadboard is done such that you can assemble your circuits easily.

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/horizontal-rows.png" width="300" />
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/verticalpower.png" width="300" /> 
</p>

## Wires

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/Dupont%20Wires.jpg" width="300" />
</p>

Wires are the most important part of your circuit. Without them, you would not be able to have electricity flowing through your circuit as there is simply nothing connecting them together! The wires provided in the kit are Male - Male Dupont wires (*I dont think I have to explain why the ends of the wire is male, right?* *wink*), and are the right size for you to be able to connect from your SSTuino to the breadboard or the component.

## Push Button

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/PushButton.jpg" width="300" />
</p>

This push button is a very simple example of a switch. But before you connect this push button into your house's mains, please do not do so :). The push button is meant for the breadboard instead.

When the push button is pressed down, the circuit is closed and current would flow through the two terminals of the button. Likewise, when the push button is not pressed down, the circuit will be open and current would not flow through the two terminals of the button. One good example would be your Macbook keyboard. As you depress the key, the circuit is closed and the computer can detect wether the key is pressed down or not

## Light Dependant Resistor

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/LDR.jpeg" width="300" />
</p>

As the name suggests, the Light Depedant Resistor (or Photoresistor) is a component that changes resistance when the light intensity changes. For the LDR that is provided in the kit, the resistance of the LDR **decreases** when the light intensity **increases**.

Like a normal resistor, there is no polarity for the LDR and can be connected in both sides.

## Buzzer

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/146-2.jpg" width="300" />
</p>

This buzzer is a Piezo Buzzer. If you try to open up the buzzer, you would see that there are a few embedded components inside the buzzer. What happens when you connect it to power is that it is converted to an oscilating signal, which is amplified and applied to the piezo disc. This causes the material to expand and contract rapidly, which results in sound waves being produced. 

**Note:** The sound from the Piezo buzzer can be quite sharp and loud. Do be careful when using these components.

## Potentiometer

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/10KPot.jpg" width="300" />
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/resistor-pot3.gif" width="300" />
</p>

The potentiometer is a variable resistor, with a adjustable knob. As the knob is turned from one side to another, the resistance changes. Potentiometers are used for controlling devices, such as the brightness of the LED, and with the appropriate circuit, the speed of a motor.

## Ultrasonic Sensor

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/Ultrasonic.jpg" width="300" />
</p>

The ultrasonic sensor is a device that measures distance by emitting ultrasonic waves, waits for the wave the bounce back and then measure the time taken.

## TMP36 Temperature Sensor

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/TMP36GZ_PinOut.png" width="300" />
</p>

The TMP36 temperature sensor is a rather accurate sensor despite is low price. For more information, visit the [Adafruit Website](https://learn.adafruit.com/tmp36-temperature-sensor/overview).

**Note:** You may notice that this package may resemble that of other components such as transistors. **Please do not mix them up and read the respective manuals carefully.** The component model would be marked out on the **flat** side of the component for this package. Use the model number to search for the pinouts for you to make sure you are connecting the component the right way.

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/TO92%20Pinout%20Transistor.jpeg" width="300" />
</p>

This shape and pinouts is called the TO-92 Package and is a very cheap and easy to manufacture method for transistors.

## PIR - Passive Infra-Red Sensor

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/PIR.jpg" width="300" />
</p>

PIR sensors are low-power, inexpensive and easy to deploy devices that detect if a person is in range of the sensor. A common use would be the light sensor installed in toilets that automatically turns on the lights when someone steps into the toilet.

To find out more about how it works, check out this detailed explanation from Adafruit: [https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor/how-pirs-work](https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor/how-pirs-work)

## DHT11 Temperature and Humidity Sensor

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/DHT11.jpg" width="300" />
</p>

The DHT11 Temperaure and Humidity sensor is an excellent hobbyist sensor, albeit with low refresh rates. It is also cheap to purchase and has relatively good accuracy for basic data logging. The data from the sensor can also be easily read from any microcontroller.

## 9g Micro Servo

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/servo.jpg" width="300" />
</p>

This Micro Servo has a lot of cool uses! Being a servo, it has precise control from 0 to 180º and is a very good component for prototyping.

## RGB LED (Common Cathode)

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/RGB.jpg" width="300" />
</p>

The RGB LED is a more complex version of the conventional coloured LED. It combines 3 LEDs (Red, Green and Blue) into one package. By configuring the intensity of the various LEDs, you can create lots of different colours from this LED.

## Last but not least

 This tutorial is meant for you to know that with every component that you use, you will need to decide for yourself wether it fits the circuit or not; be it simple components like LEDs and buzzers to more advanced (*and more expensive*) components like LCD displays and sensors!

One thing that is great when you explore the Arduino ecosystem is the immense amount of community support. When in doubt, always ask. As an individual learning 21st century digital skills, there are lots of platforms where your queries can be answered. It is just a matter of wether you would want to go and find the correct resources or not.

Therefore, before giving up on your design, maybe consider:

* Refering to your component manual. They will include essential infomation about the properties of the component
* Google the issue. Usually people would have posted this issue online in places like forums (StackOverflow, Arduino forum, Reddit etc.)
* Ask around about that issue. You can also post your questions in the appropriate channels, and if the question is good, others can learn from the issues that you faced!

If you would like to know more about:

* Ohm's Law : [(Link)](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law/all)
* LEDs : [(Link)](https://learn.sparkfun.com/tutorials/light-emitting-diodes-leds/all#introduction)