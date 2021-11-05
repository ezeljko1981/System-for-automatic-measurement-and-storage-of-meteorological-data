# System for automatic measurement and storage of meteorological data
NodeMCU_Firebase Library for reading values from sensors for temperature, pressure and humididty and sending value to Firebase.

 The circuit:
  BMP180     NODEMCU
  -------------
  SCL        D1
  SDA        D2
  VCC        3.3V
  GND        0V
  
  DHT22      NODEMCU
  -------------
  DATA       D3 
  VCC        5V
  GND        0V
