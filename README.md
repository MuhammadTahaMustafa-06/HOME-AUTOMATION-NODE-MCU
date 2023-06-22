# Home Automation Project with Arduino

This project enables home automation using an Arduino board and Blynk IoT platform. It allows you to control various devices connected to the Arduino remotely using a mobile app.

## Prerequisites

- Arduino board (e.g., ESP8266)
- WiFi network credentials
- Blynk IoT platform account

## Getting Started

1. Clone or download this project repository.

2. Connect the Arduino board to your computer.

3. Install the necessary libraries:
   - ESP8266WiFi
   - Blynk

4. Open the Arduino IDE.

5. Modify the following lines in the code:

   ```cpp
   #define BLYNK_TEMPLATE_ID "TMPL6KzRzftJ_"
   #define BLYNK_TEMPLATE_NAME "HOME AUTOMATION"
   #define BLYNK_AUTH_TOKEN "VNLUr1fdr9Mrvla6H_gDOEe7FkLMoyC0"
   char ssid[] = "TP-Link_FFA4";
   char password[] = "@surti1122";
Replace the values with your Blynk template ID, template name, Blynk authentication token, WiFi SSID, and password.

6.Upload the code to your Arduino board.

7.Open the Serial Monitor to view the debug information.

8.Launch the Blynk mobile app on your device.

9.Create a project in the Blynk app and configure the following widgets:

10.Four buttons (V1, V2, V3, V4) for controlling the relays.
Run the project and enjoy controlling your home automation devices remotely!

## Circuit Diagram
![Project Image](https://github.com/MuhammadTahaMustafa-06/HOME-AUTOMATION-NODE-MCU/blob/33700fe7ee20d474614314be27a09edb1b3e4ac5/Home%20Automation.jpg)

## License
This project is licensed under the MIT License.
