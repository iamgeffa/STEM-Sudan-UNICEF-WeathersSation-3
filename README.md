#Project Name
Weather Station with DHT11 and BMP180 sensors and ThingSpeak IoT platform

Description
This project uses an ESP8266 microcontroller with DHT11 temperature and humidity sensor and BMP180 barometric pressure sensor to measure and monitor environmental conditions. The readings are sent to the ThingSpeak IoT platform for data visualization and analysis. The program is written in Arduino IDE using C++ language.

Installation
To run this program, you need the following components:

ESP8266 microcontroller board
DHT11 temperature and humidity sensor
BMP180 barometric pressure sensor
Breadboard
Jumper wires
USB cable
Computer with Arduino IDE installed
Follow these steps to set up the project:

Connect the ESP8266 board to your computer via USB cable.
Open Arduino IDE and go to File > Preferences.
In Additional Boards Manager URLs, add the following URL: http://arduino.esp8266.com/stable/package_esp8266com_index.json
Go to Tools > Board > Boards Manager and search for ESP8266. Install the package by ESP8266 Community.
Go to Sketch > Include Library > Manage Libraries and install the following libraries: ESP8266WiFi, WiFiClient, ESP8266HTTPClient, Adafruit_Sensor, DHT, and Adafruit_BMP085.
Copy and paste the code from the program file into Arduino IDE.
Replace the Wi-Fi credentials and ThingSpeak API key with your own values.
Connect the DHT11 sensor to the ESP8266 board's GPIO2 pin and the BMP180 sensor to the SDA and SCL pins.
Upload the program to the ESP8266 board.
Open the serial monitor to view the sensor readings and check if the data is being sent to ThingSpeak.
Usage
This program measures temperature, humidity, barometric pressure, and altitude using DHT11 and BMP180 sensors and sends the data to ThingSpeak for monitoring and analysis. To use this program, follow the installation instructions and connect the sensors to the ESP8266 board. You can view the sensor readings on the serial monitor and the data visualization on the ThingSpeak platform.

Contributing
If you want to contribute to this project, you can submit a pull request with your proposed changes or improvements. Make sure to follow the coding style and keep the program simple and efficient.

License
This project is licensed under the MIT License - see the LICENSE file for details.
