# 🔒 Laser Security Alarm System using Arduino

## 📖 Overview
This project is a *Laser Security Alarm System* built using Arduino.  
It creates an invisible security barrier using a *laser beam* and an *LDR (Light Dependent Resistor)*.  
When the beam is interrupted by an intruder, the Arduino detects the change in light intensity and triggers an *alarm (buzzer + LED)*.  

The system is *low-cost, easy to implement, and reliable*, making it suitable for homes, offices, and restricted areas.  


## 🎯 Objectives
- Design a simple and cost-effective security system.  
- Detect intrusions in real-time using a laser beam and LDR.  
- Trigger visual and sound alerts when unauthorized access occurs.  
- Provide a scalable system that can be extended with IoT or GSM modules.  

## 🛠 Components Required
| Component | Quantity | Description |
|-----------|----------|-------------|
| Arduino Uno | 1 | Main controller (ATmega328P) |
| 5V Laser Module | 1 | Emits focused laser beam |
| LDR (Light Dependent Resistor) | 1 | Detects laser light |
| Buzzer | 1 | Generates alarm sound |
| LEDs (Red & Green) | 4 | Status indication |
| Breadboards | 2 | Circuit prototyping |
| Jumper Wires | 15 | Connections |
| Resistors (220Ω, 10kΩ) | 6 | Current limiting & voltage divider |
| Push Button | 1 | Arm/Disarm control |

## ⚡ Working Principle
1. A *laser beam* is projected onto the LDR.  
2. The *LDR resistance* stays low when the beam is uninterrupted.  
3. When an object blocks the beam, LDR resistance increases.  
4. Arduino detects this change and *triggers the buzzer and LEDs*.  
5. The system can be armed/disarmed using a push button.  

