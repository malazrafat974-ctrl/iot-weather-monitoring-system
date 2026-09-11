IoT Weather Monitoring System
Project Description

The IoT Weather Monitoring System is an Arduino-based project designed to monitor environmental conditions in real time.

The system uses a DHT11 sensor to measure temperature and humidity and an LDR sensor to measure light intensity. The collected data is processed by an Arduino Uno and displayed on a 16×2 LCD. The readings can also be monitored through the Arduino Serial Monitor.

This project demonstrates the basic concepts of IoT, sensor data collection, microcontroller programming, and real-time data display.

Features
Measures temperature using a DHT11 sensor.
Measures humidity using a DHT11 sensor.
Measures light intensity using an LDR sensor.
Displays sensor readings on a 16×2 LCD.
Uses a 10kΩ potentiometer to adjust the LCD contrast.
Displays sensor data through the Serial Monitor.
Updates environmental readings continuously.
Uses simple and low-cost hardware.
Hardware Requirements
Arduino Uno
DHT11 Temperature and Humidity Sensor
LDR (Light Dependent Resistor)
16×2 LCD Display
10kΩ Resistor
10kΩ Potentiometer
Breadboard
Jumper Wires
USB Cable
Software Requirements
Arduino IDE
DHT sensor library
Adafruit Unified Sensor library
LiquidCrystal library
Installation
1. Clone the Repository
git clone https://github.com/malaz/iot-weather-monitoring-system.git
2. Open the Project

Open the project folder and locate the Arduino source file:

iot-weather-monitoring-system/
└── weather_monitor.ino

Open weather_monitor.ino using the Arduino IDE.

3. Install the Required Libraries

In Arduino IDE, go to:

Sketch → Include Library → Manage Libraries

Search for and install:

DHT sensor library
Adafruit Unified Sensor

The LiquidCrystal library is included with the Arduino IDE.

4. Connect the Hardware

Connect the components to the Arduino Uno according to the following configuration.

DHT11
DHT11	Arduino Uno
VCC	5V
DATA	D2
GND	GND
LDR
LDR	Arduino Uno
Sensor Output	A0
VCC	5V
GND	GND

The LDR is connected with a 10kΩ resistor to form a voltage divider.

LCD 16×2 and Potentiometer

The 10kΩ potentiometer is used to adjust the contrast of the LCD display.

LCD / Potentiometer	Arduino Uno
LCD VSS	GND
LCD VDD	5V
LCD V0	Potentiometer middle pin
LCD RS	D7
LCD RW	GND
LCD E	D6
LCD D4	D5
LCD D5	D4
LCD D6	D3
LCD D7	D8
LCD A	5V through a resistor
LCD K	GND
Potentiometer Pin 1	5V
Potentiometer Pin 2	LCD V0
Potentiometer Pin 3	GND

Turn the potentiometer to adjust the LCD contrast until the text is clearly visible.

Hardware Setup




5. Upload the Code
Connect the Arduino Uno to the computer.
Open weather_monitor.ino.
Select Arduino Uno from Tools → Board → Arduino Uno.
Select the correct COM port.
Click Upload.
Arduino IDE










Usage

After uploading the program:

Power the Arduino Uno.
The LCD displays the system startup message.
The system reads temperature, humidity, and light intensity.
Temperature and humidity are displayed on the LCD.
The light intensity reading is displayed after a few seconds.
The same sensor readings are printed on the Serial Monitor.
Open the Serial Monitor and set the baud rate to 9600.
Example LCD Output
Temp: 27.0°C
Humidity: 52%

After a few seconds:

Light:
680
Example Serial Monitor Output
IoT Weather Monitoring System
-----------------------------
Temperature: 27 C
Humidity: 52 %
Light Intensity: 680
-----------------------------

The readings are continuously updated according to the surrounding environmental conditions.

Project Structure
iot-weather-monitoring-system/
│
├── weather_monitor.ino
├── README.md
└── LICENSE
Contributors

Malaz — Project development, Arduino programming, hardware integration, testing, and documentation.

License

This project is developed for educational purposes and is available under the MIT License.
