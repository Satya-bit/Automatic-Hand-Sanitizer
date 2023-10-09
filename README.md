# Automatic-Hand-Sanitizer
Made an automatic hand sanitizer with the help of Arduino.
=>My aim was to build an automatic hand sanitizer dispenser which provides a contactless way to dispense sanitizer.

=>Things that are used
● Arduino Uno

● Transistor

● Ultrasonic Sensor

● Servo Motor

● Connecting Wires

● Sanitizer Bottle

=>Basic Working
● We make use of an ultrasonic sensor (Range: 2 cm to 400 cm and operating voltage: 5V)
to calculate the distance between the hand and the sanitizer bottle.
● The trigger pin of the sensor transmits a high frequency sound and when it hits the hand,
the reflected signal is received by the echo pin thus finding out the distance.
● When the hand is at a certain distance from the sanitizer bottle, the Arduino activates the
Servo motor and the sanitizer is expelled out of the bottle.

![image](https://github.com/Satya-bit/Automatic-Hand-Sanitizer/assets/70309925/96ab62b2-03f3-4de9-924d-488c65f1faae)
