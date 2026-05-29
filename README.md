# Smart Surveillance System

An IoT-based Smart Surveillance System built on the ESP32 platform. The system uses sensors and camera modules to detect motion, send alerts, and enable remote access — making it suitable for smart homes, offices, and industrial applications.

---

## How It Works

1. ESP32 continuously monitors the environment via connected sensors
2. On detecting motion or a security trigger, the system captures the event
3. An alert is sent remotely via Wi-Fi
4. Live feed or event data can be accessed remotely
5. The dome enclosure (3D modeled in Fusion 360) houses the hardware for a clean, deployable form factor

---

## Features

- Real-time motion detection and monitoring
- Remote access and alert system over Wi-Fi
- Compact dome enclosure designed in Fusion 360
- Suitable for smart homes, offices, and industrial environments

---

## Hardware Used

| Component | Purpose |
|---|---|
| ESP32 | Main microcontroller with built-in Wi-Fi |
| Camera Module | Visual monitoring and capture |
| PIR / Motion Sensor | Detects movement in the environment |
| Power Supply | Regulated supply for ESP32 and peripherals |

---

## Project Files

| File | Description |
|---|---|
| `Smart_Suvreillance_main.ino` | Main Arduino/ESP32 source code |
| `Robot_Dome.f3d` | Fusion 360 3D model of the enclosure |
| `Circuit Diagram & Component Specifications.pdf` | Full circuit diagram and component details |
| `Experiment Results & Discussion.docx` | Testing results and analysis |

---

## 3D Enclosure

The surveillance dome was custom designed in Fusion 360. Open `Robot_Dome.f3d` in Fusion 360 to view or modify the model.

---

## Setup & Usage

**Requirements:**
- Arduino IDE with ESP32 board support installed
- ESP32 board package: `https://dl.espressif.com/dl/package_esp32_index.json`

**Steps:**

1. Clone the repository
   ```
   git clone https://github.com/Arpanbhuva/Smart-Surveillance-System.git
   ```

2. Open `Smart_Suvreillance_main.ino` in Arduino IDE

3. Install required libraries via Library Manager if prompted

4. Update Wi-Fi credentials in the code:
   ```cpp
   const char* ssid = "YOUR_WIFI_SSID";
   const char* password = "YOUR_WIFI_PASSWORD";
   ```

5. Select the correct ESP32 board and COM port

6. Upload the code to your ESP32

---

## Key Learnings

- ESP32 programming for IoT applications
- Wi-Fi-based remote monitoring and alert systems
- Sensor integration and real-time event detection
- 3D enclosure design using Fusion 360 for hardware deployment

---

## Author

**Arpan Bhuva**  
ECE | IoT & Embedded Systems  
[GitHub Profile](https://github.com/Arpanbhuva)
