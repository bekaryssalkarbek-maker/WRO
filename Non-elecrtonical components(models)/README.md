# **Models documentation**
This folder contains the complete 3D CAD models and manufacturing files for the team CyberBots WRO 2026 Future Engineers robot. All mechanical components were carefully designed and assembled to achieve our goal of completing the track in the shortest possible time while keeping the robot’s external structure as similar as possible to a real vehicle. The initial structural concept was inspired by the Mars Rover, particularly in terms of base layout, after which the design was further adapted to resemble a conventional ground vehicle. The design process focused on improving stability, component placement efficiency, and realistic vehicle proportions while ensuring reliable integration of all systems inside a chassis.

<img width="990" height="484" alt="Screenshot 2026-04-15 at 11 12 22" src="https://github.com/user-attachments/assets/72d100cb-582a-4746-af32-988386d658b2" />

<img width="1280" height="720" alt="photo_2026-04-19_05-08-14" src="https://github.com/user-attachments/assets/218898eb-68ea-4962-bdb7-21483a5193d4" />





## **🎯Design Goals:**
Our design focused on achieving high performance while maintaining a structure similar to a real vehicle. Instead of minimizing size and weight, we optimized the chassis to complete the track in the shortest possible time while ensuring stability and reliable component placement. Special attention was given to realistic vehicle proportions and efficient internal layout so that all mechanical and electronic components could operate without interference inside a compact structure.

## **⚙️Steering and 4-Gear Mechanical Differential systems:** 
The steering system is designed as a hybrid LEGO and 3D-printed mechanism with the following goals:

 - Provide **precise and repeatable turning control** for accurate navigation on the WRO field
 
 - Use a **simple front-wheel steering mechanism** driven by a single servo motor for reliability and simplicity
 
 - Integrate a **LEGO differential system** to ensure smooth and stable wheel rotation during turns
 
 - Minimize **mechanical friction** by carefully aligning all moving components
 
 - Apply light lubrication to improve **movement consistency and efficiency**
 
 - Combine LEGO and 3D-printed parts to achieve a **balance between structural rigidity and custom precision parts**
 
 - Ensure stable and predictable behavior of the robot during movement on a **3×3 meter competition field**

<img width="720" height="800" alt="Differential" src="https://github.com/user-attachments/assets/fe4e534b-013c-4913-af2e-0b3cc791b225" />

https://github.com/user-attachments/assets/e802eda8-740b-4b7b-a47c-ce4926abeb2c

<img width="495" height="564" alt="Снимок экрана 2026-04-19 041454" src="https://github.com/user-attachments/assets/ed89cba6-75d6-42c0-8a24-96551a3d9dae" />




## **🏗️Chassis and Structural Design:**
- Provide a **strong and stable base structure** capable of supporting all electronic and mechanical components

 - Maintain an effective **balance between structural strength and lightweight construction** to improve speed and efficiency
 
 - Use an **initial layout inspired by the Mars Rover platform** to improve stability and component distribution
 
 - Adapt the final structure to resemble a **conventional ground vehicle design** with realistic proportions
 
 - Avoid adding a suspension system because the **competition track is flat and predictable**
 
 - Reduce **unnecessary weight and mechanical complexity** by using a rigid chassis instead of shock absorbers
 
 - Integrate **LEGO structural elements together with custom 3D-printed parts** for precise mounting and compact component placement
 
 - Ensure stable positioning of key systems such as the **differential, steering system, motors, and control electronics**

<img width="375" height="280" alt="Снимок экрана 2026-04-19 041640" src="https://github.com/user-attachments/assets/3efeac46-7361-405e-a71e-c5b23a6135c0" />


 ## **🏭Manufacturing Process:**
 We utilized a locally available 3D printer within our workspace to manufacture custom-designed components. This allowed us to rapidly prototype parts, test different design iterations, and refine mechanical performance efficiently during the development process.

### **🖨️CAD & Slicing Software Integration:**
 - **Design Platform:** Autodesk Fusion for comprehensive 3D modeling, simulation, and engineering analysis
 
 - **Slicing Software:** Creality Print 7 for optimized print preparation and manufacturing parameter management
 
 - **3D Printer:** Creality Ender 3 V3 SE FDM printer used for in-house fabrication of custom mechanical components
 
 - **Workflow Integration:** Seamless transition from CAD design to manufacturing-ready files for rapid prototyping and production

 <img width="960" height="1280" alt="photo_2026-04-16_17-16-10" src="https://github.com/user-attachments/assets/461826ef-e81d-4051-933a-86081cd35ae9" />


## **🛠️Infilling Selection Process:**
**Final Infilling:** Gyroid infill

**Infilling Choices && Explanations:**
- **Gyroid infill** — Selected as the final choice due to its optimal balance between weight reduction and mechanical strength, providing high structural rigidity with minimal material usage
 
- **Honeycomb infill** — Offered good strength but resulted in higher material consumption and weight
 
- **Linear infill** — Lightweight but insufficient in strength for load-bearing components
 
- **Cubic infill** — Provided uniform strength but was less efficient in weight optimization compared to gyroid


## **🔥Engineering Challenge:**
During the mechanical design process, we encountered several structural challenges that required iterative improvements:

- **Front bumper and wheel rotator sharing the same space:**
The initial design resulted in a spatial conflict where the front bumper and the wheel rotator (steering mechanism) occupied overlapping space. This caused limitations in assembly and restricted the movement of the steering system. To solve this issue, we redesigned the bumper in Autodesk Fusion, adjusting its geometry and repositioning it to provide dedicated clearance for the wheel rotator, ensuring full steering functionality without compromising the overall structure.
#### **First Model**
<img width="570" height="386" alt="Снимок экрана 2026-04-16 015208" src="https://github.com/user-attachments/assets/a041b2ff-99e1-4c8a-b007-5f14be15b739" />

#### **Improved Model**
<img width="556" height="422" alt="Снимок экрана 2026-04-16 015010" src="https://github.com/user-attachments/assets/059d2d1f-b395-40a3-b4cc-67eb3d3c3d86" />

- **Upper enclosure cover interfering with Raspberry Pi connections:**
The top cover of the electronics enclosure, which holds the Raspberry Pi, partially blocked access to several GPIO pin connections. This problem was solved by physically removing a small section of the cover that did not affect the structural integrity or external appearance of the robot, allowing proper cable routing and reliable connections.
#### **First Model**
<img width="503" height="412" alt="Снимок экрана 2026-04-16 015659" src="https://github.com/user-attachments/assets/3f88304d-6a00-419f-a4e0-6797c06a0604" />

#### **Modified Model**
 <img width="960" height="1280" alt="photo_2026-04-16_13-39-19" src="https://github.com/user-attachments/assets/162d14e3-075f-4eae-80b3-6145b4859bd9" />


- **Differential manufacturing limitations due to 3D printing constraints:**
The original plan was to manufacture a custom differential using 3D printing. However, due to printer limitations and insufficient precision for small mechanical tolerances, the printed design could not function reliably. As a result, we switched to a LEGO-based differential system and integrated its components into our drivetrain. This solution ensured smooth and reliable torque distribution while maintaining mechanical simplicity and reducing manufacturing risks.

- **Front fender interference**
During early mechanical testing, the front fenders were found to interfere with wheel rotation during steering due to the compact chassis layout. To improve steering clearance and ensure smooth turning performance, the fenders were removed from the final design. This modification significantly increased maneuverability and improved overall navigation stability during autonomous runs on the WRO field.

## **🧩Assembly Guide**
**Step-by-Step Assembly Process:**

<img width="720" height="1280" alt="photo_2026-04-16_02-32-52" src="https://github.com/user-attachments/assets/7acfaac6-ecf2-4e52-9997-0fc8be28b0bb" />

#### **Phase 1: Base Structure & Foundation Assembly**

- **Bottom Layer Construction:** The assembly process began with the bottom structural layer, forming the main chassis “floor” as the primary load-bearing foundation for all components
 
- **Electronics Mounting:** Installation of the Raspberry Pi and supporting electronic components directly onto the base layer for compact and stable integration

- **Wiring & Connectivity Setup:** Organization and connection of all power and control wiring to ensure clean routing and accessibility

- **Motor Installation:** Integration of the Yellow DC TT Gear Motor (3V–6V, 130–290 rpm, 1:48 gear ratio) as the main drivetrain motor, mounted securely onto the base structure

- **Power System Integration:** Placement of the battery in an optimized position to maintain stable weight distribution and balance

- **Initial Mechanical Alignment:** Early verification of structural alignment to ensure correct positioning of drivetrain components before upper assembly




#### **Phase 2: Upper Structure & Mechanical Systems**

- **Chassis Completion:** Installation of upper structural elements to protect internal systems while maintaining modular accessibility

- **Steering System Integration:** Assembly of the front steering mechanism, including rotator system, with adjustments to avoid spatial conflicts with the bumper

- **Wheel & Differential Installation:** Final integration of wheels and LEGO differential system, ensuring smooth torque transfer and correct alignment with the drivetrain


#### **Phase 3: Final System Assembly & Validation**

- **Full System Integration:** Connection of mechanical, electrical, and control systems into a unified working robot

- **Structural Verification:** Final checks of mechanical stability, component fitment, and assembly integrity

- **Functional Testing:** Validation of drivetrain efficiency, steering response, and overall robot movement performance



## **🔄Component Development & Engineering Itegration**
**Component Development & Engineering Iteration**

- Gear system evolution: The drivetrain was developed through multiple iterations, combining LEGO gear components with optimized alignment to improve smooth torque transfer and reduce friction losses.

 - Steering mechanism refinement: The steering system was repeatedly redesigned to solve spatial conflicts with the bumper and wheel rotator, achieving precise control with minimal mechanical restriction and improved turning clearance.
 
 - Structural component optimization: The chassis and body components were iteratively adjusted to balance strength and lightweight construction, ensuring stable mounting of all electronics and mechanical parts under dynamic movement.
 
 - Differential integration approach: Due to limitations of the 3D printer in producing small and precise mechanical tolerances, a LEGO differential system was adopted and successfully integrated into the drivetrain for reliable and smooth operation.
 
 - System integration validation: Continuous testing ensured compatibility between LEGO mechanical elements, 3D-printed parts, and the Raspberry Pi-based control system, improving overall system reliability and assembly efficiency.

## **🎯Performance Analysis**





## **📊Engineering Calculations & Performance Validation**


## **📁Complete Manufacturing File Repository**
#### **3D Printing Files & Assembly Specifications**
| Component  | Quantity | Description | CAD Photo Preview |
|-----------|-----------|-------------|-------------------|
| **Main Chassis** | 1 | Primary structure with integrated mounting system | <img width="375" height="280" alt="Снимок экрана 2026-04-19 041640" src="https://github.com/user-attachments/assets/eae22bbc-7fa8-4479-9273-14218230db48" /> |
| **LEGO 4-Gear Differential**  | 1 |A LEGO differential is a drivetrain component that distributes torque between the left and right wheels, allowing them to rotate at different speeds during turns for smooth and stable cornering. | <img width="900" height="900" alt="image" src="https://github.com/user-attachments/assets/eceb4ce4-00ff-4d6e-8991-0a77ea6a0f8b" /> |
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
| **Raspberry upper holder** |  1 | Mount used to secure the Raspberry Pi board. |   <img width="503" height="412" alt="Снимок экрана 2026-04-16 015659" src="https://github.com/user-attachments/assets/e9208a34-350c-4a35-9a1e-74e30fb302e6" />  | 
| **Raspberry lower holder** |  1 |  Mount used to secure the Raspberry Pi board. | <img width="729" height="512" alt="Снимок экрана 2026-04-16 113956" src="https://github.com/user-attachments/assets/c8061646-2289-4a14-b08a-15e4aa7d81bc" /> |
| **Swich 2 Axis** |  1 | Mount designed for installation of the 2-axis control switch. | <img width="624" height="528" alt="Снимок экрана 2026-04-16 141304" src="https://github.com/user-attachments/assets/ea85fff0-97f6-46ad-9a5f-e77436cfd11d" /> | 
| **Wheel 45 degree Rotator** |  1 | Steering mechanism component enabling wheel rotation up to 45°. |  <img width="627" height="456" alt="Снимок экрана 2026-04-16 120034" src="https://github.com/user-attachments/assets/dd7cd1a3-0e75-4916-a396-5912854f5a8e" /> |  
| **180 degree gea** |  1 | Gear used for rotation of front wheels within the steering mechanism. | <img width="729" height="441" alt="Снимок экрана 2026-04-16 113746" src="https://github.com/user-attachments/assets/2abac45d-b16f-4f36-b3f8-9a46610f2776" /> |
| **Wheel holder left** | 1 | Mount designed to secure the wheel and maintain correct alignment. | <img width="727" height="453" alt="Снимок экрана 2026-04-16 135411" src="https://github.com/user-attachments/assets/58fa46c3-0bb7-4486-9d35-7389be6198da" /> | 
| **Lego wheels** | 4 |  Standard LEGO wheel used for robot movement, providing traction, stability, and reliable motion on the competition field. | <img width="385" height="325" alt="Снимок экрана 2026-04-16 165149" src="https://github.com/user-attachments/assets/88dc3f68-e868-42c3-83d1-f9f13da57646" /> |  

## **🚀Engineering Design & Development Process**
#### **🔄Comprehensive Iterative Engineering Approach**

**Conceptual Design & Requirements Analysis**
 - Competition size constraint analysis and chassis dimension optimization
 
 - Steering system layout planning with rotation clearance consideration for front wheel movement
 
 - Strategic placement planning of Raspberry Pi, LiDAR sensor, drivetrain motor, and battery for balanced weight distribution
 
 - Structural holder integration for safe robot handling and transportation

**Precision CAD Modeling & Engineering Simulation**

-  Detailed CAD modeling of custom mechanical components in Autodesk Fusion
 
-  Steering mechanism geometry validation including servo gear and 45° wheel rotator alignment
 
-  Spatial verification to prevent interference between steering system and front bumper
 
-  Integration modeling of LEGO differential with drivetrain structure

**Prototyping & Performance Optimization**
 - Multiple iterations of 3D printed components for improved fit and mechanical stability
 
 - Testing of different infill structures (gyroid, honeycomb, linear, cubic) for strength-to-weight optimization
 
 - Selection of gyroid infill pattern to achieve optimal balance between durability and lightweight structure
 
 - Verification of LiDAR holder positioning for stable sensing performance

**Production Engineering & System Validation**
 - Optimization of printing parameters for reliable and repeatable part production
 
 - Development of structured assembly sequence starting from electronics base integration followed by drivetrain installation
 
 - Full mechanical system alignment verification including wheels, steering system, and differential
 
 - Competition-condition movement testing including drivetrain efficiency and steering responsiveness
 
 - Final validation of structural stability, LED headlight mounting

## ✅Engineering Validation & Testing Protocols

### 🧪Mechanical System Verification & CAD Design Testing

- Differential Operation Validation: Testing of LEGO 4-gear differential confirmed stable torque distribution and smooth drivetrain performance during autonomous movement.
- Steering System Verification: Front steering linkage tested in real driving conditions to ensure reliable wheel rotation clearance and stable turning behavior on the WRO field.
- Structural Integrity Assessment: PETG chassis components validated through repeated movement tests over minor surface irregularities to confirm strength and durability.
- Component Placement Optimization: CAD-based layout adjustments performed to improve internal spacing, accessibility, and weight distribution stability.

**Fender Design Modification:** Front fenders removed after testing revealed interference with wheel rotation during turning, improving steering freedom and overall navigation performance.

### 🏆Competition Readiness & Reliability Engineering

- Regulation Compliance Verification: Full compliance with WRO Future Engineers 2026 regulations including maximum robot dimensions of 300 × 200 × 300 mm and fully autonomous onboard operation using integrated sensors and computing systems.
- Operational Reliability Demonstration: Repeated autonomous driving tests performed on the 3 × 3 meter competition field confirming stable navigation, obstacle detection, and consistent steering performance.
- Maintenance & Service Protocols: Modular chassis structure and accessible Raspberry Pi ports allow fast software updates, wiring inspection, and mechanical adjustments during testing and competition preparation.
- Backup System Preparation: Spare mechanical components, electronic modules, and pre-tested software configurations prepared to ensure quick recovery in case of unexpected issues during competition runs.

------------------------------------------------------------------------------------------------------------------------------------------------------------------
This comprehensive mechanical documentation provides full transparency into our design process, CAD development, manufacturing methods, validation procedures, and engineering decisions. Every part of our mechanical system has been optimized for the requirements of the WRO Future Engineers 2026 category, focusing on compact design, stability, and reliable autonomous performance on the 3 × 3 meter competition field.
