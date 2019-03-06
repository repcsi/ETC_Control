# ETC_Control

## What is this?

This project started out as an electronic throttle controller project for AlphaECU which is done by ElDominio. AlphaECU is a fork of speeduino with modifications added.
[AlphaECU](https://github.com/ElDominio/AlphaECU-FW)
[Speeduino](https://github.com/noisymime/speeduino/)


### Prerequisites

You need some kind of arduino board and a dc motor controller that is capable of driving your electronic valve (amperage wise).

### Setting up

* The analog signals from your tps and accelerator pedal must be connected to the appropiate ANALOG pins on the arduino. Usually 4 signals. A0,A1,A2,A3 Analog pins.
* By default there is a1 DIGTAL direction pin (sets direction forwards/backwards) and 1 PWM-DIGITAL pin for pwm output. Marked with ~ .
* Setup common ground
* Make sure that you supply the correct voltage to your parts (5v for arduino, controller board and sensors, 12V for the dc motor)

## Built With Libraries

* [FastCRC](https://github.com/FrankBoesing/FastCRC) - FastCRC Arduino Library by FrankBoesing
* [PID library](https://github.com/br3ttb/Arduino-PID-Library) - PID Arduino Library by Brett Beauregard
* [EnableInterrupt](https://github.com/GreyGnome/EnableInterrupt) - New Arduino interrupt library by Mike Schwager

## Authors

* **ElDominio** - *Initial work* - [ElDominio](https://github.com/ElDominio)