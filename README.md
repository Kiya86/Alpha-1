<h1 align="center">
  <br>
  <a href="#">
    <img width="220" height="220" alt="Alpha 1 Avionics Logo" src="https://github.com/user-attachments/assets/c3a05ca5-c952-491d-af0b-322891801b5a" />
  </a>
  <br>
  Alpha 1 Avionics
  <br>
</h1>

<h4 align="center">
A custom ESP32-S3 based avionics and GPS telemetry board designed for Taft Rocketry high power flights. 
</h4>

<div align="center">

![EasyEDA](https://img.shields.io/badge/EasyEDA-1769FF?style=for-the-badge&logo=easyeda&logoColor=white)
![ESP32-S3](https://img.shields.io/badge/ESP32--S3-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

</div>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#purpose">Purpose</a> •
  <a href="#pcb">PCB</a> •
  <a href="#main-components">Main Components</a> •
  <a href="#team">Team</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

## Key Features

- **ESP32-S3FH4R2** Microcontroller responsible for all logic 
- **SAM-M10Q GNSS** GPS for recovery and altitude 
- **DL-RFM95-915M LoRa module** Long-range 915 MHz telemetry (15km+)
- **BMP390** Altitude and pressure measurements
- **H3LIS331DLTR** Launch and flight-event events/detection
- **AHT20** Temperature logging (Not required to use)
- **W25Q64** Onboard data logging
- **USB-C** Used programming, debugging, and power input (Diodes to prevent voltage issues)
- **XT30 battery input** Used for 2s-3s batter input 
- **LM61495** Steps down battery voltage for ease of use 
- **AP2114 (3.3V)** Used for 3.3V rail
- **Buzzer and LEDs** Recovery, debugging, and feedback

## Purpose

Alpha 1 is designed as a compact avionics and telemetry board for **Taft Rocketry**, a student-led high-power rocketry team created at William Howard Taft Charter High School.

Taft Rocketry designs, builds, and launches high power rockets while developing custom electronics, recovery systems, and flight computers. Alpha 1 is intended to add GPS tracking, telemetry, sensor logging, and future flight computer development for the team’s rocket projects (2 year support).

## PCB

Designed in **EasyEDA** and **KiCad** with ideal sensor placement, RF layout, power matching and performance. The board is separated into sections for key systems, such as power, telemetry, GPS, and sensors. 

The design uses a 4-layer PCB stackup to improve ground return paths, reduce noise, and support cleaner RF routing.

### Board Top View

<img width="1515" height="743" alt="Alpha 1 PCB Top View" src="https://github.com/user-attachments/assets/3a4739e7-e671-45a3-a877-b64a1aa5b36a" />

### Board Bottom View

<img width="1513" height="743" alt="Alpha 1 PCB Bottom View" src="https://github.com/user-attachments/assets/7aff397e-abfd-4046-901b-121e3f1a70d7" />

### Schematic

<img width="1450" height="1351" alt="Schematic_Alpha 1_2026-05-13" src="https://github.com/user-attachments/assets/07074cb2-50fe-4e45-b5c9-9893b1079d48" />

## Main Components

| Category | Component |
|---|---|
| Microcontroller | ESP32-S3FH4R2 |
| GPS / GNSS | SAM-M10Q-00B |
| Telemetry | DL-RFM95-915M LoRa Module |
| Barometer | BMP390 |
| High-G Accelerometer | H3LIS331DLTR |
| Temperature / Humidity | AHT20 |
| Flash Storage | W25Q64JVSSIQ |
| Main Regulator | LM61495Q5RPHRQ1 |
| 3.3V Regulator | AP2114H-3.3TRG1 |
| RF Connector | SMA Connector |
| Power Input | XT30 Connector |
| USB | USB-C Connector |

## Team

This project was created for **Taft Rocketry**, a student rocketry team focused on designing, building, and launching high-power rockets.

The team works on:

- Custom avionics
- GPS and radio telemetry
- Rocket recovery systems
- High-power rocket structures
- Flight testing and data logging

## Credits

This project uses:

- [EasyEDA](https://easyeda.com/) for schematic and PCB design
- [JLCPCB](https://jlcpcb.com/) for PCB fabrication and assembly

## License

GNU Affero General Public License v3.0
