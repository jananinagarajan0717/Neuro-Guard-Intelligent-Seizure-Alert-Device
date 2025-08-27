# Neuro-Guard-Intelligent-Seizure-Alert-Device

📑 Patent Status: Application Published (Patent Pending)

![Hardware](https://github.com/jananinagarajan0717/Neuro-Guard-Intelligent-Seizure-Alert-Device/blob/main/Hardware.png)

The system is composed of a set of different sensors linked to an ESP32-C3 microcontroller, which is intended to record the first symptoms of seizures and notify about them in real-time. The main parts and their functions are the following:

**•**	**ADXL345 Accelerometer:** Records unexpected or unusual body movements, as a rule, related to seizures.

**•**	 **MAX30102 Heart Rate Sensor:** Constantly checks the heart rate of the user and seeks any unusual spikes or drops in heart rate, which can happen during a seizure.

**•**	**MLX90614 Infrared (IR) Sensor:** A non-contact body temperature sensor which can detect thermal anomalies often occur during seizures.

**•** **ESP32-C3 Microcontroller:** The role of the central processing unit. It reads sensors data, analyses them, and makes decisions about whether a seizure is happening or not according to some pre-defined thresholds or patterns.

**•** **Buzzer:** It will be like a local alerting mechanism, to alert the surrounding caregivers or people in the vicinity of a seizure detection.

**•**	**Telegram Bot:** The ESP32-C3 connects to the internet and can send data or give alerts through a Telegram bot.

**•**	**Notification System (Telegram & Web Server):** Alerts are sent to a remote caregiver or guardian notifying, and can be viewed on a web interface in real-time.

This combined system ensures real-time detection and remote alerting, which provides local and remote assistance to persons undergoing seizures.

![Bot&Webpage](https://github.com/jananinagarajan0717/Neuro-Guard-Intelligent-Seizure-Alert-Device/blob/main/TelegramBot%26Webpage.jpeg)

#Abstract
t- Seizure attacks chronically affect many lives globally, and their manifestations are frequent and call for urgent assistance. As such, this project’s primary goal is to develop a wearable seizure attack detection device that constantly monitors a patient’s movement, pulse, and body temperature. The Seeed Studio XIAO ESP32-C3 microcontroller will be used as the core processing unit due to its smaller size and reduced power consumption, built-in Wi-Fi and Bluetooth for real-time alerts, an ADXL345 accelerometer for capturing sudden, unexpected jolting movements, a heart rate sensor that is able to detect bolus beats, and an MLX90614 infrared sensor to track temperature fluctuations. After the seizure is diagnosed, the warning system is initiated, which activates a buzzer for prompt notice. For improved security, the system can connect via Bluetooth or the Internet of Things (IoT) to send instant notifications through mobile phone to the caregivers.
