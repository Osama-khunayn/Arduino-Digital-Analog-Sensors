# Arduino Digital & Analog Sensors

## 📌 Project Overview
This project demonstrates the difference between digital and analog sensors using Arduino.  
It includes a digital system using a PIR motion sensor and an analog system using a potentiometer to control LED brightness.

---

## 🎯 Project Goal
To understand the difference between digital and analog signals through practical Arduino applications.

---

## 🔵 Digital Sensor (PIR Motion Detection System)

### 📖 Description
The PIR motion sensor detects movement and sends a digital signal to the Arduino.  
When motion is detected, the LED turns ON. Otherwise, it remains OFF.

### ⚙️ Components
- Arduino Uno
- PIR Motion Sensor
- LED
- Resistor
- Breadboard

### 💻 Code
[Open PIR Arduino Code](pir_motion_detection_system1.ino)

### 📷 Circuit
<img src="Screenshot 2026-04-02 010249.png" width="500">

### 🎥 Demo Video
[Watch PIR Motion Detection Demo](PIR-Motion-Detection-System.mp4)

> Note: GitHub may not display `.mp4` videos directly inside the README, so use the link above to open the video.

---

## 🟢 Analog Sensor (Potentiometer System)

### 📖 Description
The potentiometer provides a continuous analog signal from 0 to 1023.  
Arduino reads this value and uses PWM to control LED brightness smoothly.

### ⚙️ Components
- Arduino Uno
- Potentiometer
- LED
- Resistor
- Breadboard

### 💻 Code
[Open Analog Arduino Code](analog_brightness_control_system1.ino)

### 📷 Circuit
<img src="Screenshot 2026-04-02 012541.png" width="500">

### 🎥 Demo Video
[Watch Analog Brightness Control Demo](Analog-Brightness-Control-System.mp4)

> Note: GitHub may not display `.mp4` videos directly inside the README, so use the link above to open the video.

---

## 🧠 Key Concepts
- Difference between digital and analog signals
- `digitalRead()` for digital input
- `analogRead()` for analog input
- `analogWrite()` for PWM output

---

## 📊 Results
- The PIR sensor successfully detects motion and controls the LED as a digital system.
- The potentiometer successfully controls LED brightness as an analog system.
- The project clearly demonstrates the practical difference between digital and analog sensors.

---

## 🛠️ Simulation
This project was designed and tested using Tinkercad.

---

## 🚀 Future Improvements
- Combine both systems into one smart project
- Add LCD display for sensor values
- Add buzzer or alarm for motion detection
