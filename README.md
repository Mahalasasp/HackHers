# HackHers 

# Smart Women-Centric Home Safety System

## Overview
Women’s safety within residential spaces remains a critical concern, particularly in urban and semi-urban areas. Traditional security measures often fail to provide real-time awareness of potential intrusions. This project presents a smart home monitoring system equipped with motion sensors and audio alerts to enhance security and provide real-time awareness.

## Features
- **Motion Detection:** PIR sensor detects movement within a customizable range of 3 to 25 feet.
- **Audio Alert System:** Voice Recording Module (ISD1820) plays a pre-recorded alert message upon motion detection.
- **Amplified Output:** Power Amplifier (PAM1804) ensures loud and clear alerts.
- **Volume Control:** Users can adjust alert loudness using a potentiometer.
- **Power Status Indicator:** LED indicator provides visibility on power status.
- **Battery Backup:** Ensures uninterrupted operation in case of power outages.

## Tech Stack
### Hardware Components:
- **Arduino Nano** – Microcontroller for processing sensor data
- **PIR Sensor** – Motion detection sensor
- **Voice Modulator (ISD1820)** – Generates alert messages
- **Power Supply Module** – Converts 220V AC to 5V DC (LM7805 Regulator)
- **Amplifier (PAM1804)** – Boosts the audio output
- **Speakers** – Audio alert system
- **Rectifier & Transformer** – Converts AC to DC power

### Software & Communication:
- **Arduino IDE** – Coding and flashing the microcontroller
- **C++ (Embedded C)** – Programming the Arduino Nano

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-link.git
   ```
2. Install **Arduino IDE** and connect the **Arduino Nano**.
3. Open the project files in Arduino IDE.
4. Compile and upload the code to the Arduino Nano.
5. Assemble the hardware components as per the circuit diagram.
6. Power up the system and test motion detection and audio alerts.

## How It Works
1. **Motion Detection:** When movement is detected, the PIR sensor triggers an alert.
2. **Audio Alert Activation:** The ISD1820 voice module plays a pre-recorded message.
3. **Amplification & Output:** The audio output is boosted and played through speakers.
4. **Power Backup:** The system remains functional even during power failures.

## Contributors
- Mahalasa S P
- Vidhi D Kamat
- S Alisha
- T N Harsha Shriya

