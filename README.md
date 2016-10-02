# Eight-LEDs-and-a-Shift-Register
Using a shift register to control 8 LEDs with 3 pins

source: https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds/overview

In this lesson, you will learn how to use eight large red LEDs with an Arduino without needing to give up 8 output pins!

Although you could wire up eight LEDs each with a resistor to an Arduino pin (like we did for an RGB LED in Lesson 2) you would rapidly start to run out of pins on your Arduino. If you don't have a lot of stuff connected to your 'duino it's OK to do so - but often times we want buttons, sensors, servos, etc and before you know it you've got no pins left. So, instead of doing that, you are going to use a chip called the 74HC595 Serial to Parallel Converter. This chip has eight outputs (perfect) and three inputs that you use to feed data into it a bit at a time. 

This chip makes it a little slower to drive the LEDs (you can only change the LEDs about 500,000 times a second instead of 8,000,000 a second) but it's still really really fast, way faster than humans can detect, so it's worth it!

To build the project described in this lesson, you will need the following parts.

5mm Red LED 8
270 Ω Resistors (red, purple, brown stripes) 8
74HC595 Shift Register
Breadboard 
Arduino Uno R3 1 (in my experiment I used an Arduino Mega 2560)
Jumper wire 

