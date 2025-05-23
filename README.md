# IEEE 14-Bus Power System Analysis Project

## 📘 Introduction

This project was undertaken to gain a comprehensive understanding of power system modeling and simulation. The IEEE 14-bus system was selected due to its simplicity and widespread use as a benchmark in academic and research applications. The system comprises 14 buses, 5 generators, and 11 loads, representing a simplified approximation of the American Electric Power system as of February 1962 :contentReference[oaicite:0]{index=0}.

---

## 🔍 Objectives

The primary objectives of this project were:

- To perform load flow analysis using the IEEE 14-bus system.
- To analyze power losses across different components of the system.
- To study voltage profiles and identify areas requiring voltage control.
- To understand the impact of reactive power compensation on system stability.

---

## 🛠️ Methodology

## 📊 Studies Conducted

### 1. Power Flow Analysis

We performed load flow studies using the **Newton-Raphson method** to determine voltage magnitudes, angles, active power (P), and reactive power (Q) at all buses. The study focused on:

- Identifying the **slack**, **PV**, and **PQ** buses  
- Calculating **bus voltages** and **line power flows**  
- Detecting areas of **under-voltage** or **line overload**

---

### 2. Loss Evaluation

Using the simulation results, we evaluated:

- **Active power losses (P Loss)** and **reactive power losses (Q Loss)** across transmission lines  
- **Transformer losses** at different voltage levels  
- **Zone-wise and area-wise** contribution to total system losses  

This helped in identifying inefficiencies and areas for potential optimization.

---

### 3. Voltage-Level Performance Analysis

The power system was evaluated at various voltage levels (7.8 kV, 13.8 kV, 18 kV, and 69 kV) to determine:

- **Line-specific and transformer-specific losses**  
- **Voltage drops** and system behavior under varying load conditions  

---

### 4. Generation and Load Matching

To ensure a balanced power system, we analyzed:

- Total **active and reactive power generation vs. load demand**  
- **Generator reactive support** and system-level **compensation requirements**

---

### 5. Reactive Power Compensation

The need for **reactive power compensation** was reviewed using:

- **Shunt capacitors** and **shunt reactors**  
- Ensuring **voltage profile** stability and maintaining acceptable **power factor**

---

### 6. Economic Considerations (Cost Analysis)

A basic **economic assessment** was conducted by:

- Comparing generator outputs with **assumed cost units**  
- Gaining insight into **economic dispatch** and cost-efficiency of generation

---

## 📊 Results

Key findings from the analysis include:

- Identification of buses with voltage levels outside the acceptable range, indicating the need for voltage control measures.
- Quantification of active and reactive power losses, highlighting areas where system efficiency can be improved.
- Evaluation of the effectiveness of reactive power compensation in enhancing voltage stability and reducing losses.

Detailed results, including tables and graphs, are provided in the accompanying report.

---

## 📁 Project Files

- `IEEE14BusSystem.pdf`: Detailed system data, simulation results, and power flow reports.
---

## 🧰 Tools and Software Used

- **Neplan AG V555**: For modeling and simulation of the power system.
- **Microsoft Word**: For documentation and reporting.

---

## 📚 References

- IEEE 14-Bus System Overview: [Illinois Center for a Smarter Electric Grid](https://icseg.iti.illinois.edu/ieee-14-bus-system/)
- PSCAD IEEE 14-Bus System Example: [PSCAD Knowledge Base](https://www.pscad.com/knowledge-base/article/26)
- Modeling and Simulation Report: [ResearchGate Publication](https://www.researchgate.net/publication/353452133_IEEE_14_Bus_System_Simulink_Model)

---

## 📞 Contact

**Vraj Prajapti**  
B.E. Electrical Engineering, Class of 2026  
Email: vrajprajapati23042001@gmail.com

---

*Note: All data and resources used in this project are credited to their respective owners and contributors. Special thanks to the open-source communities and forums for providing valuable resources and support.*
