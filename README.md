# **Automated-Door-System-using-NodeMCU-Blynk-and-Ultrasonic-Sensor**
This project is an IoT-based Automated Door System that uses a NodeMCU (ESP8266), ultrasonic sensor, servo motor, and the Blynk platform to detect motion and control door opening/closing remotely.

**Features:**
- Proximity detection using an ultrasonic sensor
- Automatic door control with a servo motor
- Real-time status updates via Blynk mobile app
- Displays "WELCOME HOME" when someone is detected
- Door stays open for 5 seconds, then closes automatically


**Technologies Used:**
- NodeMCU ESP8266
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- Blynk IoT Platform
- Arduino IDE


**How It Works:**
1. The ultrasonic sensor measures the distance in front of the door.
2. If a person is detected within 20 cm, the servo opens the door.
3. A message is sent to the Blynk app: "WELCOME HOME".
4. After 5 seconds, the door closes and status resets to "System Ready".

**Blynk Setup:**
- Use your own BLYNK_TEMPLATE_ID, BLYNK_TEMPLATE_NAME, and BLYNK_AUTH_TOKEN.
- Connect to your Wi-Fi network by updating the SSID and password.
