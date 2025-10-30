
# ♻️ ECOMATIC — Automated Robot for Cleaning Surroundings and Waste Collection with Segregation

![IJARIIE](https://img.shields.io/badge/IJARIIE-Published-blue?style=for-the-badge)
![IoT](https://img.shields.io/badge/IoT-Enabled-orange?style=for-the-badge)
![NodeMCU](https://img.shields.io/badge/NodeMCU-ESP8266-green?style=for-the-badge)
![SmartCity](https://img.shields.io/badge/Smart_City-Automation-lightblue?style=for-the-badge)
![License](https://img.shields.io/badge/License-Academic_Publication-lightgrey?style=for-the-badge)

---

## 📄 Publication Details
- **Paper ID:** IJARIIE27547  
- **Journal:** *International Journal of Advance Research and Innovative Ideas in Education (IJARIIE)*  
- **Volume:** 11 | **Issue:** 5 | **Year:** 2025  
- **Authors:** Mr. Jagannath B. R., Ms. Kavya M. D., Mr. Keerthan Murthy S., Mr. Mohith C., **Mr. Nandan U**  
- **Affiliation:** Department of Electronics and Communication Engineering, Vidya Vikas Institute of Engineering & Technology (VVIET), Mysuru  
- 📎 [View Publication (Adobe Acrobat link)](https://acrobat.adobe.com/id/urn:aaid:sc:AP:f18d95d4-6ec1-4f48-8f9b-eedbb86a6b4c)

---

## 🔍 Abstract
**ECOMATIC** is an intelligent, autonomous robot designed for **waste collection, cleaning, and segregation** in public environments such as roadsides, campuses, and parks.  
It employs a **NodeMCU microcontroller** as its core controller, integrating **ultrasonic sensors** for obstacle avoidance, **IR sensors** for navigation, and a **soil moisture sensor** for wet/dry waste classification.  
The system achieves **85% waste collection efficiency** and **88% segregation accuracy**, proving its effectiveness as a **smart city sanitation solution**.

---

## 🧠 Key Highlights
- **Controller:** NodeMCU (ESP8266) — Wi-Fi and IoT ready  
- **Sensors:** Ultrasonic (HC-SR04), IR line follower, Soil moisture sensor  
- **Actuators:**  
  - DC motors (mobility & brush rotation)  
  - SG90 servo motors (waste segregation gates)  
- **Power Supply:** Battery + voltage regulation circuit  
- **Software Tools:** Arduino IDE (C/C++), Servo.h, NewPing.h, ESP8266WiFi.h  
- **Applications:**  
  - Smart city waste collection  
  - Public sanitation  
  - Autonomous cleaning in educational or industrial campuses  

---

## ⚙️ System Overview
The robot’s architecture is divided into **hardware**, **software**, and **control logic** modules:

### 🔧 Hardware
| Module | Component | Function |
|--------|------------|-----------|
| Central Controller | NodeMCU (ESP8266) | Processes sensor data and controls motors/servos |
| Mobility | DC motors + L298N driver | Enables forward, reverse, and turn movement |
| Cleaning | Rotating brush motor | Sweeps debris into collection bay |
| Waste Detection | Soil moisture sensor | Classifies waste as wet (organic) or dry (inorganic) |
| Segregation | SG90 servo motor | Directs waste into correct bin |
| Navigation | IR line sensors | Detects and follows cleaning paths |
| Obstacle Detection | Ultrasonic sensors | Avoids obstacles within range |
| Power System | Battery + Regulator | Ensures stable voltage for all modules |

---

## 🧭 Control Logic
1. **Initialization:** Calibrates sensors and motors; connects to Wi-Fi if enabled.  
2. **Line Following:** IR sensors guide the robot along a predefined path.  
3. **Cleaning:** Front brush sweeps debris while moving forward.  
4. **Waste Detection:** Sensors detect debris and trigger classification.  
5. **Segregation:**  
   - Wet → Directed to wet waste bin  
   - Dry → Directed to dry waste bin  
6. **Obstacle Avoidance:** Ultrasonic sensors detect and reroute around objects.  
7. **IoT Logging (Future):** Transmits data to cloud for monitoring and analytics.

---

## 📈 Performance Evaluation
| Parameter | Result | Remarks |
|------------|---------|----------|
| Waste collection efficiency | 85% | Effective brush mechanism |
| Waste segregation accuracy | 88% | Moisture-sensor-based detection |
| Cleaning coverage | 92% for 5 m² area | High surface efficiency |
| Obstacle avoidance | 100% within 15 cm | Reliable ultrasonic response |
| Continuous operation | 2–3 hours | Battery-powered |
| IoT data logging | Successful prototype | Ready for smart city integration |

---

## 🌱 Future Enhancements
- **IoT Integration:** Cloud-based bin monitoring and analytics  
- **Solar Power:** Autonomous energy harvesting  
- **AI Waste Detection:** Vision-based CNN classification using TensorFlow Lite  
- **Enhanced Navigation:** GPS and SLAM for unstructured environments  
- **Modular Bins:** Detachable smart bins with fill-level sensors  

---

## 🧩 Repository Structure
```
/ECOMATIC/
 ├── Code/
 │   ├── ecomatic_main.ino
 │   ├── sensor_modules/
 │   ├── motor_control/
 ├── Hardware_Diagram/
 ├── Simulation/
 ├── Test_Results/
 ├── Images/
 ├── IJARIIE27547_Paper.pdf
 └── README.md
```

---

## 📘 Citation
> **Jagannath B. R., Kavya M. D., Keerthan Murthy S., Mohith C., and Nandan U.**  
> *“ECOMATIC – Automated Robot for Cleaning Surroundings and Waste Collection with Segregation”*  
> *International Journal of Advance Research and Innovative Ideas in Education (IJARIIE)*,  
> Vol. 11, Issue 5, 2025.  
> [Read Paper 📄](https://ijariie.com/FormDetails.aspx?MenuScriptId=27547)

---

## 📚 BibTeX
```bibtex
@article{nandan2025ecomatic,
  author  = {Jagannath B R and Kavya M D and Keerthan Murthy S and Mohith C and Nandan U},
  title   = {ECOMATIC: Automated Robot for Cleaning Surroundings and Waste Collection with Segregation},
  journal = {International Journal of Advance Research and Innovative Ideas in Education (IJARIIE)},
  volume  = {11},
  number  = {5},
  year    = {2025},
  paperid = {IJARIIE27547}
}
```

---

## 👨‍💻 Author
**Name:** Nandan U  
🎓 B.E. Electronics and Communication Engineering  
🏫 Vidya Vikas Institute of Engineering & Technology (VVIET), Mysuru – India  
📧 nandanunandanu1@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/nandan-u-473a85226/) • [GitHub](https://github.com/Nandronic) • [ResearchGate](#)

---

## 🏁 Keywords
`Autonomous Robot` • `Waste Segregation` • `Smart City` • `NodeMCU ESP8266` • `Ultrasonic Sensor` • `IoT Robotics` • `Embedded Systems`

---

> ⭐ **Status:** Peer-Reviewed and Published in IJARIIE Vol 11 Issue 5 (2025)
