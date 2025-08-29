<!--
SPDX-FileCopyrightText: Copyright (c) 2024 Infineon Technologies AG
SPDX-License-Identifier: MIT
-->

# Software collection for Infineon Robotics Development Platform

<a href="https://www.infineon.com" target="_blank" rel="noreferrer noopener">
<img src="./assets/images/Logo.svg" align="right" alt="Infineon logo">
</a>
<br>
<br>
<br>

## Overview

<p>This is the the landing page for all software repositories for Infineon robotics project. The following is description for each project.</p>

### Infineon Mobile Robot (IMR) software repositories
- <a href="https://www.infineon.com/cms/de/applications/robotics/development-platform/" target="_blank" rel="noreferrer noopener">Demo boards reference</a>

#### IMR PSOC™ 6 Battery Management

- <a href="https://github.com/Infineon/IMR_PSoC6_BMS" target="_blank" rel="noreferrer noopener">Github Link</a>
- Battery Management software based on dual-core 32-bit PSOC™ 6 microcontroller
- 12-cell in series battery management system
- 30 V – 50.4 V voltage range
- Support for 1 Mbps CAN and 5 Mbps CAN-FD
- SoC and SoH estimation, balancing and pre-charge algorithm
- Hot-plug support, real-time data recording, and extensive diagnostic system

#### IMR Single-Motor Control

- <a href="https://github.com/Infineon/IMR_IMD701_MC" target="_blank" rel="noreferrer noopener">Github Link</a>
- Motor control solution based on integrated motor drive IC i.e. MOTIX™ IMD701A (microcontroller + 3-phase gate driver)
- Motor control software based on 32-bit XMC™ 1404 microcontroller
- Field Oriented Control (FOC) algorithm with position sensing feedback using magnetic angle sensor TLI5012B E1000
- Operating voltage up to 50 V and power output up to 280 W
- Support for 1 Mbps CAN

#### IMR XMC4700 Robot Control

- <a href="https://github.com/Infineon/IMR_XMC4700_RC" target="_blank" rel="noreferrer noopener">Github Link</a>
- Robot control software based on 32-bit XMC™ 4700 microcontroller
- Support for SBUS protocol for FrSky remote control
- Support for 1 Mbps CAN

#### IMR XMC1404 LED Control

- <a href="https://github.com/Infineon/IMR_XMC1404_LED" target="_blank" rel="noreferrer noopener">Github Link</a>
- RGB-LED control software based on 32-bit XMC™ 1404 microcontroller
- Support for dynamic LED modes e.g. pulsing and chasing with various colors
- Support for 1 Mbps CAN
<!--
#### IMR Navigation

- <a href="https://github.com/Infineon/IMR_nVIDIA_JONX_Navigation" target="_blank" rel="noreferrer noopener">Github Link</a>
- Autonomous navigation implemented in nVIDIA Jetson Orin NX 8 GB development kit with 2x hybrid-ToF cameras (by Infineon, pmdtechnologies, and Ofilm) and Wi-Fi 6E module based on CYW55573
- SLAM and obstacle avoidance capabilities accompanied with LED effects
- ROS framework with Google Cartographer and DWA path planner
- Support for 1 Mbps CAN

#### IMR Navigation GUI

- <a href="https://github.com/Infineon/IMR_Navigation_GUI" target="_blank" rel="noreferrer noopener">Github Link</a>
- Graphic User Interface to complete the IMR autonomous navigation experience
- Ubuntu 22.04 host laptop with connection to a router and nVIDIA Jetson Orin NX in IMR
- User input / command for navigation target and LED modes and colors

### GaN Matchbox

- <a href="https://github.com/Infineon/REF_MTR_48V30A_GaN" target="_blank" rel="noreferrer noopener">Github Link</a>
- Motor control software based on 32-bit XMC™ 4200 microcontroller with high resolution PWM
- (Position) Sensorless Field Oriented Control (FOC) algorithm aided with magnetic current sensor TLI4971
- 3-phase GaN HEMT inverter for high pole-pair number of PMSM motor
- High switching frequency and top-side cooling -->

<br><br>
### Compact Single-Motor Control

- <a href="https://github.com/Infineon/REF_36V_220W_SLFOC" target="_blank" rel="noreferrer noopener">Github Link</a>
- Motor control solution based on integrated motor drive IC i.e. MOTIX™ IMD701A (microcontroller + 3-phase gate driver) in a compact PCB design
- Motor control software based on 32-bit XMC™ 1404 microcontroller
- (Position) Sensorless Field Oriented Control (FOC) algorithm 
- Speed control and position control schemes
- Equation-based stall detection
- Operating voltage up to 40 V and power output up to 220 W in a PCB of 40 mm diameter with inner hole of 9 mm diameter

### PSOC™ Control C3 Dual-Motor Control

- <a href="https://github.com/Infineon/IMR_REF_48V_2x1KW_ASFOC" target="_blank" rel="noreferrer noopener">Github Link</a>
- Single microcontroller controlling 2 motors independently
- Dual-motor control software based on 32-bit PSOC™ Control C3 microcontroller
- Angle-sensor-based Field Oriented Control (FOC) algorithm in Rotor Frame Orientation (RFO) method
- Operating voltage up to 60 V and power output up to 1 kW per motor (total 2 kW) in 100 x 80 x 20 mm envelope size
- Separate power stage board and microcontroller card enabling flexible design for different power level and/or inverter type
- CAN communication with other subsystems in an application

<!---
### Contact
In case of questions regarding this repository and its contents, refer to [MAINTAINERS.md](MAINTAINERS.md) for the contact details of this project's maintainers.

### Licensing

Please see our [LICENSE](LICENSE) for copyright and license information.

## Intended use cases

<p>These examples can be used as a starting point for your project. They are meant to be used with DAVE 4.5.0</p>
-->
