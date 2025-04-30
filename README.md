# 🚗 Motor Control for a Smart Car

A cost-effective motor control system that allows **bidirectional control and adjustable speed** of two DC motors without using microcontrollers. Built using the classic NE555 Timer IC and an H-Bridge circuit composed of TIP142/147 transistors.

## 📌 Project Highlights

- 🌀 **PWM-based Speed Control** using 555 timer in astable mode
- 🔁 **Direction Control** using a discrete H-Bridge circuit
- ⚙️ Fully tested via **simulation, breadboarding, and PCB fabrication**
- 🧠 Ideal for: Robotics, automation systems, and mechatronics education

## 🧰 Components Used

- NE555 Timer IC
- TIP142 (NPN) & TIP147 (PNP) Power Transistors
- BC337 Transistors (as drivers)
- Dual Shaft DC Motors
- 1MΩ Potentiometers
- SPDT Toggle Switches
- Diodes, LEDs, Capacitors, Resistors
- Custom-designed PCB

## 🛠️ How It Works

- **Speed Control**: Achieved by varying the PWM duty cycle output of the 555 timer using a potentiometer.
- **Direction Control**: Achieved by toggling SPDT switches that activate different branches of the H-Bridge.

## ⚡ Circuit Overview

- Each motor is connected to a dedicated 555 timer and an H-Bridge
- PWM frequency and duty cycle are adjustable
- H-Bridge direction logic:
  - `IN1 = HIGH, IN2 = LOW`: Forward
  - `IN1 = LOW, IN2 = HIGH`: Reverse

## 🧪 Project Steps

1. **Simulation** in Proteus
2. **Breadboard Testing**
3. **Schematic & PCB Design** using Altium
4. **3D Visualization**
5. **Gerber File Export**
6. **PCB Fabrication**
7. **Soldering & Final Assembly**
8. **Car Robot Prototype Implementation**

## 📷 Screenshots

> Include these in your GitHub repo:
- Circuit schematic (Proteus)
- PCB Layout & 3D model
- Final soldered PCB
- Working robot (if available)

## 🚀 Applications

- DIY robotics (e.g., differential drive cars)
- Educational kits on motor control
- Low-cost automation prototypes
- Simple mechatronic systems

## ✅ Future Enhancements

- Microcontroller integration (Arduino, ESP32)
- Speed feedback via encoders
- Wireless (Bluetooth or RF) control
- Motor driver IC replacement (L298N)

## 👨‍💻 Authors

- Ali El-Sayed  
- Ali Mohamed Abdelsalam  
- Omar Mohamed  
- Philopateer Charl  
- Nour Eldeen Nashat  

> Supervised by: Dr. Nabil Abd-Rabou  
> [El-Shorouk Academy – Engineering Faculty]

---

> 🎓 If you liked this project, feel free to ⭐ star it or fork it!

