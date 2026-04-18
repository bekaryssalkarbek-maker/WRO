# 🚀 WRO 2025 Future Engineers – CyberBots
Welcome to the GitHub repository of Team CyberBots, participating in the World Robot Olympiad™ (WRO®) Future Engineers 2026 category. Our team designed and developed a compact autonomous vehicle inspired by real-world automotive engineering principles, with a design approach that visually reflects concepts similar to real vehicles and Mars rover-style exploration systems.

Our main objective was to build a robot that not only successfully completes the WRO challenge but also incorporates a realistic automotive-inspired design language. The external structure was intentionally designed to resemble a real vehicle in terms of proportions and layout, while maintaining full compliance with WRO constraints. Special attention was given to mechanical reliability, precise steering geometry, stable power architecture, sensor-based navigation, and modular electronic integration.

During development, each subsystem — including drivetrain, steering mechanism, perception system, onboard computing, and power distribution — was iteratively tested and optimized to achieve stable performance on the official 3 × 3 meter WRO competition field.

This repository documents our full engineering workflow, including system architecture, electrical schematics, component selection rationale, software logic structure, testing procedures, and validation results prepared for the WRO 2026 Future Engineers competition.

## 📚Table of Contents
## 📁 Project Structure

- 💾 [Code](./Code/)
- 🔌 [Electronical Components (CAD)](./Electronical%20Components%20(CAD)/)
- 🔌 [Electronical Components(photos)](./Electronical%20Components%20(Photos)/)
- 📚 [Engineer Journal](./Engineer%20Journal/)
- ⚙ [Non-Electronical Components](./Non-Electronical%20Components/)
- 🔌 [Schemes](./Schemes/)
- 👥 [Team](./Team/)
- 🚗 [Vehicle Photos](./Vehicle%20Photos/)
- 📁 [SRC](./SRC/)
- 
## 📂Complete Documentation Structure
### Each folder contains comprehensive README documentation with specialized technical content
| 📁 Folder | 🎯 Technical Content | 📖 Detailed Documentation |
|----------|--------------------|---------------------------|
|  💾 Code | Software System |
|  | • Autonomous navigation algorithms |
| | • Camera color detection logic |
| | • LiDAR-based distance processing |
| | • Motor and steering control systems |
|  |
| 🔌 Electronical Components (CAD) | Electrical Design Models |
| | • CAD models of electronic layout |
| | • Component placement and integration |
| | 🔗 Explore Electrical CAD Documentation |
| 🔌 Electronical Components (Photos) | Electronics Implementation |
| | • Real photos of all electronic components |
| | • Individual component descriptions |
| | • Engineering problems and solutions |
| | 🔗 Explore Electronics Photos Documentation |
| 📚 Engineer Journal | Engineering Development Process |
| | • Design iterations and improvements |
| | • Problem solving and optimization |
| | • System-level engineering decisions |
| | 🔗 Explore Engineering Journal |
| ⚙ Non-Electronical Components | Mechanical Design |
| | • Full robot CAD model |
| | • Differential system design |
| | • Steering mechanism design |
| | • Chassis and structural architecture |
| | • 3D printing process and assembly stages |
| | • Design challenges and solutions |
| | • Individual CAD explanations for parts |
| | 🔗 Explore Mechanical Design Documentation |
| 🔌 Schemes | Electrical System Documentation |
| | • Electronics overview (photos + specs + quantity) |
| | • Full wiring schematic and system logic |
| | • Power distribution and current flow strategy |
| | • Assembly process of electrical system |
| | • Engineering problems and solutions |
| | 🔗 Explore Schemes Documentation |
| 👥 Team | Team Information |
| | • Team members and roles |
| | • Coach/mentor information |
| | • Task distribution (mechanical, electronics, software, testing) |
| | 🔗 Explore Team Documentation |
| 🚗 Vehicle Photos | Robot Documentation |
| | • CAD renders of robot |
| | • Real robot photos |
| | • Multi-angle system overview |
| | 🔗 Explore Vehicle Photos Documentation |
| 📁 SRC | Testing & Resources |
| | • Autonomous navigation tests |
| | • Steering and drivetrain performance tests |
| | • Sensor calibration and validation |
| | • Competition condition testing |
| | • Debugging and additional resources |
| | 🔗 Explore SRC Documentation |

## 👥The Team
Team CyberBots includes passionate students working under the guidance of a coach. This is our first time competing in the WRO Future Engineers category (2026), where each member contributes unique skills to the project, including mechanical design, electronics, programming, and computer vision development.









## 🎯Challenge Overview
### **Two distinct autonomous navigation challenges testing vehicle intelligence and precision**

</div>

### **🚀 Open Challenge**
<div align="center">

**Objective**: Complete three autonomous laps on dynamically configured tracks

| Aspect | Challenge | Our Solution |
|--------|-----------|--------------|
| **Track Variability** | Random internal wall placements | Adaptive path planning algorithms |
| **Navigation** | Unknown track layouts each round | Robust wall-following with corner detection |
| **Performance** | Consistent lap times across variations | Optimized PID control and sensor fusion |
| **Precision** | Maintain course in narrow lanes | High-accuracy steering and speed control |

</div>

### **🚧 Obstacle Challenge**
<div align="center">

**Objective**: Navigate three laps with traffic sign compliance and precision parking

| Challenge Element | Requirement | Our Implementation |
|-------------------|-------------|-------------------|
| **Traffic Signs** | Red → Right bias<br>Green → Left bias | Real-time color detection with LAB colorspace |
| **Obstacle Avoidance** | Dynamic path adjustment | Smooth following at consistent distances |
| **Parking Maneuver** | Parallel parking after lap completion | Multi-stage parking with sensor validation |
| **Navigation** | Shortest path optimization | Efficient routing around obstacle combinations |
</div>

## 📊 **WRO 2025 Engineering Documentation Scoring (30 points total)**

| Scoring Area | Maximum Points | Our Documentation Coverage |
|--------------|----------------|---------------------------|
| **1. Mobility Management** | 4 points | Complete mechanical design, motor selection, steering system, assembly instructions |
| **2. Power & Sense Management** | 4 points | Power systems, sensor integration, wiring diagrams, component specifications |
| **3. Obstacle Management** | 4 points | Navigation algorithms, parking strategies, source code with detailed comments |
| **4. Pictures – Team and Vehicle** | 4 points | Multi-angle vehicle photos, team photos, component labeling |
| **5. Performance Videos** | 4 points | Complete challenge demonstrations with commentary and analysis |
| **6. GitHub Utilization** | 4 points | Version control, structured documentation, regular commits |
| **7. Engineering Factor** | 4 points | Custom design and manufacturing throughout the vehicle |
| **8. Overall Judge Impression** | 2 points | Clear communication enabling easy replication |
| **Total Documentation Score** | **30 points** | **(≈25% of total competition score)** |
</div>

## 🤖Our Robot
### **Vehicle Photos**
The following folder contain the final assembled robot from different perspectives. They demonstrate the chassis structure, steering mechanism, drivetrain layout, bumper design, LED headlights, and placement of key electronic components such as the Raspberry Pi and LiDAR sensor.

### **Photos**
#### **Front photo**
**Focus:** Lidar, Camera, Stearing system, LED headlights
- Lidar: Xiaomi Lidar Sensor (Used for distance measurement and obstacle detection to support accurate navigation and safe robot movement during competition runs.)
- Camera: USB 8MP 4K 60fps Camera(Used for color detection and environment recognition to support navigation decisions during robot movement, while distance measurement is handled by the LiDAR sensor.)
- Stearing system: Mechanism responsible for controlling the direction of the robot’s front wheels, enabling precise turning and stable navigation during movement.
- LED headlights: Used primarily for aesthetic purposes, improving the robot’s visual appearance without affecting its functional performance during operation

<img width="1280" height="720" alt="Front photo" src="https://github.com/user-attachments/assets/5ba6866e-0446-47a9-ae07-8e477fa54baa" />

#### Core Processing Architecture
- Primary Computing Unit:Raspberry Pi 5 (1GB) single-board computer with Quad-core 2.4 GHz Cortex-A76 CPU, VideoCore VII GPU, Wi-Fi 802.11ac, Bluetooth 5.0, and 40-pin GPIO interface. Responsible for vision processing, LiDAR data handling, navigation logic, and overall system coordination.
- PWM Control Expansion:PCA9685 16-Channel PWM Driver (I2C) with 12-bit resolution (4096 steps) and adjustable PWM frequency (24–1526 Hz), used for stable actuator signal generation and precise control of steering systems.
- Distributed Control Strategy:Separation between high-level navigation processing on Raspberry Pi 5 and low-level motor actuation through DRV8833 dual H-bridge motor driver ensures reliable real-time control performance.

#### Perception System
- Front Visual Navigation:USB 8MP Camera with IMX415 sensor supporting 4K resolution and wide-angle field of view, used for track detection, color recognition, and environmental interpretation.
- Environmental Mapping:RPLIDAR 360° laser scanner with approximately 10–12 meters measurement range, enabling obstacle detection and spatial awareness during autonomous navigation.
- Sensor Fusion Logic:Combined processing of camera-based visual perception and LiDAR distance measurements improves navigation reliability under varying competition conditions.

#### Propulsion and Control
- Drive System:TT DC Gear Motor (3–6 V, gear ratio 1:48) with 130–290 RPM no-load speed and 160–240 mA no-load current provides stable drivetrain motion.
- Steering Mechanism:MG996R V17 Digital Servo Motor with metal gears, operating voltage 4.8–7.2 V, speed 0.17 s/60°, and approximately 180° rotation range enables precise steering control.
- Motor Control Interface:DRV8833 Dual H-Bridge Motor Driver supporting 2.7–10.8 V operating voltage and up to 1.5 A per channel output current with PWM speed control capability.
- Power Management Architecture:Custom 2S LiPo Battery (7.4 V, 3000 mAh) combined with HW-411 LM2596 DC-DC Buck Converter (input 4–40 V, output 1.25–35 V adjustable, up to 3 A) ensures stable voltage regulation across all subsystems.
- Electrical Safety Control:SS12D10 SPDT Slide Switch (90°) used as the primary system power isolation switch for safe startup and shutdown operations.

### Potential Future Improvements (Overall Vehicle)

- Improve vehicle speed by integrating a more powerful drivetrain motor with higher torque and better acceleration characteristics while maintaining the current robot dimensions. This upgrade will increase responsiveness and allow faster navigation on the competition track.
- Enhance drivetrain efficiency by optimizing gear ratio selection and reducing mechanical friction within the transmission system. These improvements will support smoother motion and more stable high-speed performance.
- Further improve power distribution stability to support higher peak acceleration without voltage drops by refining voltage regulation stages and optimizing current flow between computing, sensing, and actuation subsystems.

## 🔧 Electronic Systems
| Components | Image  | Description   |    Quantity | 
|------------|-------|-------------|-------------|
|      Battery 7.4V      |  ![Battary 7 4 v](https://github.com/user-attachments/assets/a3a33397-1ca3-4cc4-b1ab-a9e5a3964dbe) |     Lithium polymer battery pack / custom 2S LiPo battery – 7.4V, 3000mAh, Charge 0.5C, Discharge 1C, Size 13×42.5×98 mm, Weight ~108 g. | 1  | 
|       yellow toymotor dims     |  ![yellow_toymotor_dims](https://github.com/user-attachments/assets/41cab360-41f7-4b28-86ab-22f1f83db447) |Yellow DC 3V–6V Gear Motor TT for Intelligent Car / Robot Wheels – Voltage 3–6V, No-load current 160–240 mA, No-load speed 130–290 rpm, Gear ratio 1:48, Single axis. |  1  | 
|       mg996r v17     |    ![mg996r v17](https://github.com/user-attachments/assets/93aa6d62-c5ba-42ee-b0fb-3a9695d8cc29) |      MG996R V17 Servo Motor – High torque, Digital, Rotation ~180°, Operating voltage 4.8–7.2 V, Speed 0.17 s/60° (6 V), Metal gears, Standard size. | 1 | 
|      HW-411      |   ![HW-411](https://github.com/user-attachments/assets/de25cf16-1348-4981-8cdb-a0039846c536) |      HW‑411 DC‑DC Buck Converter Module – Adjustable step‑down voltage regulator (LM2596S), Input 4–40 V, Output 1.25–35 V (adjustable), Max current ≈3 A, High efficiency (~92%), Overheat and short‑circuit protectio      | 2 | 
|      USB 8MP 4K 60fps Camera      |    ![Cam V2 1 v1](https://github.com/user-attachments/assets/6ecaaff7-5ee0-459c-8b8a-232d9993058d) |      USB 8MP 4K 60fps Camera with IMX415 Sensor and Microphone, Day & Night Wide-Angle Surveillance HD CCTV System      |  1  | 
|       DRV8833     |    ![DRV8833](https://github.com/user-attachments/assets/f2e9be73-154f-4143-b417-316e2a65708c)  |       DRV8833 Dual DC Motor Driver Module – Dual H-bridge motor driver, operating voltage 2.7–10.8 V, controls 2 DC motors, output current 1.5 A per channel, supports PWM control, built-in protection circuits.     |  1  | 
|       PCA9685 v18     |     ![PCA9685 v18](https://github.com/user-attachments/assets/76a841d0-7075-4609-adf3-c341e1f91f2f)  |       PCA9685 16-Channel PWM Servo Driver Module (I2C) – Controls up to 16 servos, 12-bit PWM resolution (4096 steps), communication via I2C (SDA/SCL), logic voltage 3.3 V / 5 V compatible, adjustable PWM frequency ≈24–1526 Hz, supports chaining up to 62 modules.     |  1 | 
|     RASPBERRY_PI5_1       |   ![RASPBERRY_PI5_1](https://github.com/user-attachments/assets/06984689-b434-4728-9a16-8c8e57939f1b)  |       Raspberry Pi 5 (1GB) – Quad-core 2.4 GHz Cortex-A76 CPU, 1 GB LPDDR4X RAM, VideoCore VII GPU, Wi-Fi (802.11ac) + Bluetooth 5.0, Gigabit Ethernet, 2× USB 3.0 + 2× USB 2.0, dual 4K HDMI output, PCIe 2.0, 40-pin GPIO, power 5 V / 5 A via USB-C.     |  1  |
|        RPLIDAR    |   ![RPLIDAR](https://github.com/user-attachments/assets/1cf18d49-74b6-41e7-a085-5e194217d2f8)  |      Xiaomi LiDAR Sensor (e.g., TOF / 360°)* – Long‑range distance measurement up to ~10–12 m, 360° scanning, high‑precision time‑of‑flight (ToF) / laser ranging, fast sampling, low‑power, interface UART / I2C / SPI (зависит от модели), used for SLAM and robot navigation.    |  1  | 
|      SS12D10_90_Degree     |    ![SS12D10_90_Degree](https://github.com/user-attachments/assets/45f4b953-98b4-4426-b274-ee7f9f6c7a1c) |      SS12D10 90° Slide Switch (DIP) – SPDT slide switch, 90° actuation, DIP package, rated current ≈0.3–1 A, voltage ≈12–24 V DC, used for power/control switching in circuits. |   1  | 

**Component Sourcing Rules:** Direct product links and pricing information are intentionally not included to ensure long-term accessibility and avoid outdated references. All listed components can be easily found online using their names and images, while their authenticity can be confirmed through the datasheets provided in this repository.

### **⚡️Complete Wiring System**
#### **Wiring Schematic & Physical Implementation**
#### **1**
<img width="1280" height="960" alt="full scheme" src="https://github.com/user-attachments/assets/54b185f3-cd24-4e35-bc5f-5de216cd842b" />

#### **2**
<img width="720" height="1280" alt="photo_2026-04-17_12-05-50" src="https://github.com/user-attachments/assets/2ccbdcd4-6c02-4028-869f-cd20d50bd9f9" />
<img width="720" height="1280" alt="photo_2026-04-17_12-05-27" src="https://github.com/user-attachments/assets/7b9c2c86-8762-400e-9b0d-c4907345d5bf" />
<img width="720" height="1280" alt="photo_2026-04-17_12-05-21" src="https://github.com/user-attachments/assets/965a1c76-98c0-44ce-b76c-4cdfd23806cf" />

1) Complete hand-drawn and digitally traced wiring schematic showing full electrical connections
2) Physical implementation demonstrating socket-based construction of the schematic

## Power Management Innovation

During system integration, we identified the necessity of implementing a stable and efficient power distribution architecture capable of supporting both high-current drivetrain components and sensitive computing modules operating simultaneously.

Our robot uses a 7.4V (2S) LiPo battery as the primary energy source. To ensure reliable voltage regulation for onboard electronics, we implemented a dedicated power management structure based on the HW-411 (LM2596) DC-DC buck converter module, providing stable regulated voltage for critical subsystems including the Raspberry Pi 5, sensors, and control electronics.

To improve operational safety and prevent unintended battery discharge during inactive states, an SS12D10 SPDT slide switch was integrated as the primary hardware-level power isolation mechanism controlling system startup and shutdown.

Additionally, we applied a separated power distribution strategy between computational modules and actuator subsystems. This approach reduces electrical noise from motors, prevents voltage drops during peak load conditions, and improves overall stability of perception and navigation performance during autonomous operation.

This structured power architecture significantly increases electrical reliability, protects sensitive components, and ensures consistent system behavior under dynamic competition conditions.

### Engineering Solution:

- **Structural Layout Optimization:** Internal components reorganized using electronics-first placement to avoid interference and improve weight distribution.

- **Mechanical Strength vs Weight Optimization:** Gyroid infill selected after testing multiple patterns to achieve best balance of strength and low weight.

- **Sensor Integration Stability:** Dedicated mounts and cable routing implemented for stable LiDAR and camera operation without mechanical interference.

### Modular Manufacturing Strategy Advantages
Our robot architecture was intentionally designed to support iterative development and serviceability during competition preparation:

- Rapid mechanical adjustments without external fabrication delays
- Independent subsystem upgrades without full system redesign
- Fast component replacement during testing and competition
- Continuous weight distribution optimization
- Improved robustness through direct assembly verification
  
This strategy ensured that the robot remained adaptable throughout the engineering cycle while maintaining competition reliability.

## Development Convenience Features
