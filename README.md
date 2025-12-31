# S500 Autonomous Drone Project

![Build Status](https://img.shields.io/badge/Build_Status-Complete-success?style=for-the-badge) ![Platform](https://img.shields.io/badge/Platform-S500-blue?style=for-the-badge&logo=drone)

## 🚁 Project Overview

This repository documents the build and configuration of a custom **S500 Autonomous Drone**. Built on the robust PCB-integrated S500 airframe, this quadcopter is designed for stability and payload versatility. It features a dual-stack flight intelligence system capability (Radiolink CrossFlight / Pixhawk 2.4.8) and a high-fidelity video link system.

The primary goal of this project is to establish a reliable aerial platform for autonomous waypoint navigation and aerial imaging.

## 📸 Build Gallery

<div align="center">
  <img src="images/fullyassembleddrone.jpg" width="800" alt="Fully Assembled S500 Drone" />
  <p><em>Fig 1. The fully assembled S500 Quadcopter ready for flight.</em></p>
</div>

| | |
|:---:|:---:|
| <img src="images/droneflyinggrid3.jpg" width="400" alt="Flight Test"> | <img src="images/dronemotorprpellorcinematic.jpg" width="400" alt="Propulsion System"> |
| <img src="images/droneremotecameramovilelivefeed.jpg" width="400" alt="Ground Control"> | <img src="images/frameremoteconnector.jpg" width="400" alt="Frame Assembly"> |

---

## 🛠️ Technical Specifications

### Airframe & Propulsion
*   **Frame**: S500 SK500 Quadcopter (PCB Version) for clean power distribution.
*   **Motors**: 2212 920KV Brushless DC Motors (CW/CCW).
*   **ESCs**: BLHeli_S LITTLEBEE 30A-S OPTO (2-6S LiPo support).
*   **Propellers**: 9450 Self-Locking props for efficiency and safety.

### Flight Intelligence
*   **Primary Controller**: Radiolink CrossFlight / Pixhawk 2.4.8 (32-Bit).
*   **GPS**: Radiolink TS100 Mini GPS / Standard M8N GPS.
*   **Mounting**: Anti-vibration shock absorber plates for IMU stability.

### Power System
*   **Battery**: Orange 4S 4500mAh 35C / 3S 2200mAh 30C LiPo.
*   **Charging**: IMAX B6 AC Professional Balance Charger.
*   **Distribution**: Integrated PCB frame + APM Power Module (XT60).

---

## 📋 Bill of Materials (BOM)

### A. Core Airframe & Propulsion
| Sl. No | Component Name | Qty | Price/Item (₹) | Total (₹) |
| :--- | :--- | :---: | :---: | :---: |
| 1 | S500 SK500 Quadcopter Frame Board PCB Version | 1 | 2,349.00 | 2,349.00 |
| 2 | 2212 920KV Brushless DC Motor for DJI Silver Cap (CCW) | 2 | 685.00 | 1,370.00 |
| 3 | 2212 920KV Brushless DC Motor for DJI Black Cap (CW) | 2 | 639.00 | 1,278.00 |
| 4 | BLHeli_S LITTLEBEE 30A-S OPTO 2-6S LIPO ESC | 4 | 999.00 | 3,996.00 |
| 5 | 9450 Self Locking Propeller For Drone 1CW+1CCW (Original) | 4 | 449.00 | 1,796.00 |

### B. Flight Intelligence & Navigation
| Sl. No | Component Name | Qty | Price/Item (₹) | Total (₹) |
| :--- | :--- | :---: | :---: | :---: |
| 6 | Radiolink CrossFlight Flight Controller | 1 | 5,403.00 | 5,403.00 |
| 7 | Radiolink TS100 Mini GPS | 1 | 3,554.00 | 3,554.00 |
| 8 | Pixhawk 2.4.8 Drone Flight Controller PX4 32 Bit | 1 | 6,299.00 | 6,299.00 |
| 9 | GPS folding metal stand for APM and Pixhawk | 2 | 299.00 | 598.00 |
| 10 | CC3D/APM/Pixhawk Shock Absorber Anti-vibration Plate | 3 | 224.00 | 672.00 |

### C. Remote Control & Video Link
| Sl. No | Component Name | Qty | Price/Item (₹) | Total (₹) |
| :--- | :--- | :---: | :---: | :---: |
| 11 | SKYDROID T10 2.4Ghz 10CH Remote with T10 Receiver | 1 | 12,099.00 | 12,099.00 |
| 12 | SKYDROID TWO AXIS GIMBAL CAMERA for T10/H12 | 1 | 9,999.00 | 9,999.00 |
| 13 | Flysky FS-i6X 2.4GHz 6CH Transmitter with iA10B | 1 | 5,299.00 | 5,299.00 |

### D. Power Management & Charging
| Sl. No | Component Name | Qty | Price/Item (₹) | Total (₹) |
| :--- | :--- | :---: | :---: | :---: |
| 14 | Orange 14.8V 4500mAh 4S 35C Lithium Polymer Battery | 1 | 5,799.00 | 5,799.00 |
| 15 | Orange 11.1V 2200mAh 3S 30C Lipo Battery | 1 | 1,849.00 | 1,849.00 |
| 16 | IMAX B6 AC Lipo Battery Professional Balance Charger | 1 | 2,649.00 | 2,649.00 |
| 17 | Pixhawk APM Power Module with XT60 Connectors | 3 | 629.00 | 1,887.00 |
| 18 | 2s-8s Lipo Battery Voltage Tester / Low Voltage Buzzer | 3 | 129.00 | 387.00 |

### E. Wiring, Connectors & Hardware
| Sl. No | Component Name | Qty | Price/Item (₹) | Total (₹) |
| :--- | :--- | :---: | :---: | :---: |
| 19 | XT60 Male To T Plug Female Adapter | 4 | 199.00 | 796.00 |
| 20 | High Quality 20AWG Silicone Wire 1m - Black | 5 | 49.00 | 245.00 |
| 21 | Heat Shrink Sleeve 3mm Black 1meter | 2 | 13.00 | 26.00 |
| 22 | SafeConnect Twisted 60CM 22AWG Servo Extension | 10 | 69.00 | 690.00 |
| 23 | 5 Pin JST XH 2.54mm Pitch Plug with cable | 10 | 19.00 | 190.00 |
| 24 | M2.5 X 8MM Socket Head Cap Allen Bolt and Nut | 2 | 189.00 | 378.00 |
| 25 | Self Locking Nylon Cable Ties (Black) 100pcs | 3 | 79.00 | 237.00 |

---
**Total Project Cost estimation**: ₹ 68,569.00
