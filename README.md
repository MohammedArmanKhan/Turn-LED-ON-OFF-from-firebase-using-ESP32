# Turn LED ON/OFF from Firebase using ESP32

Here I have shared the arduino code and the libraries you will need to do this project.

Components: ESP32, LED, Jumper Wire, Bread Board, Good data cable.
In bread board connect the LED's long pin to ESP32's pin2 and LED's short pin to ESP32's GND.

To install the ESP32 Board open your preferences press Ctrl+Comma or go to (File) tab and click on (Preferences). There in the additional boards manager URLs paste this URLs: 
https://dl.espressif.com/dl/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json
Then open (Boards Manager) window from (Tools) tab and there type "ESP32" and install the software.

Now to use the (IOXhop_FirebaseESP32-master) library you will need the (ArduinoJson-v5.13.3.zip) library. Also you need to keep the (ArduinoJson-v5.13.3.h) file in your project's folder.
Arduino library location: user> Documents> Arduino> libraries.

Then just go to Firebase website and open a project. After that. creat a database. In the realtime database you will find the URL for the arduino code copy it without any slashes and you will find the database auth key from (Project Settings)>(Service Accounts)>(Database Secrets) paste it in the arduino code. In the arduino code type your wifi name and password. In the code change Firebase.setString(); and Firebase.getString(); to the realtime string data which have auto genarated. you and create new data too i.e: "LED_STATUS". Finnaly, in the realtime database type the value as "ON/OFF" and your done. :D

Youtube Video tutorial: https://youtu.be/eY6rufd4vnc
