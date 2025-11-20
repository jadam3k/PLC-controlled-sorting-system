### Idk why journal doesnt work its not my fault
### i have all components for plc in my house so i dont have to buy new ones

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
# BOM
| Item | Description | Quantity | Unit Price (PLN) | Total Price (PLN) | Total Price (USD) |
|---|---|---|---|---|---|
| Grove Ultrasonic Distance Sensor | Grove Ultrasonic Distance Sensor | 2 | 47 | 94 | 25.85 |
| 2020 aluminum profiles | 2020 aluminum profiles (6 m) | 1 | 340 | 340 | 93.47 |
| PU pneumatic hose | Polyurethane hose PU 8/5 mm | 1 | 4 | 4 | 1.10 |
| FRL filter | Drain-oil filter regulator FRL 1/4″ | 1 | 86 | 86 | 23.65 |
| Pneumatic solenoid valve NAMUR | NAMUR 5/2 G 1/4 230V AirTAC | 2 | 192 | 384 | 105.72 |
| Pneumatic cylinder | Pneumatic actuator 32×200 mm, double-acting | 1 | 310 | 310 | 85.22 |
| Stepper motor driver | Driver for NEMA 16/17/23/24 up to 5.6 A | 1 | 90 | 90 | 24.74 |
| Stepper motor NEMA23 | NEMA23 2 Nm, 3 A (57HS76-3004A08) | 1 | 118 | 118 | 32.45 |
| DIN rail power supply | 24 V 15 W Qoltec DIN-rail | 1 | 49 | 49 | 13.47 |
| Circuit breaker | Overcurrent breaker HN-C20/1 | 1 | 23 | 23 | 6.32 |
| Control button | ONPOW LAS0-B3Y-11/R red NO/NC | 2 | 20 | 40 | 10.99 |
| **Total** |  |  |  | **1,938 PLN** | **≈ 534 USD** |





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

## PLC SCHEMATIC AND view
<img width="750" height="570" alt="image" src="https://github.com/user-attachments/assets/19ac9053-86d5-409c-a004-81d5426cd71e" />
<img width="674" height="526" alt="image" src="https://github.com/user-attachments/assets/4c4cc033-daf3-4b93-8068-8577ef521d2a" />





