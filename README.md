# bmp280-logger-arduino
* Program to log BMP280 data feed to an external memory card using an SD card reader

## Prerequisites
* Adruino UNO
* SD card reader
* MicroSD card
* BMP280 barometric pressure sensor
* Jumper wires
* PC with Arduino IDE installed

## Instructions
* Connect the BMP280 sensor and the SD card reader to the Arduino UNO as shown below

* **Interfacing BMP280 to Arduino UNO** <br>

  ![Image](/component-library/images/bmp280.jpeg) <br>
  
  VCC -> 5V <br>
  GND -> GND <br>
  SCL -> A5 or SCL <br>
  SDA -> A4 or SDA <br>
  CSB -> Not connected <br>
  SDO -> Not connected <br>
  
* **Interfacing SD Card Reader to Arduino UNO** <br>

  ![Image](/component-library/images/Micro-SD-Card-Reader-Module.jpg) <br>

  C5 -> 10 <br>
  SCK -> 13 <br>
  MOSI -> 11 <br>
  MISO -> 12 <br>
  VCC -> 5V <br>
  GND -> GND <br>
