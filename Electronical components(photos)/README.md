# **Electronics**
This folder contains supplementary materials for Team CyberBots’s WRO 2026 Future Engineers robot, including component images, technical documentation, development resources and faced problems during development.

## **Movement & Power Components**
| Components | Image | Description |
|------------|-------|------------|
|      Battery 7.4V      |  ![Battary 7 4 v](https://github.com/user-attachments/assets/a3a33397-1ca3-4cc4-b1ab-a9e5a3964dbe) |     Lithium polymer battery pack / custom 2S LiPo battery – 7.4V, 3000mAh, Charge 0.5C, Discharge 1C, Size 13×42.5×98 mm, Weight ~108 g.       |
|       yellow toymotor dims     |  ![yellow_toymotor_dims](https://github.com/user-attachments/assets/41cab360-41f7-4b28-86ab-22f1f83db447) |Yellow DC 3V–6V Gear Motor TT for Intelligent Car / Robot Wheels – Voltage 3–6V, No-load current 160–240 mA, No-load speed 130–290 rpm, Gear ratio 1:48, Single axis.           |
|       mg996r v17     |    ![mg996r v17](https://github.com/user-attachments/assets/93aa6d62-c5ba-42ee-b0fb-3a9695d8cc29) |      MG996R V17 Servo Motor – High torque, Digital, Rotation ~180°, Operating voltage 4.8–7.2 V, Speed 0.17 s/60° (6 V), Metal gears, Standard size.      |
|      HW-411      |   ![HW-411](https://github.com/user-attachments/assets/de25cf16-1348-4981-8cdb-a0039846c536) |      HW‑411 DC‑DC Buck Converter Module – Adjustable step‑down voltage regulator (LM2596S), Input 4–40 V, Output 1.25–35 V (adjustable), Max current ≈3 A, High efficiency (~92%), Overheat and short‑circuit protectio      |

## **Electronic Components**
| Components | Image | Description |
|------------|-------|------------|
|      USB 8MP 4K 60fps Camera      |    ![Cam V2 1 v1](https://github.com/user-attachments/assets/6ecaaff7-5ee0-459c-8b8a-232d9993058d) |      USB 8MP 4K 60fps Camera with IMX415 Sensor and Microphone, Day & Night Wide-Angle Surveillance HD CCTV System      |
|       DRV8833     |    ![DRV8833](https://github.com/user-attachments/assets/f2e9be73-154f-4143-b417-316e2a65708c)  |       DRV8833 Dual DC Motor Driver Module – Dual H-bridge motor driver, operating voltage 2.7–10.8 V, controls 2 DC motors, output current 1.5 A per channel, supports PWM control, built-in protection circuits.     |
|       PCA9685 v18     |     ![PCA9685 v18](https://github.com/user-attachments/assets/76a841d0-7075-4609-adf3-c341e1f91f2f)  |       PCA9685 16-Channel PWM Servo Driver Module (I2C) – Controls up to 16 servos, 12-bit PWM resolution (4096 steps), communication via I2C (SDA/SCL), logic voltage 3.3 V / 5 V compatible, adjustable PWM frequency ≈24–1526 Hz, supports chaining up to 62 modules.     |
|     RASPBERRY_PI5_1       |   ![RASPBERRY_PI5_1](https://github.com/user-attachments/assets/06984689-b434-4728-9a16-8c8e57939f1b)  |       Raspberry Pi 5 (1GB) – Quad-core 2.4 GHz Cortex-A76 CPU, 1 GB LPDDR4X RAM, VideoCore VII GPU, Wi-Fi (802.11ac) + Bluetooth 5.0, Gigabit Ethernet, 2× USB 3.0 + 2× USB 2.0, dual 4K HDMI output, PCIe 2.0, 40-pin GPIO, power 5 V / 5 A via USB-C.     |
|        RPLIDAR    |   ![RPLIDAR](https://github.com/user-attachments/assets/1cf18d49-74b6-41e7-a085-5e194217d2f8)  |      Xiaomi LiDAR Sensor (e.g., TOF / 360°)* – Long‑range distance measurement up to ~10–12 m, 360° scanning, high‑precision time‑of‑flight (ToF) / laser ranging, fast sampling, low‑power, interface UART / I2C / SPI (зависит от модели), used for SLAM and robot navigation.    |
|      SS12D10_90_Degree     |    ![SS12D10_90_Degree](https://github.com/user-attachments/assets/45f4b953-98b4-4426-b274-ee7f9f6c7a1c) |      SS12D10 90° Slide Switch (DIP) – SPDT slide switch, 90° actuation, DIP package, rated current ≈0.3–1 A, voltage ≈12–24 V DC, used for power/control switching in circuits.      |

## **Challenges and Problems Faced During Development**

**Component specifications (especially LiDAR)**

Another challenge was finding reliable technical specifications for some components, especially the LiDAR sensor. It was difficult to find complete official datasheets in PDF format, which created uncertainty during integration and system planning. Because of this, we collected and compared specifications from different sellers and technical sources and used them as reference values.

**Limited internal space and Raspberry Pi placement**

Initially, the Raspberry Pi was installed at the rear part of the robot, but this placement interfered with the LiDAR operation and reduced its effective sensing performance. Moving the Raspberry Pi to a lower position required reorganizing multiple components inside a very limited internal space. It was difficult to fit all electronics correctly, but after several hours of adjustments, we successfully arranged all components inside the chassis.

**Electronic architecture and GPIO planning**

Designing the electronic architecture and wiring layout was also challenging. Several modules had to be connected to the Raspberry Pi, and the limited number of available GPIO pins required careful planning. We studied the pin configuration in detail to ensure correct communication between all components and stable system operation.

## **Notes**
