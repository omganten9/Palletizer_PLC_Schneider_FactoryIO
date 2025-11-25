# Palletizer_PLC_Schneider_FactoryIO
# Box Sorting and Palletizing System Using PLC and Factory I/O

This project simulates a **box sorting and palletizing system** using a **Schneider TM221CE16R PLC** integrated with **Factory I/O**.  
The system sorts boxes by height using pneumatic pushers and arranges the smallest boxes on a pallet with a palletizer machine.

---

## 🧩 Overview
This project demonstrates how PLCs can automate material handling and packaging.  
It combines **conveyor-based sorting**, **pneumatic actuation**, and **palletizing logic** in a virtual factory environment.

---

## ⚙️ Hardware Configuration
- **PLC:** Schneider TM221CE16R  
- **Inputs:** 9 digital, 2 analog  
- **Outputs:** 7 relay (2A each)  
- **Ports:** 1 Ethernet, 1 Serial (Modbus)  
- **Software:** EcoStruxure Machine Expert, Factory I/O  

![PLC Configuration](/mnt/data/a3fc2401-4116-48a5-b2e2-c893e52c39b0.png)

---

## 🏗 System Description
- Boxes of different heights move along a **conveyor belt**.  
- **Photoelectric sensors** detect the box height.  
- **Pneumatic pushers** separate boxes based on size.  
- The **smallest boxes** are transferred to a **palletizer**, which arranges them in stacks.  
- Logic control and sequencing are implemented using **Ladder Diagram (LD)** in the PLC.  

---

## 🧠 Features
- Real-time PLC–Factory I/O integration  
- Modular control for conveyor, pusher, and palletizer subsystems  
- Fully documented wiring, ladder logic, and process flow  
- Includes simulation video and full project report  

---

## 📁 Repository Structure
