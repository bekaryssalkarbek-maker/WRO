# **Models documentation**
This folder contains the complete 3D CAD models and manufacturing files for the team CyberBots WRO 2026 Future Engineers robot. All mechanical components were carefully designed and assembled to achieve our goal of completing the track in the shortest possible time while keeping the robot’s external structure as similar as possible to a real vehicle. The initial structural concept was inspired by the Mars Rover, particularly in terms of base layout, after which the design was further adapted to resemble a conventional ground vehicle. The design process focused on improving stability, component placement efficiency, and realistic vehicle proportions while ensuring reliable integration of all systems inside a chassis.

<img width="990" height="484" alt="Screenshot 2026-04-15 at 11 12 22" src="https://github.com/user-attachments/assets/72d100cb-582a-4746-af32-988386d658b2" />

![photo_2026-04-15_23-16-42](https://github.com/user-attachments/assets/a7772561-089b-47cc-9cec-4b4a99889604)




## **🎯Design Goals:**
Our design focused on achieving high performance while maintaining a structure similar to a real vehicle. Instead of minimizing size and weight, we optimized the chassis to complete the track in the shortest possible time while ensuring stability and reliable component placement. Special attention was given to realistic vehicle proportions and efficient internal layout so that all mechanical and electronic components could operate without interference inside a compact structure.

## **⚙️Steering and 4-Gear Mechanical Differential systems:** 
The steering system is designed as a hybrid LEGO and 3D-printed mechanism with the following goals:

 • Provide **precise and repeatable turning control** for accurate navigation on the WRO field
 
 • Use a **simple front-wheel steering mechanism** driven by a single servo motor for reliability and simplicity
 
 • Integrate a **LEGO differential system** to ensure smooth and stable wheel rotation during turns
 
 • Minimize **mechanical friction** by carefully aligning all moving components
 
 • Apply light lubrication to improve **movement consistency and efficiency**
 
 • Combine LEGO and 3D-printed parts to achieve a **balance between structural rigidity and custom precision parts**
 
 • Ensure stable and predictable behavior of the robot during movement on a **3×3 meter competition field**

## **🏗️Chassis and Structural Design:**
• Provide a **strong and stable base structure** capable of supporting all electronic and mechanical components

 • Maintain an effective **balance between structural strength and lightweight construction** to improve speed and efficiency
 
 • Use an **initial layout inspired by the Mars Rover platform** to improve stability and component distribution
 
 • Adapt the final structure to resemble a **conventional ground vehicle design** with realistic proportions
 
 • Avoid adding a suspension system because the **competition track is flat and predictable**
 
 • Reduce **unnecessary weight and mechanical complexity** by using a rigid chassis instead of shock absorbers
 
 • Integrate **LEGO structural elements together with custom 3D-printed parts** for precise mounting and compact component placement
 
 • Ensure stable positioning of key systems such as the **differential, steering system, motors, and control electronics**

 ## **🏭Manufacturing Process:**
 We utilized a locally available 3D printer within our workspace to manufacture custom-designed components. This allowed us to rapidly prototype parts, test different design iterations, and refine mechanical performance efficiently during the development process.

### **🖨️CAD & Slicing Software Integration:**
 • **Design Platform:** Autodesk Fusion for comprehensive 3D modeling, simulation, and engineering analysis
 
 • **Slicing Software:** Creality Print 7 for optimized print preparation and manufacturing parameter management
 
 • **3D Printer:** Creality Ender 3 V3 SE FDM printer used for in-house fabrication of custom mechanical components
 
 • **Workflow Integration:** Seamless transition from CAD design to manufacturing-ready files for rapid prototyping and production

 <img width="960" height="1280" alt="3d printer" src="https://github.com/user-attachments/assets/e73dc7a7-d24a-484a-8bfe-30a47b6a5575" />

## **🛠️Comprehensive Material Selection Process:**
**Final Material:**

**Material Testing Results & Explanation:**

**Selection Explanation**

## **🔥Engineering Challenge:**
During the mechanical design process, we encountered several structural challenges that required iterative improvements:

 **• Front bumper and wheel rotator sharing the same space:**
The initial design resulted in a spatial conflict where the front bumper and the wheel rotator (steering mechanism) occupied overlapping space. This caused limitations in assembly and restricted the movement of the steering system. To solve this issue, we redesigned the bumper in Autodesk Fusion, adjusting its geometry and repositioning it to provide dedicated clearance for the wheel rotator, ensuring full steering functionality without compromising the overall structure.
#### **First Model**
<img width="570" height="386" alt="Снимок экрана 2026-04-16 015208" src="https://github.com/user-attachments/assets/a041b2ff-99e1-4c8a-b007-5f14be15b739" />

#### **Improved Model**
<img width="556" height="422" alt="Снимок экрана 2026-04-16 015010" src="https://github.com/user-attachments/assets/059d2d1f-b395-40a3-b4cc-67eb3d3c3d86" />

 **• Upper enclosure cover interfering with Raspberry Pi connections:**
The top cover of the electronics enclosure, which holds the Raspberry Pi, partially blocked access to several GPIO pin connections. This problem was solved by physically removing a small section of the cover that did not affect the structural integrity or external appearance of the robot, allowing proper cable routing and reliable connections.
#### **First Model**
<img width="503" height="412" alt="Снимок экрана 2026-04-16 015659" src="https://github.com/user-attachments/assets/3f88304d-6a00-419f-a4e0-6797c06a0604" />

#### **Modified Model**
 <img width="960" height="1280" alt="photo_2026-04-16_13-39-19" src="https://github.com/user-attachments/assets/162d14e3-075f-4eae-80b3-6145b4859bd9" />


**• Differential manufacturing limitations due to 3D printing constraints:**
The original plan was to manufacture a custom differential using 3D printing. However, due to printer limitations and insufficient precision for small mechanical tolerances, the printed design could not function reliably. As a result, we switched to a LEGO-based differential system and integrated its components into our drivetrain. This solution ensured smooth and reliable torque distribution while maintaining mechanical simplicity and reducing manufacturing risks.


## **🧩Assembly Guide**
**Step-by-Step Assembly Process:**

<img width="720" height="1280" alt="photo_2026-04-16_02-32-52" src="https://github.com/user-attachments/assets/7acfaac6-ecf2-4e52-9997-0fc8be28b0bb" />

#### **Phase 1: Base Structure & Foundation Assembly**

 **• Bottom Layer Construction:** The assembly process began with the bottom structural layer, forming the main chassis “floor” as the primary load-bearing foundation for all components
 
**• Electronics Mounting:** Installation of the Raspberry Pi and supporting electronic components directly onto the base layer for compact and stable integration

**• Wiring & Connectivity Setup:** Organization and connection of all power and control wiring to ensure clean routing and accessibility

**• Motor Installation:** Integration of the Yellow DC TT Gear Motor (3V–6V, 130–290 rpm, 1:48 gear ratio) as the main drivetrain motor, mounted securely onto the base structure

**• Power System Integration:** Placement of the battery in an optimized position to maintain stable weight distribution and balance

**• Initial Mechanical Alignment:** Early verification of structural alignment to ensure correct positioning of drivetrain components before upper assembly




#### **Phase 2: Upper Structure & Mechanical Systems**

**• Chassis Completion:** Installation of upper structural elements to protect internal systems while maintaining modular accessibility

**• Steering System Integration:** Assembly of the front steering mechanism, including rotator system, with adjustments to avoid spatial conflicts with the bumper

**• Wheel & Differential Installation:** Final integration of wheels and LEGO differential system, ensuring smooth torque transfer and correct alignment with the drivetrain


#### **Phase 3: Final System Assembly & Validation**

**• Full System Integration:** Connection of mechanical, electrical, and control systems into a unified working robot

**• Structural Verification:** Final checks of mechanical stability, component fitment, and assembly integrity

**• Functional Testing:** Validation of drivetrain efficiency, steering response, and overall robot movement performance



## **🔄Component Development & Engineering Itegration**
**Component Development & Engineering Iteration**

• Gear system evolution: The drivetrain was developed through multiple iterations, combining LEGO gear components with optimized alignment to improve smooth torque transfer and reduce friction losses.

 • Steering mechanism refinement: The steering system was repeatedly redesigned to solve spatial conflicts with the bumper and wheel rotator, achieving precise control with minimal mechanical restriction and improved turning clearance.
 
 • Structural component optimization: The chassis and body components were iteratively adjusted to balance strength and lightweight construction, ensuring stable mounting of all electronics and mechanical parts under dynamic movement.
 
 • Differential integration approach: Due to limitations of the 3D printer in producing small and precise mechanical tolerances, a LEGO differential system was adopted and successfully integrated into the drivetrain for reliable and smooth operation.
 
 • System integration validation: Continuous testing ensured compatibility between LEGO mechanical elements, 3D-printed parts, and the Raspberry Pi-based control system, improving overall system reliability and assembly efficiency.

## **🎯Performance Analysis**





## **📊Engineering Calculations & Performance Validation**


## **📁Complete Manufacturing File Repository**
#### **3D Printing Files & Assembly Specifications**
| Component  | Quantity | Description | CAD Photo Preview |
|-----------|-----------|-------------|-------------------|
| **Main Chassis** | 1 | <img src="CAD_design_base_1.jpg" width="100"><img src="CAD_design_base_2.jpg" width="100"> | Primary structure with integrated mounting system |
| **LEGO 4-Gear Differential**  | 1 | <img src="CAD_design_4_gear_mini_differential_1.jpg" width="100"><img src="CAD_design_4_gear_mini_differential_2.jpg" width="100"> | A LEGO differential is a drivetrain component that distributes torque between the left and right wheels, allowing them to rotate at different speeds during turns for smooth and stable cornering.|
| **Bumper** | 2 |  A front bumper is a structural protective component mounted on the front of the robot, designed to absorb minor impacts and protect internal systems while maintaining clearance for the steering mechanism, and it also serves as a mounting point for LED headlights | <img width="556" height="422" alt="Снимок экрана 2026-04-16 015010" src="https://github.com/user-attachments/assets/1a684ae9-2750-41ef-a5d2-e526f7f97032" /> |
| **Back right wheel fender** |   |  |
| **Back left wheel fender** |  |  |
| **Front left wheel fender** | [`design_spur_25_gear.3mf`](design_spur_25_gear.3mf) | 1 | <img src="CAD_design_spur_25_gear_1.jpg" width="100"><img src="CAD_design_spur_25_gear_2.jpg" width="100"> | 25-tooth torque transmission gear |
| **Front right wheel fender** | [`design_spur_26_gear.3mf`](design_spur_26_gear.3mf) | 1 | <img src="CAD_design_spur_26_gear_1.jpg" width="100"><img src="CAD_design_spur_26_gear_2.jpg" width="100"> | 26-tooth motor output gear |
| **Disk for wheel** | [`design_bevel_12_gear.3mf`](design_bevel_12_gear.3mf) | 4 |  | <img width="505" height="339" alt="Снимок экрана 2026-04-16 120709" src="https://github.com/user-attachments/assets/e118a329-f708-470c-b00f-0f14c5747433" />  |
| **Servo Gear** | [`design_motor_lid.3mf`](design_motor_lid.3mf) | 1 |   | <img width="442" height="446" alt="Снимок экрана 2026-04-16 113454" src="https://github.com/user-attachments/assets/c9bd2d08-e307-4eea-8f5d-15806db6785b" /> |
| **Left holder** | [`design_back_rim_long.3mf`](design_back_rim_long.3mf) | 1 | <img src="CAD_design_back_rim_long.jpg" width="100"> | Extended for right side, connecting farther from the gear |
| **Right holder** | [`design_back_rim_short.3mf`](design_back_rim_short.3mf) | 1 | <img src="CAD_design_back_rim_short.jpg" width="100"> | Shorter for left side, connecting closer to the gear |
| **Lidar holder** | [`design_front_top_cover.3mf`](design_front_top_cover.3mf) | 1 | <img src="CAD_design_front_top_cover_1.jpg" width="100"><img src="CAD_design_front_top_cover_2.jpg" width="100"> | Electronics protection cover |
| **Lower left body panel** | [`design_front_bottom_cover.3mf`](design_front_bottom_cover.3mf) | 1 |  | <img width="501" height="468" alt="Снимок экрана 2026-04-16 140342" src="https://github.com/user-attachments/assets/cc8de552-ae55-481c-b917-31fe9651449e" /> |
| **Lower right body panel** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 | <img src="CAD_design_button_cap_1.jpg" width="100"><img src="CAD_design_button_cap_2.jpg" width="100"> | Start button interface |
| **Upper right body panel** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  |  <img width="577" height="441" alt="Снимок экрана 2026-04-16 135838" src="https://github.com/user-attachments/assets/bdb19c56-4f39-488e-bd08-6972e738974a" />  |
| **Upper left body panel** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |   |  <img width="488" height="497" alt="Снимок экрана 2026-04-16 140112" src="https://github.com/user-attachments/assets/e2fa7855-ffcc-46fe-a3d2-e4ea9cf8ce7f" />  |
| **Motor holder** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  | <img width="476" height="185" alt="Снимок экрана 2026-04-16 113226" src="https://github.com/user-attachments/assets/8a2ecd13-bc6b-4f54-bf51-e770bfbf5672" /> |
| **Raspberry upper holder** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |   | <img width="631" height="434" alt="Снимок экрана 2026-04-16 140928" src="https://github.com/user-attachments/assets/096a85af-7417-44d8-819f-6460d478c959" />  |
| **Raspberry lower holder** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  | <img width="729" height="512" alt="Снимок экрана 2026-04-16 113956" src="https://github.com/user-attachments/assets/c8061646-2289-4a14-b08a-15e4aa7d81bc" />  |
| **Swich 2 Axis** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  | <img width="624" height="528" alt="Снимок экрана 2026-04-16 141304" src="https://github.com/user-attachments/assets/ea85fff0-97f6-46ad-9a5f-e77436cfd11d" /> |
| **Wheel 45 degree Rotator** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  |  <img width="627" height="456" alt="Снимок экрана 2026-04-16 120034" src="https://github.com/user-attachments/assets/dd7cd1a3-0e75-4916-a396-5912854f5a8e" /> |
| **180 degree gear** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  | <img width="729" height="441" alt="Снимок экрана 2026-04-16 113746" src="https://github.com/user-attachments/assets/2abac45d-b16f-4f36-b3f8-9a46610f2776" /> |
| **Wheel holder left** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  | <img width="727" height="453" alt="Снимок экрана 2026-04-16 135411" src="https://github.com/user-attachments/assets/58fa46c3-0bb7-4486-9d35-7389be6198da" /> |
| **Wheel holder right** | [`design_button_cap.3mf`](design_button_cap.3mf) | 1 |  |  <img width="690" height="435" alt="Снимок экрана 2026-04-16 135701" src="https://github.com/user-attachments/assets/2e77490d-b71c-4dbb-a058-054d39711b0a" />  |
