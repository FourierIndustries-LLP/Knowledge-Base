---
layout: default
title: First SSTuino Circuit
nav_order: 1
parent: TinkerCAD
has_toc: false
---
# First circuit with the SSTuino Kit!

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

So you have built yourself some very simple circuits. Now let us build circuits, but with the SSTuino!

In TinkerCAD, create a new circuit. In this new circuit, drag out an Arduino Uno, a breadboard, one resistor and a LED. Connect it in this manner, with the **Positive(+)** connect to **5V** and the **Negative(-)** connect to **GND**. 

![arduino1](imageAssets/arduino1.png)

If you had read [this tutorial](https://d3lta-v.github.io/SSTuino/tutorials/Sec1/electronicBasics.html), you should have known how the breadboard works.

Press **Start Simulation** and see your circuit light up!

![arduino2](imageAssets/arduino2.png)

Now, copy your circuit from TinkerCAD onto your SSTuino Innovator's Kit. 

>**NOTE:** To prevent damage to your computer or the components, please **disconnect all power from the SSTuino board** when you are wiring up your circuit!

It should look something like this:

![arduino8](imageAssets/arduino8.png)

Let us go back to the simulation and change the circuit like this:

![arduino7](imageAssets/arduino7.png)

What would happen and why?

## Add a button!

Now time for you to "control" your circuit. Set up your circuit like this:

![arduino4](imageAssets/arduino4.png)

What this circuit allows you to do is to turn on and off your LED. This push button works something like this: When you press the button, the circuit is closed and current can flow to the LED, which makes the LED light up. When the button is not pressed, the circuit is considered open and current will not flow to the LED, which makes the LED not light up.

Copy this circuit over to your SSTuino board setup.

>**NOTE:** To prevent damage to your computer or the components, please **disconnect all power from the SSTuino board** when you are wiring up your circuit!

![arduino3](imageAssets/arduino3.mp4)

To futher spice up your circuit, you can consider adding more LEDs to the circuit. How would you add the LEDs to the circuit? What kind of reaction does your circuit have?

## The photoresistor

The photoresistor is a resistor that reacts to light. It changes resistance when the amount of light it detects changes.

Create a new circuit and set up your circuit like this:

![arduino5](imageAssets/arduino5.png)

What this circuit allows you to see is the difference in LED brightness as you cover the photoresistor or shine a torch on it. 

![arduino6](imageAssets/arduino6.mp4)

Copy this circuit over to your SSTuino board setup.

>**NOTE:** To prevent damage to your computer or the components, please **disconnect all power from the SSTuino board** when you are wiring up your circuit!

What happens to the LED brightness as you play with the photoresistor? Record and post a video onto Instagram and place a hashtag `#sstuino`! 

## Time to turn it up!

We are going to move into the programming stage of the SSTuino Innovator's Kit, so please move to the **[next tutorial](https://d3lta-v.github.io/SSTuino/tutorials/Sec1/sstuinoProgram.html)**