# PLC-Controlled Sorting System

## Project Overview
This project is a small industrial-style **PLC-controlled item sorting system**. The system uses pneumatic cylinders, stepper motors, and a Siemens S7-1200 PLC to automatically sort objects based on rules. The design focuses on reliability, expandability, and realistic industrial while remaining suitable for educational purposes ;p.

Key features include:
- Pneumatic actuators for precise pushing of items
- Stepper motor-driven conveyors
- Siemens S7-1200 PLC for advanced control and future expansion
- Modular design with 2020 aluminum profiles
- Full BOM based on real, commercially available components


---

## Bill of Materials (BOM)

| Component | Quantity | Price (PLN) |
|-----------|---------|------------|
| PU 8/5 mm pneumatic hose | 1 | 3.30 |
| FRL unit (filter, dryer, oiler, regulator) 1/4" | 1 | 85.92 |
| AirTAC 5/2 monostable pneumatic valve 4M310-08AG | 2 | 192.00 |
| Double-acting pneumatic cylinder 32×200 mm | 1 | 80.00 |
| Stepper driver 5.6 A | 1 | 90.00 |
| Stepper motor NEMA23, 2.0 Nm | 1 | 118.00 |
| DIN-rail 24V / 15W power supply (Qoltec) | 2 | 96.04 |
| ONPOW button red NO/NC | 1 | 19.15 |
| ONPOW button green NO/NC | 1 | 19.15 |
| Siemens S7-1200 CPU 1214C | 1 | 1351.77 |
| Aluminum extrusion profiles 2020 (6 meters) | 6 m | 300.00 |
| Grove Ultrasonic Distance Sensor (Seeedstudio) | 1 | 23.34 |
| **Total** |   | 2361.67 |

---

## Project Stages
1. **CAD Modeling** – Designed full 3D assembly of the conveyor and actuator system.
2. **PLC Programming** – Ladder Diagram code implemented in CODESYS for controlling cylinders and motors.
3. **BOM Creation** – Selected all components to ensure reliability and expandability.
4. **Controller Upgrade** – Replaced Siemens LOGO! with Siemens S7-1200 for professional-grade PLC control.
5. **Testing & Verification** – Checked calculations, motor/actuator sizing, and system stability in simulation.
6. **Pneumatic System Setup** – Assembled cylinders, valves, FRL, tubing, and fittings.
7. **Sorting Area Design** – Configured sliding area for sorted items with correct actuator positioning.
8. **Optimizations** – Improved pulley design, code reliability, and 3D structure aesthetics.

---

## 3D Model / Schematic

<img width="454" height="309" alt="image" src="https://github.com/user-attachments/assets/65c4340d-f95f-4a07-9cbf-a26f348135fb" />

---

## LD CODE
<img width="1384" height="510" alt="image" src="https://github.com/user-attachments/assets/af19ded6-742e-494d-9c79-3a1655f41c19" />




