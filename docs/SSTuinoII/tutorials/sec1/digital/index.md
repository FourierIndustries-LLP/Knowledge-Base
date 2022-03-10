---
layout: default
title: Programming the SSTuino II
nav_order: 1
parent: SSTuino II Sec 1 Tutorials
has_children: true
has_toc: false
---

# Programming the SSTuino II

In this tutorial, we will discuss about the programming language that the SSTuino II uses, and explore some examples.

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Virtual Programming

Before we go into programming with the Arduino IDE, let us take things slow with the coding functionality on TinkerCAD!

The Arduino programming language is very similar to the [C/C++ Language](https://en.wikipedia.org/wiki/C%2B%2B) and are actually C/C++ functions that can be called into your code. When the code is uploaded onto the SSTuino, the compiler inside the Arduino IDE will convert it to something that the microcontroller can read.

For documentation regarding the Arduino IDE, please visit [this website](https://docs.arduino.cc/software/ide-v1/tutorials/arduino-ide-v1-basics).

Create a new circuit on TinkerCAD, and set it up like this:

![arduinoProg1](assets/arduinoProg1.png)

Once you set it up and press start simulation, notice the LED on the Arduino blinking? Why does this happen?

[![arduinoProg2](assets/arduinoProg2.mp4)]

The reason this happens is that TinkerCAD places in a sample code when you insert the Arduino into the circuit.

> Stop the simulation and press the **CODE** button. You should see something like this:

![arduinoProg3](assets/arduinoProg3.png)

TinkerCAD is very simple to use as you can use block coding to program the Arduino. You may have had experience in block coding with Scratch, Thunkable and Blockly Games. The programming environment would be very similar to those you had used before.

If you would like to program with text in TinkerCAD, you can also do so like this:

![arduinoProg10](assets/arduinoProg10.png)

They also have another format called Blocks + Code. The text code changes according to the blocks that you place.

![arduinoProg11](assets/arduinoProg11.png)

> **Note:** In TinkerCAD, when you program in blocks, the text that you coded will be deleted, and when you program in text, the blocks that you placed will be deleted when you change the programming mode. This is to prevent any internal application error with the website.![arduinoProg12](assets/arduinoProg12.png)

So what does this block of code do? It tells the Arduino to:

* Turn on the `built-in` LED for one second
* Turn off the `built-in` LED for one second

and it repeats all over until you turn off the circuit by unplugging the Arduino from the power source.

In programming, **HIGH** means to turn something on or give it power, while **LOW** means to turn something off or to not give it power. For this code, there are only **2 STATES, HIGH or LOW**. This means that it is either on or off and there is no value in between (either 1 or 0).

Now change the value of the `wait ___ seconds` to something that you like. What happens then?

## Pin 13

[Note for self: need to verify if pin13 is still used, due to the migration to the SSTuino II platform.]

Now, let us connect up the circuit:

![arduinoProg4](assets/arduinoProg4.png)

After you start simulation, it should look something like this:

![arduinoProg5](assets/arduinoProg5.mp4)

*Wait a minute...* How come the LED attached turns on and off even though I did not program it? Well the reason behind it is that the `built-in` LED pin is also connected to pin 13. This means in the program, `LED_BUILTIN` is also pin 13.

## Blink!

In TinkerCAD, another awesome feature is the ability to download the program that you have coded just now! You just have to press the download button as shown here:

> Go to code, and press the download button

![arduinoProg6](assets/arduinoProg6.png)

A `.ino` file will be downloaded on your LD and can be used on the Arduino IDE. Open the file and you would see this:

![arduinoProg7](assets/arduinoProg7.png)

Click **OK**.

A folder will then be created, and you will be able to see this code appear.

![arduinoProg8](imageAssets/arduinoProg8.png)

## Next Chapter

[Code Explanation and Upload](page2.md)