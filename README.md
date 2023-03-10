# bmp280-logger-arduino
* Program to log BMP280 data feed to an external memory card in `.csv` and `.txt` formats using a MicroSD card reader

## Prerequisites
* Adruino UNO
* MicroSD card reader
* MicroSD card
* BMP280 barometric pressure sensor
* Jumper wires
* PC with Arduino IDE installed

## Instructions
* Connect the BMP280 sensor and the MicroSD card reader to the Arduino UNO as given below

* **Interfacing BMP280 to Arduino UNO** <br>

  ![Image](/component-library/images/bmp280.jpeg) <br>
  
  VCC -> 5V <br>
  GND -> GND <br>
  SCL -> A5 or SCL <br>
  SDA -> A4 or SDA <br>
  CSB -> Not connected <br>
  SDO -> Not connected <br>
  
* **Interfacing MicroSD Card Reader to Arduino UNO** <br>

  ![Image](/component-library/images/Micro-SD-Card-Reader-Module.jpg) <br>

  C5 -> 10 <br>
  SCK -> 13 <br>
  MOSI -> 11 <br>
  MISO -> 12 <br>
  VCC -> 5V <br>
  GND -> GND <br>

* Open `bmp280_logger_skg-10.ino` using Arduino IDE
* Connect the UNO to the computer and select the correct COM port 
* Insert the MicroSD card in the MicroSD card reader
* Upload the program
* Voila! The data feed from the BMP280 sensor will now be logged on the MicroSD in `.csv` and `.txt` formats
