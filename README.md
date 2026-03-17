# 🔋 PEM Fuel Cell Stack Design & Modeling (32 kW)

A comprehensive design and performance analysis of a 32 kW Proton Exchange Membrane (PEM) fuel cell stack for an urban delivery van, combining electrochemical modeling, system-level engineering, and physics-based simulation (AlphaPEM).

---

## 🔬 Project Overview

This project focuses on the **design, dimensioning, and modeling** of a PEM fuel cell stack for automotive applications.

It integrates:
- First-principles electrochemistry  
- Stack-level design  
- Performance analysis  
- Thermal and energy balance  
- Physics-based simulation  

---

## ⚙️ Stack Design

- **Power Output:** 32 kW  
- **Cells:** ~200  
- **Cell Voltage:** 0.65 V  
- **Stack Voltage:** ~130 V  
- **Current Density:** 1.0 A/cm²  
- **Active Area:** 250 cm²  

The design aligns with real-world automotive fuel cell stacks and is suitable for urban delivery applications.

---

## ⚡ Modeling Approach

The fuel cell performance is modeled using:

- **Nernst Equation** → Open-circuit voltage  
- **Butler–Volmer Equation** → Activation losses  
- **Ohmic Losses** → Membrane & contact resistance  
- **Concentration Losses** → Mass transport limitations  

### Stack Voltage Model

V = N (E − η_act − η_ohm − η_conc)

---

## 📊 Results & Analysis

### Performance Trends
- Voltage decreases with increasing current density  
- Power increases, reaches a peak, then declines  
- Efficiency decreases at higher loads  

### Key Results
- **Thermodynamic Efficiency:** ~83% (HHV)  
- **Voltage Efficiency:** ~65%  
- **Overall Efficiency:** ~52%  
- **Heat Generation:** ~29 kW  

---

## 🔁 AlphaPEM Simulation

A physics-based PEM fuel cell model was used to:
- Generate polarization curves  
- Analyze efficiency trends  

> Note: The simulation is not fully optimized but demonstrates how physics-based models can be extended to real-world systems with further calibration.

---

## 🌡️ Thermal & System Analysis

- Hydrogen consumption calculated using Faraday’s law  
- Energy balance shows significant heat rejection (~29 kW)  
- Liquid cooling system selected for thermal management  

---

## 🧠 Key Insights

- Trade-off between efficiency and power density  
- Importance of thermal management in PEMFC systems  
- Material selection impacts durability and performance  
- Battery hybridization is essential for real-world operation  

---

## 📁 Repository Structure
