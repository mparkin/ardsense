# Demo Setup Sensors

## Aduino mini ( Genuino )

### Description
This connects a mass scale to the arduino and a Pressure sensor to the arduino.

1. A0/A1 are bit bang serial connections to the HX711 load sensor amp.
2. A3 is the connection to the 0-5V analog signal from the Pressure sensor.
3. The data are collected and sent out through the USB connector via a standard serial connection

### Status

1. Basic communication tested
2. Serial output message defined. ( "Single mass reading","AVG mass reading","Pressure Reading")


### TO DO
1. Output is raw sensor data. Needs to be calibrated and interpolated to grams and PSI.

   
