# **Schemes Documentation**
The following schematic presents the electrical connection layout of the robot, showing how the Raspberry Pi, LiDAR sensor, camera, steering servo, drivetrain motor, and power system are integrated. This diagram helps visualize signal routing, power distribution, and overall system interaction for reliable robot performance.

## **🎯Electrical Design Goal**
The purpose of this schematic is to clearly illustrate the electrical connections between the main components of the robot, including the Raspberry Pi, LiDAR sensor, camera, steering servo, drivetrain motor, and power system, ensuring correct integration, troubleshooting support, and reliable system operation.

## **📋Complete Bill of Materials(Electronical)/BOM**
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

## **⚡️Complete Wiring System**
### **Wiring Schematic & Physical Implementation**
### **1**
<img width="1280" height="960" alt="full scheme" src="https://github.com/user-attachments/assets/54b185f3-cd24-4e35-bc5f-5de216cd842b" />

### **2**
<img width="720" height="1280" alt="photo_2026-04-17_12-05-50" src="https://github.com/user-attachments/assets/2ccbdcd4-6c02-4028-869f-cd20d50bd9f9" />
<img width="720" height="1280" alt="photo_2026-04-17_12-05-27" src="https://github.com/user-attachments/assets/7b9c2c86-8762-400e-9b0d-c4907345d5bf" />
<img width="720" height="1280" alt="photo_2026-04-17_12-05-21" src="https://github.com/user-attachments/assets/965a1c76-98c0-44ce-b76c-4cdfd23806cf" />

1) Complete hand-drawn and digitally traced wiring schematic showing full electrical connections
2) Physical implementation demonstrating socket-based construction of the schematic

### **Engineering Documentation Excellence**

- **Professional Schematic:** All electrical connections between the Raspberry Pi, LiDAR sensor, camera, steering servo, drivetrain motor, and power system are clearly documented for accurate system integration

- **Modular Architecture:** Key electronic components are mounted using dedicated holders and accessible ports to simplify maintenance, testing, and component replacement

- **Cable Management:** Organized wiring layout ensures stable power delivery, reduces cable stress, and improves overall system reliability during robot operation

## **⚡Power Management System**
| Line | Source | Consumers | Voltage | Avg Current | Peak Current |
|------|--------|-----------|---------|-------------|--------------|
| A (Logic) | DC-DC Converter #1 | Raspberry Pi 4 | 5V | 0.6–1.2A | up to 2A |
| A (Logic) | DC-DC Converter #1 | RPLIDAR | 5V | 0.5–1A | ~1A |
| A (Logic) | DC-DC Converter #1 | PCA9685 (logic) | 3.3–5V | ~20mA | ~20mA |
| B (Servo) | DC-DC Converter #2 | MG996R (1 servo) | 5–6V | 0.1–0.5A | up to 2.5A |
| C (Motors) | Battery 7.4V Li-Po | DRV8833 + DC motors | 7.4V | 1–2A | 4–6A |
| Common Bus | Battery | Shared system ground (GND) | 0V | — | — |

**Power Management Innovation**

During system integration, we identified the necessity of implementing a stable and efficient power distribution architecture capable of supporting both high-current drivetrain components and sensitive computing modules operating simultaneously.

Our robot uses a 7.4V (2S) LiPo battery as the primary energy source. To ensure reliable voltage regulation for onboard electronics, we implemented a dedicated power management structure based on the HW-411 (LM2596) DC-DC buck converter module, providing stable regulated voltage for critical subsystems including the Raspberry Pi 5, sensors, and control electronics.

Additionally, we applied a separated power distribution strategy between computational modules and actuator subsystems. This approach reduces electrical noise from motors, prevents voltage drops during peak load conditions, and improves overall stability of perception and navigation performance during autonomous operation.

## **🎯Strategic Engineering Choice Analysis:**
### Strategic Manufacturing Approach Analysis

Our robot was developed using a hybrid in-house manufacturing strategy that prioritizes rapid iteration, modularity, reliability, and competition readiness. Instead of relying on fully outsourced fabrication, we implemented a flexible engineering workflow allowing continuous improvement throughout testing cycles.

| Aspect | Fully Outsourced Fabrication | Hybrid In-House Manufacturing (Our Approach) | Engineering Rationale |
|--------|-----------------------------|----------------------------------------------|----------------------|
| Development Speed | Long fabrication turnaround | Immediate mechanical adjustments | Enables fast iteration during testing |
| Cost Efficiency | High per revision cost | Low-cost prototyping workflow | Sustainable for student engineering projects |
| Structural Adaptability | Fixed geometry after production | Adjustable structural configuration | Supports rapid competition-driven redesign |
| Integration Flexibility | Difficult subsystem replacement | Modular subsystem architecture | Allows efficient upgrades and tuning |
| Reliability Control | Dependent on external manufacturing | Fully controlled internal assembly | Ensures predictable system behavior |
| Engineering Understanding | Limited exposure to fabrication details | Full system-level ownership | Strengthens applied robotics engineering skills |

---

### Modular Manufacturing Strategy Advantages

Our robot architecture was intentionally designed to support iterative development and serviceability during competition preparation:

- Rapid mechanical adjustments without external fabrication delays
- Independent subsystem upgrades without full system redesign
- Fast component replacement during testing and competition
- Continuous weight distribution optimization
- Improved robustness through direct assembly verification

This strategy ensured that the robot remained adaptable throughout the engineering cycle while maintaining competition reliability.

---

### Integrated Mechanical–Electrical Production Strategy

The robot structure combines mechanical accessibility with electrical reliability through a modular subsystem layout.

| Design Feature | Implementation Benefit |
|---------------|-----------------------|
| Modular chassis structure | Enables quick geometry optimization |
| Socket-based electronics mounting | Supports fast diagnostics and replacement |
| Segmented power distribution architecture | Improves electrical stability under load |
| Adjustable sensor mounting interfaces | Allows rapid calibration refinement |
| Accessible drivetrain assembly | Simplifies tuning and maintenance |

---

### **Competition-Oriented Engineering Goal**

Our manufacturing workflow follows a competition-focused engineering methodology:

- prioritize reliability over complexity
- design for maintainability during live testing
- ensure subsystem independence
- enable fast iteration between test sessions
- maintain full control over system architecture

This approach allowed us to continuously refine both mechanical and electrical subsystems while preserving stability and repeatability across testing runs.

## 🛠 Engineering Challenges & Solutions

### Structural Layout Optimization

During development, one of the main challenges was organizing the internal structure of the robot while maintaining compact dimensions and stable weight distribution. Since the electronics were mounted directly on the base layer, careful placement was required to avoid interference between components and ensure reliable operation.

Root Cause Analysis:
- Limited chassis space with multiple electronic modules installed on the base platform  
- Risk of steering mechanism interference with the front bumper  
- Need for stable placement of Raspberry Pi, LiDAR sensor, and battery for balanced weight distribution  
- Requirement to maintain accessibility to Raspberry Pi ports for configuration and testing  

Engineering Solution:
- Electronics-first architecture implemented by mounting Raspberry Pi and core modules on the base layer before drivetrain installation  
- Steering geometry adjusted to maintain safe rotation clearance near the front bumper  
- Battery placement optimized to improve center-of-mass stability  
- External access to Raspberry Pi ports preserved for easier setup and debugging  

---

### Mechanical Strength vs Weight Optimization

Another engineering challenge involved selecting the optimal internal structure for 3D-printed components to achieve sufficient strength without increasing robot weight.

Root Cause Analysis:
- Need to reduce overall robot mass for improved movement efficiency  
- Requirement to maintain durability of load-bearing printed components  
- Multiple infill pattern options available (gyroid, honeycomb, linear, cubic) with different performance characteristics  

Engineering Solution:
- Comparative evaluation of several infill structures performed during prototyping  
- Gyroid infill selected due to its balanced strength-to-weight characteristics  
- Printing parameters optimized to ensure reliable structural performance during competition runs  

---

### Sensor Integration Stability

Integration of LiDAR and camera systems required careful positioning to ensure reliable environmental perception without mechanical obstruction.

Root Cause Analysis:
- LiDAR required stable mounting for accurate distance measurement  
- Camera required clear forward orientation for color detection  
- Risk of wiring interference with moving steering components  

Engineering Solution:
- Dedicated LiDAR holder designed for stable sensor positioning  
- Camera placement optimized for reliable color detection during navigation  
- Organized cable routing implemented to prevent interference with steering movement

## **📚References of components**
| Component | Files | Key Specifications | Qty |
|----------|-------|--------------------|-----|
| Yellow TT Gear Motor | [Yellow DC 3V–6V Gear Motor TT_specification.pdf](https://github.com/user-attachments/files/26836848/Yellow.DC.3V.6V.Gear.Motor.TT_specification.pdf) | DC 3V–6V gear motor, no-load current 160–240 mA, speed 130–290 rpm, gear ratio 1:48 | 1 |
| MG996R V17 Servo |  [MG996R_specification.pdf](https://github.com/user-attachments/files/26836880/MG996R_specification.pdf) | High torque digital servo, 4.8–7.2V, speed 0.17 s/60° (6V), metal gears, ~180° rotation | 1 |
| HW-411 Buck Converter | [HW‑411 DC‑DC Buck Converter Module_specification.pdf](https://github.com/user-attachments/files/26836905/HW.411.DC.DC.Buck.Converter.Module_specification.pdf) | LM2596-based step-down converter, input 4–40V, output 1.25–35V, up to ~3A, high efficiency (~92%) | 2 |
| USB 8MP 4K Camera | [USB 8MP 4K 60fps Camera.specification.pdf](https://github.com/user-attachments/files/26837379/USB.8MP.4K.60fps.Camera.specification.pdf)| IMX415 sensor, 8MP resolution, 4K support, wide-angle USB camera module | 1 |
| DRV8833 Motor Driver | [DRV8833_specification.pdf](https://github.com/user-attachments/files/26837410/DRV8833_specification.pdf) | Dual H-bridge driver, 2.7–10.8V, up to 1.5A per channel, PWM control, built-in protection | 1 |
| PCA9685 Servo Driver | [MG996R_specification.pdf](https://github.com/user-attachments/files/26837420/MG996R_specification.pdf) | 16-channel PWM driver, 12-bit resolution, I2C interface, 3.3V/5V compatible, 24–1526 Hz frequency | 1 |
| Raspberry Pi 5 (1GB) | [MG996R_specification.pdf](https://github.com/user-attachments/files/26837428/MG996R_specification.pdf) | Quad-core 2.4 GHz Cortex-A76, 1GB RAM, dual 4K HDMI, Wi-Fi, Bluetooth, USB 3.0, GPIO 40-pin | 1 |
| RPLIDAR |  | 360° laser scanning LiDAR, up to ~10–12 m range, used for SLAM and navigation | 1 |
| SS12D10 Slide Switch | [SS12D10_90_Degree_specification.pdf](https://github.com/user-attachments/files/26837433/SS12D10_90_Degree_specification.pdf) | SPDT slide switch, 90° actuation, ~12–24V DC rated, used for power control | 1 |

## **✅Engineering Validation**

This comprehensive electrical documentation provides full transparency into our robot’s system architecture, component selection, and integration methodology. Each component was carefully chosen and tested to ensure reliable interaction between control, sensing, and actuation systems.

The overall electrical design has been optimized for stability, maintainability, and consistent performance under WRO Future Engineers competition conditions.

### Development Convenience Features
Implementation of accessible Raspberry Pi port openings significantly improved development workflow, enabling fast code uploading, debugging, and continuous testing without disassembling the robot.
<img width="1280" height="720" alt="Back photo" src="https://github.com/user-attachments/assets/d11bf17a-0460-4727-8acf-20babed3cbf4" />
<img width="1280" height="720" alt="Right side photo" src="https://github.com/user-attachments/assets/40024c57-c6d4-44c3-b635-7f5fd52597a1" />





## ⚙ Mechanical Systems
Our design focused on achieving high performance while maintaining a structure similar to a real vehicle. Instead of minimizing size and weight, we optimized the chassis to complete the track in the shortest possible time while ensuring stability and reliable component placement.
### Core Mechanical Specifications

### Our Design
<img width="990" height="484" alt="CAD general photo" src="https://github.com/user-attachments/assets/812c01b3-0bcf-42ee-b5dc-5ec3e5c3a82b" />
<img width="1280" height="720" alt="General photo" src="https://github.com/user-attachments/assets/70b3300f-dde2-413f-9a0b-f1dc398f6079" />

## **⚙️Steering and 4-Gear Mechanical Differential systems:** 
The steering system is designed as a hybrid LEGO and 3D-printed mechanism with the following goals:

 - Provide **precise and repeatable turning control** for accurate navigation on the WRO field
 
 - Use a **simple front-wheel steering mechanism** driven by a single servo motor for reliability and simplicity
 
 - Integrate a **LEGO differential system** to ensure smooth and stable wheel rotation during turns
 
 - Minimize **mechanical friction** by carefully aligning all moving components
 
 - Apply light lubrication to improve **movement consistency and efficiency**
 
 - Combine LEGO and 3D-printed parts to achieve a **balance between structural rigidity and custom precision parts**
 
 - Ensure stable and predictable behavior of the robot during movement on a **3×3 meter competition field**

   ## **📁Complete Manufacturing File Repository**
#### **3D Printing Files & Assembly Specifications**
| Component  | Quantity | Description | CAD Photo Preview |
|-----------|-----------|-------------|-------------------|
| **Main Chassis** | 1 | Primary structure with integrated mounting system |  |
| **LEGO 4-Gear Differential**  | 1 |A LEGO differential is a drivetrain component that distributes torque between the left and right wheels, allowing them to rotate at different speeds during turns for smooth and stable cornering. |  |
| **Bumper** | 1 |  A front bumper is a structural protective component mounted on the front of the robot, designed to absorb minor impacts and protect internal systems while maintaining clearance for the steering mechanism, and it also serves as a mounting point for LED headlights | <img width="556" height="422" alt="Снимок экрана 2026-04-16 015010" src="https://github.com/user-attachments/assets/1a684ae9-2750-41ef-a5d2-e526f7f97032" /> |
| **Back right wheel fender** |  1 |  Protective wheel panel providing structural protection and body support. | <img width="475" height="440" alt="Снимок экрана 2026-04-16 142714" src="https://github.com/user-attachments/assets/e4ca66f8-c5de-4041-859c-59e8e564247f" />  |
| **Back left wheel fender** | 1 | Protective wheel panel providing structural protection and body support. | <img width="475" height="440" alt="Снимок экрана 2026-04-16 142714" src="https://github.com/user-attachments/assets/bee1b1b7-691c-4c60-868c-511f0173ac1f" /> |
| **Front left wheel fender** | 1 | Protective wheel panel providing structural protection and necessary clearance for steering rotation. | <img width="581" height="529" alt="Снимок экрана 2026-04-16 142253" src="https://github.com/user-attachments/assets/fde47f0d-28a5-4b79-a01f-baea723fa5ec" /> | 
| **Front right wheel fender** | 1 | Protective wheel panel providing structural protection and necessary clearance for steering rotation. | <img width="581" height="529" alt="Снимок экрана 2026-04-16 142253" src="https://github.com/user-attachments/assets/7eec2aef-ac16-4f15-affb-9eb86770cd17" />  | 
| **Disk for wheel** | 4 | Custom wheel disk ensuring reliable connection between the wheel and drivetrain. | <img width="505" height="339" alt="Снимок экрана 2026-04-16 120709" src="https://github.com/user-attachments/assets/e118a329-f708-470c-b00f-0f14c5747433" />  |
| **Servo Gear** | 1 |  Transmission gear transferring rotation from the servo motor to the steering mechanism. | <img width="442" height="446" alt="Снимок экрана 2026-04-16 113454" src="https://github.com/user-attachments/assets/c9bd2d08-e307-4eea-8f5d-15806db6785b" />  | 
| **Left holder** | 1 | Structural holder designed to simplify safe robot handling and transportation. | <img width="591" height="445" alt="Снимок экрана 2026-04-16 143249" src="https://github.com/user-attachments/assets/5e96fae0-6a19-4f36-b9bd-c2e22ead2b49" /> |
| **Right holder** | 1 | Structural holder designed to simplify safe robot handling and transportation. | <img width="591" height="445" alt="Снимок экрана 2026-04-16 143249" src="https://github.com/user-attachments/assets/e4a8cada-1572-4309-9d1b-f13473132678" />  | 
| **Lidar holder** | 1 | Mount designed for stable LiDAR sensor installation. | <img width="631" height="434" alt="Снимок экрана 2026-04-16 140928" src="https://github.com/user-attachments/assets/87ab3294-97bf-4869-b7da-bec91e4faf91" /> | 
| **Lower left body panel** | 1 | Body panel used to reinforce chassis structure. |  <img width="501" height="468" alt="Снимок экрана 2026-04-16 140342" src="https://github.com/user-attachments/assets/cc8de552-ae55-481c-b917-31fe9651449e" /> | 
| **Lower right body panel** |  1 | Body panel used to reinforce chassis structure. | <img width="599" height="424" alt="Снимок экрана 2026-04-16 145644" src="https://github.com/user-attachments/assets/19c2fa43-92ba-465b-a933-0674d3239d6a" />  | 
| **Upper right body panel** |  1 | Body panel used to protect internal robot components. | <img width="577" height="441" alt="Снимок экрана 2026-04-16 135838" src="https://github.com/user-attachments/assets/bdb19c56-4f39-488e-bd08-6972e738974a" /> |  
| **Upper left body panel** |  1 | Body panel used to protect internal robot components. | <img width="488" height="497" alt="Снимок экрана 2026-04-16 140112" src="https://github.com/user-attachments/assets/e2fa7855-ffcc-46fe-a3d2-e4ea9cf8ce7f" />  |  
| **Motor holder** |  1 | Mount designed for secure drivetrain motor fixation. | <img width="476" height="185" alt="Снимок экрана 2026-04-16 113226" src="https://github.com/user-attachments/assets/8a2ecd13-bc6b-4f54-bf51-e770bfbf5672" /> | 
| **Raspberry upper holder** |  1 | Mount used to secure the Raspberry Pi board. |  <img width="631" height="434" alt="Снимок экрана 2026-04-16 140928" src="https://github.com/user-attachments/assets/096a85af-7417-44d8-819f-6460d478c959" /> | 
| **Raspberry lower holder** |  1 |  Mount used to secure the Raspberry Pi board. | <img width="729" height="512" alt="Снимок экрана 2026-04-16 113956" src="https://github.com/user-attachments/assets/c8061646-2289-4a14-b08a-15e4aa7d81bc" /> |
| **Swich 2 Axis** |  1 | Mount designed for installation of the 2-axis control switch. | <img width="624" height="528" alt="Снимок экрана 2026-04-16 141304" src="https://github.com/user-attachments/assets/ea85fff0-97f6-46ad-9a5f-e77436cfd11d" /> | 
| **Wheel 45 degree Rotator** |  1 | Steering mechanism component enabling wheel rotation up to 45°. |  <img width="627" height="456" alt="Снимок экрана 2026-04-16 120034" src="https://github.com/user-attachments/assets/dd7cd1a3-0e75-4916-a396-5912854f5a8e" /> |  
| **180 degree gea** |  1 | Gear used for rotation of front wheels within the steering mechanism. | <img width="729" height="441" alt="Снимок экрана 2026-04-16 113746" src="https://github.com/user-attachments/assets/2abac45d-b16f-4f36-b3f8-9a46610f2776" /> |
| **Wheel holder left** | 1 | Mount designed to secure the wheel and maintain correct alignment. | <img width="727" height="453" alt="Снимок экрана 2026-04-16 135411" src="https://github.com/user-attachments/assets/58fa46c3-0bb7-4486-9d35-7389be6198da" /> | 
| **Lego wheels** | 4 |  Standard LEGO wheel used for robot movement, providing traction, stability, and reliable motion on the competition field. | <img width="385" height="325" alt="Снимок экрана 2026-04-16 165149" src="https://github.com/user-attachments/assets/88dc3f68-e868-42c3-83d1-f9f13da57646" /> |  

## Assembly Methodology
 <img width="720" height="1280" alt="photo_2026-04-16_02-32-52" src="https://github.com/user-attachments/assets/813e8d7c-6c3d-49c9-a3e2-46e0d00fd0f2" />

**Assembly Sequence:**
- Base Structure Integration: Bottom chassis construction with electronics mounting, wiring setup, motor installation, and battery placement
- Mechanical System Assembly: Upper chassis completion, steering mechanism integration, and wheel + differential installation
- System Integration: Connection of all mechanical, electrical, and control systems into a unified architecture
- Final Validation: Structural verification, alignment checks, and full drivetrain and steering performance testing
