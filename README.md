# wio-bme680
Display BME680 data like IAQ on the Wio-Terminal 

A 5 minutes mashup of 
- https://github.com/Seeed-Studio/Seeed_Arduino_LCD/blob/master/examples/320x240/TFT_Meters/TFT_Meters.ino
- https://github.com/BoschSensortec/BSEC-Arduino-library/blob/master/examples/basic/basic.ino

# setup
- install wio terminal for arduino: https://wiki.seeedstudio.com/Wio-Terminal-Getting-Started/ (use boards explorer)
- install bosch bsec library: https://www.arduino.cc/reference/en/libraries/bsec-software-library/ (use library explorer)

# pins
- connect 3v, SPIs and ground (wio and bme680 sensor)

# arduino
- you might have to change I2C address to primary: https://github.com/cpietsch/wio-bme680/blob/main/iaq.ino#L59
- upload iaq.ino to your wio terminal
