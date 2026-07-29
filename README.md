# DC-DC-Boost-Converter

**Duration:** Jan 2025 – Apr 2025
**Domain:** Power Electronics  
**Software:** MATLAB/Simulink 

---

## 📌 Project Overview

This project involves the design and simulation of a **DC-DC Boost Converter** capable of stepping up a low DC input voltage to a higher regulated output voltage. The converter is designed to operate in **Continuous Conduction Mode (CCM)** under normal loading conditions and is further analyzed in **Discontinuous Conduction Mode (DCM)** by varying the load resistance. The project focuses on understanding converter operation, switching behavior, and waveform analysis.

---

## 🎯 Objectives

- Design a DC-DC Boost Converter based on given specifications.
- Step up the input voltage from **7.5 V** to **12.5 V**.
- Analyze converter operation in Continuous Conduction Mode (CCM).
- Demonstrate Discontinuous Conduction Mode (DCM) by increasing load resistance.
- Observe and study the inductor current and switch voltage waveforms.

---

## 📋 Design Specifications

| Parameter | Value |
|-----------|-------|
| Input Voltage | 7.5 V |
| Output Voltage | 12.5 V |
| Switching Frequency | 12 kHz |
| Output Current | 1 A |

---

## 🛠 Components Used

- DC Voltage Source
- MOSFET Switch
- Inductor
- Diode
- Output Capacitor
- Load Resistor
- PWM Generator

---

## ⚙️ Working Principle

- The MOSFET is switched ON and OFF using a PWM signal.
- During the **ON** state, the inductor stores energy while the diode remains reverse-biased.
- During the **OFF** state, the stored energy in the inductor is transferred to the load through the diode, boosting the output voltage above the input voltage.
- By changing the load resistance, the converter transitions from **CCM** to **DCM**, allowing analysis of both operating modes.

---

## 📊 Waveform Analysis

### Continuous Conduction Mode (CCM)

- Inductor current remains continuous throughout the switching cycle.
- Stable boosted output voltage.
- Observed waveforms:
  - Inductor Current
  - Switch Voltage

### Discontinuous Conduction Mode (DCM)

- Achieved by increasing the load resistance.
- Inductor current falls to zero before the next switching cycle.
- Studied the effect of reduced load current on converter performance.

---

## 🧪 Testing & Validation

- Verified output voltage of approximately **12.5 V**.
- Observed inductor current waveform under CCM.
- Measured switch voltage waveform.
- Increased load resistance to successfully demonstrate DCM operation.
- Compared converter performance in both operating modes.

---

## 📈 Outcomes

- Successfully designed a Boost Converter meeting the required specifications.
- Demonstrated voltage step-up from **7.5 V** to **12.5 V**.
- Understood the operating principles of CCM and DCM.
- Gained practical knowledge of PWM switching and waveform analysis.
- Improved understanding of DC-DC power conversion techniques.

---

## 🚀 Future Enhancements

- Closed-loop voltage regulation using a PI controller.
- Hardware implementation using the **TL494 PWM Controller IC**.
- Efficiency analysis under different loading conditions.
- PCB design and hardware prototyping.
- Integration with renewable energy systems such as solar PV.

---

## 👤 Author

**David Kumar**  
B.Tech Electrical Engineering  
IIT Indore

---

## 📜 License

This project is licensed under the **MIT License**.
