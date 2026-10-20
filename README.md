

<div align="center">
  <h1>🤖 Hi, I'm Julien Dubuc!</h1>
  <p><i>Engineering Student @ SeaTech | Mechatronics, Robotics & Embedded AI</i></p>

  <a href="https://julien-dubuc.github.io/portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Live_Portfolio-Check_it_Out-00D4FF?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/julien-dubuc14" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</div>

---

### 👨‍💻 About Me
I am an engineering student at **SeaTech**, passionate about the intersection of software and hardware. I thrive on complex challenges. From developing Python algorithms for AI to designing embedded C/ROS systems, I am driven by the process of turning a complex idea into a functional, intelligent machine.

- 🔭 **Current Focus:** Mechatronics, Robotics, and Embedded AI.
- 🎯 **Looking for:** Internships or opportunities to apply my skills in real-world environments.

---

### 🚀 Engineering Projects

#### 🦾 Sensorized Compliant Gripper (https://github.com/julien-dubuc/Compliant-Gripper-Etextiles)

<video src="https://github.com/user-attachments/assets/0fb9064f-4c5a-48e0-bed2-30afb5b9e9d7" width="600" controls="controls"></video>

* **Tech Stack:** `Soft Robotics`, `CAD (Onshape)`, `3D Printing`, `SimScale (FEA)`, `Arduino`, `E-textiles`
* 🎯 **Challenge:** Traditional industrial grippers struggle with fragile objects due to their rigidity and high energy consumption. Previous soft gripper designs in the lab used springs, which caused violent releases and wasted energy.
* 🛠️ **Solution:** Designed and 3D-printed a low-cost, soft gripper. Developed a passive self-locking system using a worm screw to allow controlled release. Optimized the finger geometry to fix mechanical buckling using SimScale FEA



. Characterized and integrated embroidered e-textile sensors on the fingers to provide tactile feedback.
* 📈 **Impact:** Achieved safe grasping and held objects without consuming continuous power (zero watts). Reached a 100% detection success rate on fragile objects and reduced the manufacturing cost to 1.35 € with only 2 printed parts. The system was successfully validated using an OptiTrack motion capture system and integrated onto a robotic arm.
#### 🌊 AI-Powered 3D Tracking for ROV (https://github.com/Projet-BlueROV-Seatech)

<video src="https://github.com/user-attachments/assets/732c6a01-8a03-44a0-8646-d0f07517a89c" width="600" controls="controls"></video>

* **Tech Stack:** `Python`, `Computer Vision (OpenCV)`, `YOLOv8`, `Qualisys
* 🎯 **Challenge:** Develop a low-cost, markerless alternative to expensive industrial motion capture systems (Qualisys) to track the 3D trajectory of an underwater robot in a test basin.
* 🛠️ **Solution:** Built a complete Python pipeline. Trained a YOLOv8 model for robust object detection in a distorted aquatic environment. Implemented multi-camera calibration (OpenCV, ArUco) and a stereoscopic 3D triangulation algorithm using the least squares method.
* 📈 **Impact:** Achieved a tracking precision of ~4.7 cm at a 3-meter distance, validated against the Qualisys ground truth. The project was highly praised by the COSMER lab jury for its technical viability and commercial potential.

#### 🏎️ TurtleBot Autonomous Navigation (https://github.com/julien-dubuc/TurtleBot_Autonomous_Navigation)

<video src="https://github.com/user-attachments/assets/dbb1b983-a50e-456b-9680-403d112be37f" width="600" controls="controls"></video>

* **Tech Stack:** `ROS`, `Python`, `Gazebo`
* 🎯 **Challenge:** Enable a TurtleBot to navigate autonomously in an unknown environment while safely avoiding obstacles.
* 🛠️ **Solution:** Developed a navigation stack using ROS and Python within a Gazebo simulation. Implemented a robust State Machine processing Lidar data for dynamic path planning and managing physical collisions via bumper sensors.
* 📈 **Impact:** Achieved reliable autonomous movement and collision avoidance, demonstrating strong proficiency in standard robotics frameworks.

#### 🕹️ Autonomous Mobile Robot Control (https://github.com/julien-dubuc/Embedded-Autonomous-Robot)

<video src="https://github.com/user-attachments/assets/f55e6316-31b7-4a02-b46a-e93c1cc03174" width="600" controls="controls"></video>

* **Tech Stack:** `C`, `MPLAB X`, `Microchip/ADC`
* 🎯 **Challenge:** Build a low-level, collision-free control system for a physical autonomous mobile robot.
* 🛠️ **Solution:** Programmed an embedded control architecture in C using MPLAB X. Configured Microchip peripherals (ADC, Timers) and managed hardware interrupts. Designed an obstacle avoidance algorithm aggregating data from 5 telemeter sensors.
* 📈 **Impact:** Delivered a fully functional embedded system capable of real-time sensor processing and autonomous spatial awareness.

#### ⚙️ Rigid Pendulum Control (https://github.com/julien-dubuc/commande)

<video src="https://github.com/user-attachments/assets/fc95e4ed-1b68-4a0f-87b7-0e531555d385" width="600" controls="controls"></video>

* **Tech Stack:** `MATLAB`, `Simulink`, `PID`, `HIL`, `System Identification`
* 🎯 **Challenge:** Control a rigid pendulum on a horizontal motor shaft, overcoming non-linear gravity loads, dry friction, and hardware calibration discrepancies.
* 🛠️ **Solution:** Modelled the DC motor in Simulink and designed controllers in simulation. Identified real-world parameters (friction, inertia, gravity torque) on the bench, then implemented and compared a position PID with a two-loop tachometric feedback on the real hardware. *(Co-developed with Timm Claverie)*.
* 📈 **Impact:** While a standard PID failed to stabilize the physical system, the tachometric feedback successfully reached the 180° setpoint in 0.33 s with slight overshoot. Successfully quantified real-world discrepancies (e.g., 29% speed drop due to friction).

#### 📊 Financial Analysis & Site Monitoring (https://github.com/julien-dubuc/Logeo-Seine-Internship


<video src="https://github.com/user-attachments/assets/a143fd21-5afe-4d2a-82f7-b89a90d5c784" width="600" controls="controls"></video>

* **Tech Stack:** `Excel`, `Financial Analysis`, `Site Monitoring`, `Snag Tracking`, `Handover Logistics`
* 🎯 **Challenge:** Give the Technical Department of a social housing provider a synthetic, comparable view of the costs of its recent operations (new build, renovation, acquisition/upgrade), while supporting day-to-day site monitoring through to handover to the letting agencies.
* 🛠️ **Solution:** Built Excel dashboards and per-work-package charts (contract cost, amendments, cost per unit) across three operation types, plus summary tables covering all recent operations. Took part in site meetings (OPC, architect, trades), tracked snag resolution, and managed key labelling and access badges.
* 📈 **Impact:** Delivered summary tables enabling project-to-project cost comparison and better cost forecasting for future operations; secured reliable preparation of handovers to the agencies, with autonomous on-site interventions (opening units, coordinating contractors, resolving an unexpected issue).

#### 🚗 Vehicle Dynamics Simulator (https://github.com/julien-dubuc/Vehicle-Dynamics-Simulator)

<video src="https://github.com/user-attachments/assets/805dbea0-651d-4d2a-835d-6aba53c30638" width="600" controls="controls"></video>

* **Tech Stack:** `MATLAB`, `App Designer (IHM)`
* 🎯 **Challenge:** Create a tool to predict and analyze the complex physical behavior of various vehicles under different driving conditions.
* 🛠️ **Solution:** Designed a custom simulation application using MATLAB App Designer. Implemented mathematical physics models to calculate trajectory, lateral acceleration, yaw rate, and drift across multiple scenarios (dry, wet, ice).
* 📈 **Impact:** Provided a scalable UI to simulate rollover risks and handling characteristics for city cars, SUVs, and hovercrafts.

#### 🧠 AI for Hexapawn (Reinforcement Learning) (https://github.com/julien-dubuc/Hexapawn-Reinforcement-Learning)

<video src="https://github.com/user-attachments/assets/7300855c-6a6c-47d1-8aae-f0546701b2e7" width="600" controls="controls"></video>

* **Tech Stack:** `Python`, `Machine Learning`
* 🎯 **Challenge:** Build an AI capable of mastering a board game from scratch without pre-programmed strategies.
* 🛠️ **Solution:** Coded a Hexapawn game engine in Python and implemented a reinforcement learning algorithm. The AI systematically recorded winning states and pruned losing branches over multiple iterations.
* 📈 **Impact:** Achieved a model capable of perfect play. Successfully scaled the board size and generated a complete game tree for instant win-state calculation.

> 🌐 *Explore my other projects (Image Processing, Breakwaters Simulation, Business Strategy) directly on my [Interactive Portfolio](https://julien-dubuc.github.io/portfolio/).*

---

### 🛠️ Technical Skills

| Category | Technologies | Applications |
| :--- | :--- | :--- |
| **Robotics & Simulation** | `ROS`, `Gazebo`, `MATLAB` | Autonomous navigation, system dynamics modeling. |
| **Embedded & Core Logic** | `C`, `C++`, `Python`, `Java` | Microcontroller programming, Reinforcement Learning, Computer Vision. |
| **Design & Mechanics** | `SolidWorks`, `AutoCAD` | 3D modeling, mechanical parts assemblies. |
| **Project & Docs** | `LaTeX`, `Gantt`, `Google Workspace` | Scientific reporting, team leadership, timeline management. |

<br>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/ROS-22304E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS" />
  <img src="https://img.shields.io/badge/MATLAB-e26b0a?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB" />
  <img src="https://img.shields.io/badge/SolidWorks-E32227?style=for-the-badge&logo=solidworks&logoColor=white" alt="SolidWorks" />
</p>

---

### 📈 GitHub Activity

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=julien-dubuc&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=julien-dubuc&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
</div>
