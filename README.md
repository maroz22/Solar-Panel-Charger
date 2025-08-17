# Solar Battery Charger

A regulated **solar battery charger circuit** designed to charge a **6V/4.5Ah battery** using a **12V solar panel** and an **LM317 voltage regulator**.  
The project includes **over-voltage protection** and **reverse current protection**, tested through simulation and hardware implementation.  

---

## ✨ Features
- ✅ Regulated 6V output for safe charging  
- ✅ Over-voltage cutoff at 6.8V  
- ✅ Reverse current protection with diodes  
- ✅ Simulated using **Proteus** and **MATLAB**  
- ✅ Tested under varying irradiance and temperature
- 
## 🛠️ Components Used
- **Solar Panel (12V)** – DC power source  
- **LM317 Regulator** – Adjustable output, set to 6V  
- **Zener Diode (6.8V)** – Over-voltage protection  
- **1N4007 Diodes** – Reverse current protection  
- **BC548 Transistor** – Cutoff switch for safety  
- **Rechargeable Battery (6V/4.5Ah)** – Energy storage
- 
## 📊 Simulation Highlights
- **Higher irradiance → more charging current (Isc)**  
- **Higher temperature → lower open-circuit voltage (Voc)**  
- Circuit maintains **stable 6V** across the battery  
- Over-voltage cutoff triggers at **6.8V**
- 
##📌 Future Improvements
- Implement MPPT (Maximum Power Point Tracking)
- Improve efficiency with MOSFET-based regulators
- Extend design for higher-capacity batteries
- 
##👨‍💻 Authors
- Marwan Elsayed Ali
-Ali Emad
-Ahmed Reda
