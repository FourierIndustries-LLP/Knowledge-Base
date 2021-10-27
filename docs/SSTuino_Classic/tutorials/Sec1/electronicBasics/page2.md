---
layout: default
title: Resistors and LEDs
nav_order: 0
parent: Electronics Basics
has_toc: false
---

# Resistors and LEDs
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
## The resistor
### Ohms Law

For a more detailed read, click [here](https://www.allaboutcircuits.com/textbook/direct-current/chpt-2/voltage-current-resistance-relate/)

Ohm's Law is the most basic relationship between voltage, current and resistance. A circuit is formed when there is a conductive path for electric charge to move. 

The movement of the electric charge is **current**, expressed in Amperes (A). 

The force that enables the electric charge to move, or the potential energy is **voltage**, expressed in volts (v). 

In the circuit, there is bound to be some "friction" that resists the movement of electric charge, and that is **resistance**, expressed in Ohms (Ω). 

![ohmLawTable](https://www.allaboutcircuits.com/uploads/articles/units-measurement-electrical-current.png)

Resistors are essential in every circuit. They limit the flow of current in your circuit so *hopefully* there are no burnt components. 

### Types of resistors

For generic resistors, there is generally two types of resistors: Carbon Composite Resistor or Film Type Resistor. Carbon resistors are popular due to their extremely low cost and good accurancy with low enough tolerance (usually about +- 5%). Flim Type Resistor, while being slightly costlier, provide closer tolerances (up to +-1%) from the rated resistance.

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/CarbonR.jpg" width="300" />
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/MetalR.jpg" width="300" /> 
</p>

*Carbon Film Resistors (left) and metal oxide resistors (right).*

The resistors provided in the kit is metal oxide resistors and have values of 330 Ohm and 10K Ohm. You can read the values of the resistor from the colour band on the component.

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/330-ohm.jpg" width="300" />
</p>

This is a **330 Ohm** resistor.

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/10KOhm.jpg" width="300" />
</p>

This is a **10K Ohm** resistor.

If you are wondering how to read the values of resistors, refer to the infograpic below:

![resistorChart](https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/Resistors.png)

## Light Emitting Diode (LED)

Somehow or another, you would realise that you would need something to light up! Say hello to the LED! LEDs are small, efficient lightbulbs (that are rather bright). They are found in a large variety of devices like mobile phones, computer screens, the headlamps of the car and even spotlights!

<p align="center">
  <img src="https://raw.githubusercontent.com/d3lta-v/SSTuino/master/docs/tutorials/Sec1/partsList_images/LED.jpeg" width="300" />
</p>

So, you might be wondering how should you place an LED in a circuit? Here are the 3 most important things to take note:

### Polarity is important

As LEDs are essentially diodes, it will only allow current flow in one direction. This is why if you take a look at your SSTuino Innovator's Kit, you would realised that your LEDs have legs that are of different lenghths. Does the different lengths of legs indicate manufacturing defect? On the contary, the legs are specifically manufactured like this so that the you can identify the polarity of the LED easily.

The longer leg of the LED is the **positive** leg and is called the **anode**. The shorter leg of the LED is the **negative** leg and is the **cathode**. 

*But what if you just nice happen to connect it the wrong way? Would it explode?* 

The LED would not light up, so not to worry. You can just simply reverse the polarity of the LED (i.e flip the thing around) and it will work again!

### More current = More light!

As the LED is brighter (with the same voltage applied), the current draw would be higher. If you happen to purchase super-bright LEDs, you would realise that they drain your battery easily. With this, you can change the brightness of the LED by adjusting the amount of current that goes through it.

### BOOM!

As with most electronics, there is always a limit to everything. Once an LED draws current beyond a certain limit, you can see the colour change and then... it dies. RIP.

So to prevent tragic things like this from happening, we introduce resistors into the circuit to limit the amount of current the LED can draw. But what resistor would be most suitable?

## Some simple circuit theory...

Let us assume that we have some LEDs, resistors and a power source. Without any knowledge about datasheets and calculation, how should we go about connecting them together?

<p align="center">
  <img src="https://cdn.sparkfun.com/assets/6/e/8/3/c/51f93d85757b7f2049270817.png" width="300" />
</p>

It is that simple.

Moreover, a good resistor value for LEDs is 330Ohms (can be more or less), so we can simply use this resistor. *Easy, right?*

## Next Chapter
[More Components](page3.md)