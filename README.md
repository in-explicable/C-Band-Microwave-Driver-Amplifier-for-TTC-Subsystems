# 📡 C-Band Thin-Film Microwave Driver Amplifier Design and Implementation Using EM-Based Optimization for TTC Subsystems 

## 🔬 Overview

This repository documents the design, simulation, fabrication, and testing of a **C-band (6.4 GHz)** microwave **driver amplifier** for **Telemetry, Tracking, and Command (TTC)** subsystems in **Low Earth Orbit (LEO)** satellites. The project was executed at the **U R Rao Satellite Centre (URSC), Indian Space Research Organisation (ISRO)**.

Designed using **thin-film hybrid microcircuit technology** and optimized through **electromagnetic (EM)-aware methodologies**, this amplifier ensures compact size, space-grade reliability, and unconditional stability.

---

## 🚀 Key Specifications

| Parameter               | Target             | Achieved (Measured)    |
|------------------------|--------------------|-------------------------|
| Frequency              | 6.4 GHz (C-band)   | 6.4 GHz                 |
| Gain (S21)             | 9.6 ± 1 dB         | 12.14 dB                |
| Input Return Loss (S11)| < –6 dB            | –4.81 dB                |
| Output Return Loss (S22)| < –6 dB           | –1.88 dB                |
| Stability Factor (K)   | > 1                | 1.27                    |
| Substrate              | 99.6% Alumina      | Used                    |
| Layout Size            | 14.7 mm × 10.69 mm | Achieved                |

---


## 🧠 Project Highlights

### 🔹 Space-Grade Design
- Used **FLC027-WG GaAs MESFET** and **99.6% high-purity alumina** substrate.
- Designed to withstand thermal cycling, vacuum, and vibration.

### 🔹 EM-Aware Optimization
- Designed and simulated using **AWR Microwave Office** and **AXIEM**.
- EM extraction included during layout stage to reduce parasitic mismatches.

### 🔹 Thin-Film Fabrication
- Vacuum evaporation and sputtering used for high-precision microstrip lines.
- Hermetically packaged in a gold-plated **Kovar** carrier for space environments.

### 🔹 Optimization Techniques
- Applied **Pointer-Hybrid**, **Particle Swarm**, and other optimizers for impedance matching and gain maximization.

---

## 📈 Results Overview

| Stage                  | Gain (S21) | S11       | S22       |
|------------------------|------------|-----------|-----------|
| Initial Schematic      | 4.65 dB    | –1.39 dB  | –5.27 dB  |
| Optimized Schematic    | 12.2 dB    | –18.4 dB  | –13.3 dB  |
| EM Simulation (AXIEM)  | 12.3 dB    | –10.3 dB  | –2.35 dB  |
| Final Fabricated Result| 12.14 dB   | –4.81 dB  | –1.88 dB  |

> ⚠️ Although the return losses slightly missed the target, the gain and stability significantly exceeded expectations — validating the EM-aware design methodology.

---

## 🛠 Tools Used

- **AWR Microwave Office** – Schematic and layout simulation  
- **AXIEM** – EM simulation and parasitic modeling  
- **R&S ZNB40 VNA** – S-parameter measurements  
- **Thin-Film Fabrication Tools** – Vacuum evaporation, sputtering, and photolithography  

---

## 🛰 Applications

- Driver amplifier stage in **LEO satellite TTC systems**
- Suitable between **LNA and mixer (Rx)** or **before PA (Tx)**
- Adaptable to other **C-band RF front-ends** in satellite communications

---

## 🙋 About the Author

**Nivesh S**  
B.Tech. in Electronics and Communication Engineering  
Final Year Project Intern at **URSC, ISRO**

---
