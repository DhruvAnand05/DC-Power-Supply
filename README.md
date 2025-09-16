# ⚡ DC Power Supply – ELECENG 2EI4 (McMaster University)

## 📖 Project Overview  
This project involved the **design, simulation, and implementation** of a DC Power Supply for McMaster University’s **ELECENG 2EI4** course.  
The supply converts a **120V RMS, 1kHz AC input** into a regulated **3V ± 0.1V DC output** at **10 mA**.  

Key stages included:  
- Transformer design (calculated, not physically implemented)  
- Center-Tapped Full-Wave Rectifier  
- RC Filter for ripple reduction  
- Verification through both simulation and physical testing  

---

## 🛠️ Tools & Components  
- **OrCAD PSpice** – Circuit simulation & waveform analysis  
- **Analog Discovery 3 (AD3)** – Hardware measurements  
- **WaveForms Software** – Capturing voltage and current data  
- **1N4148 Diodes**, **100µF Capacitor**, **300Ω–330Ω Resistor**  

---

## 🔍 Design Details  
- **Transformer:** 23:1 ratio (theoretical, not implemented)  
- **Rectifier:** Center-Tapped Full-Wave topology (2 × 1N4148 diodes)  
- **Filter:** RC filter (100µF capacitor + 300Ω load resistor)  
- **Regulator:** Not implemented (design met specs without it)  

---

## 📊 Simulation Results (PSpice)  
- Output Voltage: **2.99V – 3.03V**  
- Load Current: **9.95mA – 10.12mA**  
- Ripple Voltage: **±0.02V**  
✅ Fully within project specifications  

---

## 🔬 Physical Implementation & Testing  
- Built on a breadboard with a **330Ω load resistor** (permitted substitution)  
- Verified using **Analog Discovery 3 + WaveForms**  
- Measured Voltage: **3.0V ± 0.09V**  
- Measured Current: **8.8mA – 9.4mA** (adjusted for 330Ω resistor)  

Discrepancies between simulation and physical results were attributed to:  
- Component tolerances (resistor, capacitor, diodes)  
- Breadboard/wire resistance  
- Measurement tolerances of the AD3  

---

## 🚀 Key Learnings  
- Designing reliable rectifier + filter circuits under tight voltage ripple requirements  
- Understanding the **gap between simulation and hardware**  
- Hands-on experience with **PSpice simulation** and **AD3/WaveForms testing**  
- Impact of real-world tolerances and component limitations  

---

## 📚 References  
1. Elprocus – *Center-Tapped Full-Wave Rectifier*  
2. Diodes Inc. – *1N4148 Datasheet*  
3. Simon Xu – *RC, RL, or RLC Filters?*  
4. Physics and Radio Electronics – *Full-Wave Rectifier*  

---

✍️ **Author:** Dhruv Anand  
📅 **Date:** February 2025  
