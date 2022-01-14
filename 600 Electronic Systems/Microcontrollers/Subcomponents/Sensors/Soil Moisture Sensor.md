# Soil Moisture Sensor
---
Soil Moisture Sensors measure the amount of water suspended in an area of soil. Every [[Plants |plant]] has differing requirements to successfully grow.

The pH measure of soil, as well as almost all other measure is influenced by the amount of water currently held in suspension in the soil.

## Implementation
---
The Soil Moisture Sensor can be used to determine how much water should be output from the [[Drip Irrigation]] system.

These can be mounted onto the [[Rovers]] to reduce the total amount of wire infrastructure required, as well as reduce the total number or sensors needed to gather information.

There are seemingly 2 types of sensors, those that use resistance (cheaper, essentially just ohmmeters) and capacitive (more expensive, less easily DIY'd). The main difference to these two are the exposure to the test medium itself, the capacitive sensors being entirely encapsulated will not experience corrosion as often, and should theoretically be far more likely to last long term. In this way, capacitive sensors are more economical.

1/13/2021
--- 
It seems that the capacitive soils sensors are incredibly easy to produce, requiring only a 555 timer, voltage regulator, and some capacitors and resistors. it may be possible to create a decentralized version that cab be run along drip irrigation, freeing up the rovers for less intensive duties.

1/14/2021
---
After reviewing total material required to run sensors over the entire [[Field]], it was decided to keep the SMS as a tool for the soil arm of the Rovers.
It is more beneficial for Rovers to work as teams, one checking the values, and the other running the watering. 
