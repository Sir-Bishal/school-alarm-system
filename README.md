# school-alarm-system
A standalone bell system using ESP32, RTC DS3231, Relay Module, and 16x2 Display. It features a preset bell schedule with manual time setting, and does not require internet connectivity.


Connections Between Components

Relay Module:
Connect the IN pin of the relay module to GPIO 23 (RELAY_PIN).

Buttons:
BTN_MODE: Connect the button to GPIO 32 (BTN_MODE).
BTN_UP: Connect the button to GPIO 33 (BTN_UP).
BTN_DOWN: Connect the button to GPIO 25 (BTN_DOWN).
BTN_SET: Connect the button to GPIO 26 (BTN_SET).
BTN_MANUAL: Connect the button to GPIO 27 (BTN_MANUAL).

Buzzer:
Connect the positive terminal of the buzzer to GPIO 4 (BUZZER_PIN).
Connect the negative terminal to GND.

16x2 LCD (I2C):
VCC: Connect to 3.3V on ESP32.
GND: Connect to GND on ESP32.
SDA: Connect to GPIO 21 (SDA) on ESP32.
SCL: Connect to GPIO 22 (SCL) on ESP32.

RTC DS3231 (I2C):
VCC: Connect to 3.3V on ESP32.
GND: Connect to GND on ESP32.
SDA: Connect to GPIO 21 (SDA) on ESP32.
SCL: Connect to GPIO 22 (SCL) on ESP32.

Relay Module:
VCC: Connect to 5V on ESP32.
GND: Connect to GND on ESP32.
IN: Connect to GPIO 23 (RELAY_PIN) on ESP32.
