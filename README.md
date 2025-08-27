# Neuro-Guard-Intelligent-Seizure-Alert-Device

![Hardware](https://github.com/jananinagarajan0717/Neuro-Guard-Intelligent-Seizure-Alert-Device/blob/main/Hardware.png)

The system is composed of a set of different sensors linked to an ESP32-C3 microcontroller, which is intended to record the first symptoms of seizures and notify about them in real-time. The main parts and their functions are the following:

•	 ADXL345 Accelerometer: Records unexpected or unusual body movements, as a rule, related to seizures.

•	 MAX30102 Heart Rate Sensor: Constantly checks the heart rate of the user and seeks any unusual spikes or drops in heart rate, which can happen during a seizure.

•	 MLX90614 Infrared (IR) Sensor: A non-contact body temperature sensor which can detect thermal anomalies often occur during seizures.

•	ESP32-C3 Microcontroller: The role of the central processing unit. It reads sensors data, analyses them, and makes decisions about whether a seizure is happening or not according to some pre-defined thresholds or patterns.

•	Buzzer: It will be like a local alerting mechanism, to alert the surrounding caregivers or people in the vicinity of a seizure detection.

•	Telegram Bot: The ESP32-C3 connects to the internet and can send data or give alerts through a Telegram bot.

•	Notification System (Telegram & Web Server): Alerts are sent to a remote caregiver or guardian notifying, and can be viewed on a web interface in real-time.

This combined system ensures real-time detection and remote alerting, which provides local and remote assistance to persons undergoing seizures.

![Bot&Webpage](https://github.com/jananinagarajan0717/Neuro-Guard-Intelligent-Seizure-Alert-Device/blob/main/TelegramBot%26Webpage.jpeg)
