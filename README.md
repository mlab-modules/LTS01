# MLAB Module LTS01

## Description

The LTS01 module is a highly accurate digital thermometer, communicating through the I2C protocol. It's based on the integrated circuit [MAX31725](https://www.analog.com/media/en/technical-documentation/data-sheets/MAX31725-MAX31726.pdf) from Maxim Integrated. This module is designed for exceptional accuracy and low power consumption, making it ideal for a wide range of applications.


![LTS01A](/doc/img/LTS01A_top_big.jpg)

## Features
 *  Digital output through the I2C protocol
 *  Based on [MAX31725](https://www.analog.com/media/en/technical-documentation/data-sheets/MAX31725-MAX31726.pdf) thermometer IC
 *  High-precision temperature measurement with an accuracy of ±0.5°C (typical) from -40°C to +105°C
 *  Extended temperature range: -55°C to +150°C
 *  Resolution 16-bit (standard), 0.00390625°C
 *  Low power consumption, making it suitable for battery-powered applications (max. 925uA)
 *  The module's address can be set by resoldering null-resistors on the board, allowing multiple modules to be used on the same I2C bus
 *  Shutdown mode to conserve power between temperature readings
 *  Thermostat functionality with programmable over-temperature alarm
 *  Compatible with the MLAB system

## Use Cases

The LTS01 module can be used for various applications, including:

* Home automation
* Industrial control and measurement
* Medical devices
* Air conditioning systems

## Connectivity

This module communicates via the I2C protocol, simplifying interfacing with many different devices. The module's address can be set using jumpers on the board.

## Power Supply

The LTS01 module can be powered from the MLAB board or another power source ranging from 1.7 V to 3.6 V.

## Installation and Use

1. Attach the LTS01 module to your MLAB board and connecto to your I2C host.
2. To communicate with the LTS01 module, you can use any standard I2C library that is compatible with your microcontroller.
3. The temperature can be read from the temperature register of the module.
