


## **EMBEDDED SYSTEM PROJECT ON FINITE STATE MACHINES**

***AIM***
The aim of this project is to simulate a discrete system with clearly definable states.
Here I am simulating an oscilloscope, three function generator and a logic analyzer.

***INTRODUCTION***
The project starts with following model:
Estimation of components required, schematic design, state transition design , deployment and verification of output .

**Estimation of components**:

Components used are:

A teensy 3.1/3.2 microcontroller          -[https://www.pjrc.com/teensy/teensy31.html](https://www.pjrc.com/teensy/teensy31.html)

![enter image description here](https://github.com/vishnurad/Projects/blob/master/20200713_073851.jpg)

 Adafruit SSD1306 OLED display with 128*64 pixel resolution -[https://www.adafruit.com/product/931](https://www.adafruit.com/product/931)


Two external push buttons for triggering different available states.

Some wires for connecting components

Breadboard 

A linear potentiometer-10 Kilo Ohm for varying the function generator states output


**Design of circuit**:

![enter image description here](https://github.com/vishnurad/Projects/blob/master/Assignment%202%20schem.png)

Adafruit OLED display pins SDA and SCL are connected to A4(SDA0) and A5(SCL0)
respectively.

![enter image description here](https://github.com/vishnurad/Projects/blob/master/20200713_073851.jpg)


Breadboard circuit:

![enter image description here](https://github.com/vishnurad/Projects/blob/master/20200713_035716.jpg)


State Model Design:

![enter image description here](https://github.com/vishnurad/Projects/blob/master/20200713_035847.jpg)


State Model description:

Available States:

Welcome menu,

Oscilloscope,

Function generator
- with Sine Wave

- with Triangular Wave

- with Square Wave

Logic Analyse

GO back


Events created:

Mode press count

Serial commands (s_command) 1, 2, 3, 4, 5, 6, & 8.

Reset


**Deployment**

Visual Studio Code IDE was used to deploy the code into the microcontroller.


**Verification of Output**

Modes:

![enter image description here](https://github.com/vishnurad/Projects/blob/master/20200713_035847.jpg)


Serial plotter output:


Sine Wave:

![enter image description here](https://github.com/vishnurad/Projects/blob/master/11.PNG)

Square Wave:
![enter image description here](https://github.com/vishnurad/Projects/blob/master/12.PNG)

Triangle Wave:
![enter image description here](https://github.com/vishnurad/Projects/blob/master/13.PNG)

Video Verification on Youtube:
https://youtu.be/hAcFkZVLBYs


**Observations:**
Square wave output is not exactly as i intended to be.

 **Conclusions**:
 Better applications of micro controller is verified here with state model designs and transitions.
 Such modes are widely used all over the world, eg, would be a teller machine(ATM) or a stopwatch. All these are discrete systems with clearly defined states.
 
Outputs are succesful though some limitatins are observed.


**References:
**
References

_All about Arduino libraries_. (2013, February 16). Adafruit Learning System.  [https://learn.adafruit.com/adafruit-all-about-arduino-libraries-install-use](https://learn.adafruit.com/adafruit-all-about-arduino-libraries-install-use)

_Arduino tutorials_. (2019, October 21). Programming Electronics Academy.  [https://www.programmingelectronics.com/arduino-tutorials-2/](https://www.programmingelectronics.com/arduino-tutorials-2/)

_Libraries_. (n.d.). Arduino.  [https://www.arduino.cc/en/reference/libraries](https://www.arduino.cc/en/reference/libraries)

_PJRC store_. (n.d.). PJRC: Electronic Projects.  [https://www.pjrc.com/store/teensy32.html](https://www.pjrc.com/store/teensy32.html)















