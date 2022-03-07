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

> **Note:** As we will be progressing towards tinkering and creating a circuits, a very important rule of thumb is to **not connect the circuit/project** to power before completing it. This helps to lower the risk of a component failing due to a improperly constructed circuit.

## How does circuits work?

A basic electrical circuit has 3 items:

1. Power Source (Battery, Wall Plug, etc.)
2. Wires/Conductors
3. Consumer (e.g. Light bulb, Speaker, Servo, etc.)

The power source provides the electrical energy required by the comsumer by travelling through the wires. For example, the battery in this circuit provides energy to the LED.

To prevent too much energy from travelling through the circuit to the consumer, we "limit" it by using resistors. Now we go into Ohm's Law.
## Ohms Law

In a basic circuit, there are 3 variables we need to consider:

1. Voltage
2. Current
3. Resistance

Voltage is the potential difference measured across the component. For example, the potential difference measured across this AA battery is 1.5V. Unit is V.

Current is the rate of which the electricity flows throughout the circuit and is measured in Ampres. Unit is A.

The resistance resists the flow of electricity, to prevent the consumer from being damaged due to too much current flowing through it. Here are 2 examples, the one with resistor to the left, the one without on the right.

## Let us put it into practice!

Next, we will be simulating what we had learnt in this tutorial. We use TinkerCAD as the simulation platform for the SSTuino Innovator's Kit v2.

[Circuit Simulation](page3.md)