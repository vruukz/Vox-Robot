# Vox — AI-Powered Home Companion Robot

![1743521838430](https://github.com/user-attachments/assets/51366c89-9410-4cb3-85a3-76edee9ad24b)
![3dmodelrobot](https://github.com/user-attachments/assets/097725c4-4978-41e4-b261-461f29a06c57)

Vox is a fully custom-built AI-powered home companion robot — my Bachelor's thesis project at the Technical University of Cluj-Napoca. Every part of it is original work: the chassis was designed in Blender and 3D printed, the electronics were hand-wired, and the software stack runs entirely on a Raspberry Pi 4.

## Current Capabilities

- 🎮 **Manual control** via keyboard or gamepad
- 🎙️ **AI voice assistant** powered by the OpenAI API — natural language interaction
- 😊 **Animated facial expressions** displayed on a TFT touchscreen
- 🖨️ **Fully 3D-printed enclosure** — custom designed from scratch in Blender

## Roadmap

- 👁️ Computer vision — object and face recognition via USB webcam
- 🗺️ Autonomous navigation using ultrasonic sensors
- 🔄 Closed-loop motor control with encoders for accurate movement (Master's thesis extension)
- 🤖 Integration with more advanced AI models

## Tech Stack

- **Platform:** Raspberry Pi 4
- **Language:** Python
- **AI:** OpenAI API
- **Motor control:** L298N Dual Motor Driver + PWM
- **Display:** TFT Touchscreen (animated expressions)
- **Input:** USB Webcam, Microphone, Speaker

## Bill of Materials

| Component | Details |
|---|---|
| Raspberry Pi 4 | Main compute unit |
| L298N Motor Driver | Dual H-bridge motor control |
| 2× 12V DC Motors | Tracked drive system |
| 3× 18650 Li-ion Batteries | Motor power supply |
| External USB Battery | Raspberry Pi power supply |
| USB Webcam | Future vision recognition |
| 3D-Printed Enclosure | Custom designed in Blender |
| Plexiglass Chassis | Robot base structure |
| TFT Touchscreen | Animated facial expressions |
| Speaker + Microphone | Voice assistant I/O |

## Background

Vox started as my Bachelor's thesis in Robotics (English programme) at TUCN and is actively being extended as part of my Master's in AI in Industrial Production. The goal is to evolve it from a manually operated prototype into a fully autonomous companion robot with computer vision and self-navigation.

---

*Built by Cărpinișan Andrei — Automation & Robotics Engineer*
