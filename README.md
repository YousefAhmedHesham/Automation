# Automation Project  

## Overview  
This project is divided into two phases:  

1. **Phase 1:** Designing and tuning controllers using the PID_Compact block in TIA Portal.  
2. **Phase 2:** Designing a fully functional production line on a simulation platform (e.g., Factory I/O).  

Each phase incorporates simulation, control, and monitoring using Siemens TIA Portal and relevant tools.  

---

## **Phase 1: Controller Design & Tuning**  
- Design and tune controllers using the **PID_Compact block** in **TIA Portal**.  
- Use **Factory I/O** or **MATLAB Simulink** for plant simulation and **SIL/HIL** simulation.  
- Develop an **HMI interface** in **TIA Portal** to monitor system states, desired setpoints, and system faults.  
- Implement **field-related alarms** to detect hardware and sequence faults.
- https://github.com/user-attachments/assets/efc37d0f-3fe7-4d17-b756-4600eaf49466

---

## **Phase 2: Production Line Simulation & Control**  
- Design a fully functioning **production line** on a simulation platform such as **Factory I/O**.  
- Use **Siemens TIA Portal** to control the simulated production line, incorporating studied control functions.  
- Develop a suitable **HMI module** for monitoring system states and sending supervisory control commands.  
- Implement **field-related alarms** to detect hardware and sequence faults.  

### **Production Line Description**  
The production line performs **machining, sorting, and assembly**, transforming raw materials into finished products.  

### **Production Line Components:**  

#### **1. Feeding Unit**  
- The entry point of the production line, responsible for generating random raw materials.  
- Incorporates a **pick & place robot** to position fed parts at the beginning of the line.  

#### **2. Machining Center**  
- Manufactures **lids and bases** from raw materials.  
- Uses an **articulated robot** to place materials into a **CNC machine**.  
- Processing times:  
  - **Lids:** 6 seconds  
  - **Bases:** 3 seconds  
- The finished product is placed at the **exit bay** after machining.  

#### **3. Assembly Unit**  
- Assembles **lids onto bases** or moves items within the system.  
- Uses **positioning bars** to ensure correct alignment of lids and bases.  

---

## **Tools & Technologies**  
- **Siemens TIA Portal** (for PLC programming & HMI development)  
- **Factory I/O** (for production line simulation)  
- **MATLAB Simulink** (for advanced simulation & analysis)  

This project aims to integrate automation, control, and simulation to design a realistic and efficient production system.  
