# bme68x-python-library-bsec2.2.0-13sensors
This project is a clone of the PI3G python library supporting the BOSCH Sensortec BME688 -BSEC 2.2.0.0 : 13 v-sensors
At BSEC 2.2.0 Boschsensortec removed a virtual sensor perviously annotated for "internal use". This version removes all aspects of that sensor from the PI3G BSEC module. This would not have been posssilble without the work of 'flipthedog'.

I have tested this with the PI3G, Pimoroni, and Adafruit BME688 modules, and from a coding perspective the only difference is the I2C address. 

Over in my p-sensors repository (p-sensors/tree/master/src/1.3.0) I have an example of how to burn in the BME688 and save a state file on completion. My other examples load the burned-in state file to reduce the time spent getting to accuracy 3.   I also show how to set up a second I2C bus at a slower speed for an adafruit PM25 particulate sensor, running alongside the BME688.
