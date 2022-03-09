---
layout: default
title: Circuit Simulation
nav_order: 1
parent: SSTuino II Basics
has_children: true
has_toc: false
---

# Circuit Simulation

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

> **Note:** As we will be progressing towards tinkering and creating a circuits, a very important rule of thumb is to **not connect the circuit/project to power** before completing it. This helps to lower the risk of a component failing due to a improperly constructed circuit.

## What is Circuit Simulation?

Circuit Simulation is a great tool to test out your circuit design before assembling it in real life. This helps to reduce the possibility of your components being spolit due to a incorrect circuit design.  The platform we will be using for the SSTuino Innovator's Kit v2 is TinkerCAD.

## TinkerCAD

Say you have an amazing idea at hand and would like to realise it, to which you are thinking: "Hmm, how can I evolve my idea into a real product?"

Meet TinkerCAD, one of the most popular classroom tools for creating simple designs from scratch. It is a simple to use online 3D design and prototyping program.

Let us set up TinkerCAD and have fun with a mini project!

## Sign in to TinkerCAD

Signing in to TinkerCAD is very simple!

* Go to [tinkercad.com](https://www.tinkercad.com/) and then click on Sign In

![Sign In](assets/tinkerCAD.png)

* Go to the login screen

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/tinkercad/imageAssets/signIn.png" width="300" />
</p>

* Select sign in using social provider, and select your SST Google Account.

<p align="center">
  <img src="https://raw.githubusercontent.com/FourierIndustries-LLP/Knowledge-Base/main/docs/SSTuino_Classic/tutorials/Sec1/tinkercad/imageAssets/signInSocialProvider.png" width="300" />
</p>

## Create a Circuit

There are a lot of functions inside TinkerCAD! However, for the purposes of the SSTuino we are going to use the "Circuits" function. Click on "Circuits" on the sidebar and click on create new circuit.

![createCircuit](assets/createCircuit.png)

* **Note:** It is a very good habit to create a new circuit after you have finished your previous tutorial, instead of overwriting the current circuit. This is to help you to be able to reference to previous tutorials done when you need help with your future projects.

After you have created the new circuit, it should look like this:

![Main Project](assets/mainProject.png)

Here are the essential buttons of building electronic circuits with TinkerCAD.

![TinkerCAD_legend](assets/tinkerCAD_legend.png)

Let us bring out a 9V battery then connect it as follows.

![9V_Test](assets/9V_Test.png)

After you have connected the circuit, click on **Start Simulation** on the top right-hand corner of the website.

Once it lights up, the LED burns itself.

![9V_Test2](assets/9V_Test2.png)

The LED burns as there is no resistor used to limit the flow of the current.

Instead, connect a resistor like this:

![9V_Test3](assets/9V_Test3.png)

With the resistor attached, the LED lights up without burning up. :) Try this with different resistor values. What kind of changes happen?

Now, let us try this out using different types of batteries. TinkerCAD mainly provides 3 types of batteries: 9V, 3V and 1.5V. Connect your circuit up as shown.

![9V_Test5](assets/9V_Test5.png)

After you connect up the circuit, this happens:

![9V_Test4](assets/9V_Test4.png)

Why would this happen? This is because that LEDs have a minimum voltage to light up. If you look at the spec sheet located here:

[https://www.sparkfun.com/datasheets/Components/LED/COM-09590-YSL-R531R3D-D2.pdf](https://www.sparkfun.com/datasheets/Components/LED/COM-09590-YSL-R531R3D-D2.pdf)

> Forward Voltage: Min 1.8V, Max 2.2V. Suggested current:16 - 18mA

This means that the 1.5V battery would be barely able to light up the circuit, and only the 2 other battery types will be able to light up the LED.
