# ⚙️ Capacitive Torque Sensor

*A precision torque-sensing system using capacitive plate displacement for robotic joint monitoring and electromechanical applications.*

---

## 🧩 Overview

This project focuses on building a **capacitive torque sensor** that measures torque based on changes in capacitance between rotating and stationary plates. It is designed to detect torque in the range of **0–5 Nm** with high sensitivity and structural stability.

Currently, the project is in progress. This repository includes all completed details up to now, including:

- ✅ Finalized enclosure design  
- ✅ PCB layout and design  
- ✅ Component selection and simulation results  
- ✅ First-stage report and documentation

We are now awaiting the arrival of our ordered PCBs for hardware assembly and testing.

---

## 🏗️ System Design Highlights

- **Capacitive Sensing Principle:** Torque induces shaft twist, altering the capacitance between interleaved plates.
- **Capacitance-to-Digital Converter:** Utilizes the high-resolution **PCAP04** for 1000 samples/sec and femtofarad-level precision.
- **MCU:** Chosen microcontroller is **ATmega32U4** with 16 MHz clock, 32 KB Flash, and 2.5 KB SRAM — ideal for register-level interfacing.
- **Dielectric Material:** **FR4 (Glass Epoxy)** selected for its machinability and dielectric stability.
- **Shaft Material:** **Aluminum 6061-T6**, selected through deformation analysis using Ansys simulations.

---

## 🔧 CAD & Simulation Tools

- 🛠️ **SolidWorks:** Complete mechanical modeling and deformation simulation
- 🧪 **Ansys:** FEA analysis for shaft performance under torque
- 🔌 **Altium Designer:** PCB schematic and layout
- ⚙️ **Verilog HDL:** For future digital signal integration

---

## 📦 Repository Includes

- `/Design report` – Project report, analysis, and evaluation tables  
- `PCB/` – Final PCB design files  
- `Enclosure Design/` – SolidWorks files for enclosure and internal structure  

---

## 👥 Contributors

- [Dayananthan.T](https://github.com/Dayananthan2021)  
- [Mathujan.S](https://github.com/)  
- [Pirathishanth.A](https://github.com/pirathi2002)  
- [Jeyasekara.S.P.R](https://github.com/)  
- [De Zoysa.A.S.I](https://github.com/)  
- [Sulojan.R](https://github.com/)  
- [Ananthakumar.T](https://github.com/ThamilezaiAnanthakumar)  
- [Ahilakumaran.T](https://github.com/)  

---

## 🔗 References

- [PCAP04 Datasheet](https://www.icap.se/download/PCap04_Datasheet.pdf)  
- [ATmega32U4 Datasheet](https://www.microchip.com/en-us/product/ATmega32U4)  
- [FR4 Material Properties](https://www.matweb.com/search/datasheet.aspx?matguid=ae92391bc6cf4d82be509b87561bb764)  
- [Ansys Simulation](https://www.ansys.com/products/structures/ansys-mechanical)

---

🚀 **This project bridges mechanical design, capacitive sensing, and embedded systems for real-world torque measurement solutions.**
