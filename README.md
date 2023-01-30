# bme68x-python-library-bsec2.2.0-13sensors
This project is a clone of the PI3G python library supporting the BOSCH Sensortec BME688 -BSEC 2.2.0.0 : 13 v-sensors
At BSEC 2.2.0 Boschsensortec removed a virtual sensor perviously annotated for "internal use". This version removes all aspects of that sensor from the PI3G BSEC module. This would not have been posssilble without the work of 'flipthedog'.

I have tested this with the PI3G, Pimoroni, and Adafruit BME688 modules, and from a coding perspective the only difference is the I2C address. 
