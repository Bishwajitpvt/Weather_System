# Weather System

# Components

1. Nodemcu ESP8266
2. DHT11 sensor
3. BMP180 sensor
4. Rain sensor
5. Breadboard
6. LDR sensor
7. LCD display
8. I2C module


# Circuit Diagram

![Capture-4NzaVL5wP-transformed](https://user-images.githubusercontent.com/77453811/230739631-eddbfd24-080c-4407-884a-abc8b2382a81.png)

# Installing the ESP8266 Board
1. Go to File =>  Preferences to open the Preferences window in the Arduino IDE.
2. Copy this URL: http://arduino.esp8266.com/stable/package_esp8266com_index.json and paste it into Additional Boards Manager URLs 
3. Then go to Tools => Board =>  Boards Manager.
4. Write ESP8266 in the search column and Install the latest version of **" esp8266 by ESP8266 Community"**
5. Now open Arduino " Tools Menu
6. Select Board => scroll down to ESP8266 Modules => Select NodeMCU 1.0(ESP-12E Module)

# Library

1. Adafruit Unified Sensor by Adafruit
2. Blynk by Volodymyr Shymanskyy
3. DHT sensor library by Adafruit Version 1.4.4
4. Grove Barometer Sensor by Seeed Studio Version 2.1.0
5. LiquidCrystal 12C by Frank de Brabander Version 1.1.2
