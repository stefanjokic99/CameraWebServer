# ESP-32 Camera Streaming

This project provides an example of streaming camera data from an Arduino-based board. The code configures the camera module, sets up a Wi-Fi connection, and streams the camera feed over a local network.

## Prerequisites

- Arduino board with a compatible camera module
- Wi-Fi module (if not built into the board)
- Wi-Fi network credentials (SSID and password)

## Getting Started

1.Install ArduinoIDE Link: https://www.arduino.cc/en/software 

2. File / Preferences  -> additional board Manager URLs: 
http://arduino.esp8266.com/stable/package_esp8266com_index.json,https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json. 
You must wait for install after OK.

3. Tools / board / board manager…  (search for) “ESP 32” —> install the library "esp32 by Espressif Systems".

4. Tools / Board / esp32 / AI Thinker ESP 32

5. Clone this repository to your local machine.

6. Run .ino file

7. Connect esp32 with usb cable to computer 

8. Select the correct COM port

9. Enter your Wi-Fi credentials in the code:

```cpp
const char* ssid = "your-ssid";
const char* password = "your-password";

10. Configure baund in serial monitor Tools -> Serial Monitor. In terminal change baud to 115200 baud.

11. After that click on Upload -> sign to te right of correct sign. 

