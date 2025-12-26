# Smart Patient Monitoring & Environmental Safety System (LabVIEW)

## 📌 Project Overview
This project presents the design and implementation of an integrated **Patient Monitoring**
and **Environmental Safety System** using **National Instruments LabVIEW**.

The system simulates a complete hospital room environment by combining biomedical
signal processing with safety-critical environmental control logic.

---

## 🧠 System Architecture
The project is divided into two main modules:

### 🩺 Module 1: Patient Monitoring System
- ECG signal simulation and heart rate extraction
- Galvanic Skin Response (GSR) stress analysis
- Stress-dependent body temperature modeling
- BMI and BMR metabolic calculations
- Nurse calling system with latch-based alarm logic

### 🔥 Module 2: Environmental Safety (Firestop System)
- Smoke and temperature fire detection
- CO₂ discharge simulation with safety interlock
- Door locking logic during fire events
- HVAC system with manual and automatic modes
- Temperature feedback control loop

---

## ⚙️ Key Features
- Fully software-based biomedical signal simulation
- Frequency-domain heart rate extraction
- GSR-based stress classification
- Persistent nurse calling alarm using SR latch
- Fire safety system with fail-safe behavior
- HVAC control with automatic temperature regulation

---

## 🚨 Nurse Calling System
The nurse calling system is designed using an **SR latch** to ensure alarm persistence.
An alarm is triggered by:
- Manual nurse call button
- Abnormal body temperature
- Abnormal heart rate
- High stress condition (GSR > threshold)

Once triggered, the alarm remains active until manually reset by medical staff.

---

## 🔥 Fire Safety Logic
- Fire alarm activates if **smoke OR temperature** exceeds safe limits
- CO₂ discharge requires manual confirmation that no one is inside the room
- HVAC system automatically shuts down during fire conditions
- Door locking mechanism prevents unsafe entry

---

## 📁 Project Structure
- labview_code/ → LabVIEW VI files
- report/ → Project report (PDF)
- images/ → Front panel & block diagram screenshots
- Readme


---

## 🧪 Verification
All subsystems were validated through LabVIEW simulation.
Results demonstrate correct alarm behavior, robust signal processing,
and safe environmental control under abnormal conditions.

---

## 👨‍💻 Team Members
- Elsayed Ashraf Ramadan Bakry  
- Mohamed Ayman Elsayegh  
- Ahmed Basem Abdelsalam AboKela  

---

## 🏫 Academic Information
**Department:** Electrical Communications and Electronics Engineering  
**University:** Alexandria University  
**Date:** 4 December 2025  

---

## 📚 References
- National Instruments – LabVIEW Core 1 Manual  
- Swain et al., *Patient Monitoring System Using LabVIEW*  
- Webster, *Medical Instrumentation: Application and Design*
