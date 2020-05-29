# Turn LED ON/OFF from Firebase using ESP32

Here I have shared the arduino code and the libraries you will need to do this project.

To istall the ESP32 Board open your preferences press Ctrl+Comma or go to (File) tab and click on (Preferences). There in the additional boards manager URLs paste this URLs: 
https://dl.espressif.com/dl/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json
Then open (Boards Manager) window from (Tools) tab and there type "ESP32" and install the software.

Now to use the IOXhop_FirebaseESP32-master library you will need the ArduinoJson-v5.13.3.zip library and ArduinoJson-v5.13.3.h in your project's folder.

Then just go to Firebase website and open a project. After that. creat a databese. In the realtime database you will find the URL for the arduino code and you will find the database auth key from (Project Settings)>(Service Accounts)>(Database Secrets).
In the realtime database type the value as "ON/OFF" and your done. :D
