# sensor-reading
For reading the sensors on the ROV and making nice, happy interfaces for them.

For PH probe:
The PH probe is giving off a current that is generated from the hydrogen ion activity
This number is the reciprocal of that activity and can be perdicted with this equation
E = E^0 - (2.303RT/F)pH; R = ideal gas constant, T= temp in Kelvin, F = Faraday constant

says for connecting: either SMA cable to SMA breakout board or Female BNC and BNC to SMA adapter
Just outputs a number
Takes time to get an accurate reading 

reading I2c inputs in Pi using C step by step
https://www.instructables.com/id/Reading-I2C-Inputs-in-Raspberry-Pi-using-C/


For temp sensor:


Something similair using I2C and Pi but diff temp sensor
https://www.instructables.com/id/Reading-I2C-Inputs-in-Raspberry-Pi-using-C/
used Librarys: stdio, stdlib, string, stdint
