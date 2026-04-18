# 🚀 WRO 2025 Future Engineers – CyberBots
Welcome to the GitHub repository of Team CyberBots, participating in the World Robot Olympiad™ (WRO®) Future Engineers 2026 category. Our team designed and developed a compact autonomous vehicle inspired by real-world automotive engineering principles, with a design approach that visually reflects concepts similar to real vehicles and Mars rover-style exploration systems.

Our main objective was to build a robot that not only successfully completes the WRO challenge but also incorporates a realistic automotive-inspired design language. The external structure was intentionally designed to resemble a real vehicle in terms of proportions and layout, while maintaining full compliance with WRO constraints. Special attention was given to mechanical reliability, precise steering geometry, stable power architecture, sensor-based navigation, and modular electronic integration.

During development, each subsystem — including drivetrain, steering mechanism, perception system, onboard computing, and power distribution — was iteratively tested and optimized to achieve stable performance on the official 3 × 3 meter WRO competition field.

This repository documents our full engineering workflow, including system architecture, electrical schematics, component selection rationale, software logic structure, testing procedures, and validation results prepared for the WRO 2026 Future Engineers competition.

## 📚Table of Contents
## 📁 Project Structure

- 💾 [Code](./Code/)
- 🔌 [Electronical Components (CAD)](./Electronical%20Components%20(CAD)/)
- 🔌 [Electronical Components (Photos)](./Electronical%20Components%20(Photos)/)
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

