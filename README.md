Security Sensor Shield for Arduino
==================================
Copyright 2010 Freetronics Pty Ltd  
Freetronics site:  <www.freetronics.com>  
Freetronics email: <info@freetronics.com>  

Based on the circuit described in the "Security / Automation Sensors"
project in the book "Practical Arduino", this shield allows up to 4
security sensors to be connected with full End-Of-Line (EOL) support to
detect tampering.

Supported sensors include:

 * PIR (passive infrared) motion detectors.
 * Microwave motion detectors.
 * Reed switches.
 * Glass break detectors.
 * Gas detectors.

End-Of-Line technology allows the system to detect a variety of events
using a single cable pair to the sensor, including:

 * Sensor triggered.
 * Sensor cable cut.
 * Sensor cable short-circuited.
 * Sensor housing opened (even when system is disarmed)

Compatible with the Freetronics TwentyTen, Arduino Uno, Arduino
Duemilanove, and other compatible boards based on the same header
format.

Features:

 * Supports 4 sensor channels simultaneously.
 * Sensor power supply connections totally isolated from the Arduino.
 * Status LED for each sensor channel.
 * Reset button wired through to Arduino reset pin.
 * Green "Sensor power on" LED with current-limiting resistor.
 * Blue "Arduino power on" LED with current-limiting resistor.
 * 100nF bypass/smoothing capacitor on supply rails.
 * Overlay guide where you need it: both top and bottom.

More information is available at:

  http://www.freetronics.com/security-sensor-shield  
  http://www.practicalarduino.com/projects/security-sensors

The "docs" folder within this repository includes a handy copy of the
schematic in PDF format and image(s) of the pcb.


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> SecuritySensorShield.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
