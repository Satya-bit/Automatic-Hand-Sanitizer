# Automatic-Hand-Sanitizer
Made an automatic hand sanitizer with the help of Arduino.

**=>Aim**-My aim was to build an automatic hand sanitizer dispenser which provides a contactless way to dispense sanitizer.

**=>Things that are used**

● Arduino Uno

● Transistor

● Ultrasonic Sensor

● Servo Motor

● Connecting Wires

● Sanitizer Bottle

**=>Basic Working**

● Made use of an ultrasonic sensor (Range: 2 cm to 400 cm and operating voltage: 5V)
to calculate the distance between the hand and the sanitizer bottle.

● The trigger pin of the sensor transmits a high frequency sound and when it hits the hand,
the reflected signal is received by the echo pin thus finding out the distance.

● When the hand is at a certain distance from the sanitizer bottle, the Arduino activates the
Servo motor and the sanitizer is expelled out of the bottle.

![image](https://github.com/Satya-bit/Automatic-Hand-Sanitizer/assets/70309925/033213cc-2b3f-48bd-ad0f-a2c84bad8a6e)


**=>Working**

The first component we made use of in the circuit is a HC- SR04 ultrasonic sensor
to give the perception of the distance of the object (hand). This type of sensor is
able to give accurate measurements of distance in the range of 2 cm to 450 cm and
has a focus of less than 15 degrees. In order to calculate the distance, the sensor
emits an ultrasonic sound (frequency 40 kHz) from one part of the sensor which
contains a transducer. There is another part of the sensor which receives the
reflected sound signals (echo).

Speed of sound= 340 m/s
 =0.034 cm/µs
Round trip time = distance/speed
Time= round trip time/2
Usage of the Ultrasonic Sensor- the VCC and GND of the ultrasonic sensor is
connected to a 5V power supply. The trigger (TRIG) pin and the echo (ECHO) pin
are connected to the digital output and digital input respectively on the Arduino
UNO. We then pulse the trigger (TRIG) pin high for time duration of at least 10µs
and the wait for the response for a high on the echo (ECHO) pin. The amount of
time the echo pin stays high corresponds to the distance of the object from the
sensor. Faster the response, lesser is the object’s distance. 



**=>Demo**

https://github.com/Satya-bit/Automatic-Hand-Sanitizer/assets/70309925/f55c0013-2dc2-4588-99f6-e16359dcce1f




