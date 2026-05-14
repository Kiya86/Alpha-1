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
A custom ESP32-S3 rocket avionics and GPS telemetry board designed for Taft Rocketry high-power rocket flights.
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

- **ESP32-S3FH4R2** microcontroller with built-in Wi-Fi and Bluetooth support
- **SAM-M10Q GNSS module** for GPS-based rocket tracking and recovery support
- **DL-RFM95-915M LoRa module** for long-range 915 MHz telemetry
- **BMP390 barometer** for altitude and pressure measurements
- **H3LIS331DLTR high-g accelerometer** for launch and flight-event detection
- **AHT20 temperature and humidity sensor** for environmental monitoring
- **W25Q64 external flash memory** for onboard data storage
- **USB-C connectivity** for programming, debugging, and power input
- **XT30 battery input** for reliable rocket power connection
- **LM61495 buck converter** for efficient main power regulation
- **AP2114 3.3V LDO** for clean low-voltage power
- **Buzzer and status LEDs** for recovery, debugging, and system feedback
- **SMA antenna connector** for external RF antenna support
- **2.4 GHz ceramic antenna** for ESP32 wireless communication
- **4-layer PCB design** focused on RF performance, power integrity, and compact avionics integration

## Purpose

Alpha 1 is designed as a compact rocket avionics and telemetry board for **Taft Rocketry**, a student-led high-power rocketry team created at Taft High School.

Taft Rocketry designs, builds, and launches high-power rockets while developing custom electronics, telemetry systems, recovery systems, and flight computers. Alpha 1 is intended to support GPS tracking, wireless telemetry, sensor logging, and future flight computer development for the team’s rocket projects.

The board combines GPS, LoRa, environmental sensors, high-g motion sensing, onboard memory, USB-C, and robust power regulation into one integrated avionics platform.

## PCB

Designed in **EasyEDA** with attention to RF layout, power management, GPS performance, and sensor placement. The board is built around a compact avionics layout with separate sections for power regulation, processing, telemetry, GPS, and sensors.

The design uses a 4-layer PCB stackup to improve ground return paths, reduce noise, and support cleaner RF routing.

### Board Top View

<img width="1515" height="743" alt="Alpha 1 PCB Top View" src="https://github.com/user-attachments/assets/3a4739e7-e671-45a3-a877-b64a1aa5b36a" />

### Board Bottom View

<img width="1513" height="743" alt="Alpha 1 PCB Bottom View" src="https://github.com/user-attachments/assets/7aff397e-abfd-4046-901b-121e3f1a70d7" />

### Schematic

<img src="assets/schematic.png" alt="Alpha 1 Schematic" width="800"/>

### PCB Layers

The 4-layer stackup provides better signal integrity, cleaner power distribution, and improved RF performance for the GPS and LoRa systems.

**Layer 1: Top Signal / Components**

<img src="assets/layer_1.png" alt="PCB Layer 1" width="800"/>

**Layer 2: Ground Plane**

<img src="assets/layer_2.png" alt="PCB Layer 2" width="800"/>

**Layer 3: Power Plane / Routing**

<img src="assets/layer_3.png" alt="PCB Layer 3" width="800"/>

**Layer 4: Bottom Signal**

<img src="assets/layer_4.png" alt="PCB Layer 4" width="800"/>

### JLCPCB Order

<img src="assets/jlcpcb.png" alt="JLCPCB Order" width="800"/>

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
- Student-led aerospace engineering projects

## Credits

This project uses:

- [EasyEDA](https://easyeda.com/) for schematic and PCB design
- [JLCPCB](https://jlcpcb.com/) for PCB fabrication and assembly
- [Espressif ESP32-S3](https://www.espressif.com/) for the main microcontroller platform
- Taft Rocketry for project development, testing, and integration

## You may also like...

- Taft Rocketry custom avionics projects
- Taft Rocketry high-power rocket builds
- Alpha-series flight computer development
- GPS and LoRa telemetry systems for student rocketry

## License

MIT

---

> Taft Rocketry &nbsp;&middot;&nbsp;
> Alpha 1 Avionics &nbsp;&middot;&nbsp;
> Designed for high-power rocket telemetry, tracking, and flight data logging
