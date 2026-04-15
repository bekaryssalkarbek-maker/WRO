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



 **• Upper enclosure cover interfering with Raspberry Pi connections:**
The top cover of the electronics enclosure, which holds the Raspberry Pi, partially blocked access to several GPIO pin connections. This problem was solved by physically removing a small section of the cover that did not affect the structural integrity or external appearance of the robot, allowing proper cable routing and reliable connections.
