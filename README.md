# Arduino Uno Mobile Controller Robot (Bluetooth and Cloud)

This project is an Arduino Uno-based robot that can be controlled using Bluetooth and a cloud connection. The robot is equipped with a Bluetooth module (HC-05/HC-06) for local control and can also be remotely operated using cloud platforms like Blynk or ThingSpeak.

## Features:
- Bluetooth-based control via a mobile app
- Cloud-based control via Blynk/ThingSpeak
- Move the robot forward, backward, left, or right

## Components Required:
- Arduino Uno
- Bluetooth Module (HC-05/HC-06)
- DC Motors with Motor Driver (e.g., L298N)
- ESP8266 (for Wi-Fi connection if using cloud control)
- Power supply for motors and Arduino

## Setup Instructions:
1. **Bluetooth Control**:
   - Pair your phone with the Bluetooth module.
   - Install a Bluetooth terminal app on your mobile phone (e.g., Bluetooth Terminal).
   - Use the app to send commands (`F`, `B`, `L`, `R`) to control the robot.

2. **Cloud Control**:
   - Set up a cloud platform like [Blynk](https://blynk.io) or [ThingSpeak](https://thingspeak.com).
   - Connect your Arduino to Wi-Fi using the ESP8266 module.
   - Use the provided Blynk/ThingSpeak template to send commands to the robot.

## How to Run:
1. Open the `bluetooth_controller.ino` for Bluetooth control or `cloud_controller.ino` for cloud control in Arduino IDE.
2. Upload the code to your Arduino Uno.
3. Follow the setup instructions for Bluetooth or Cloud control.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

