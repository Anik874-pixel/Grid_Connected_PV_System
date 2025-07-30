
Key features:
- **MPPT using P&O algorithm** for maximum solar energy extraction
- **PWM-controlled inverter** for DC-AC conversion
- **PLL for synchronization** with the grid’s frequency and phase
- **LCL filter** for reducing harmonics in output current

---

## 🧠 Technical Highlights

| Component               | Description |
|------------------------|-------------|
| 🔆 **PV Array**         | 47 parallel strings × 10 modules each (Mono plates) |
| ⚡ **Boost Converter**  | Steps up PV voltage to inverter DC link voltage |
| 🔄 **Inverter**         | 2-level VSI controlled via 6 PWM signals |
| 🎯 **MPPT**             | Perturb & Observe algorithm |
| 🌀 **PLL**              | Ensures phase/frequency sync with grid |
| 🔄 **Clarke & Park**    | abc → αβ → dq transformation for better control |
| 🧠 **Current Controller** | Uses PI controllers for managing Id, Iq |
| 🔁 **Simulation Tool** | MATLAB/Simulink |

---

## 🧪 Simulation Results

- Achieved **low THD (~1.41%)** via LCL filter
- Verified **DC Link voltage stability**
- Demonstrated **active/reactive power flow control**
- System performs reliably under dynamic load conditions

---

## 📊 Key Parameters

| Parameter                         | Value           |
|----------------------------------|-----------------|
| System Power                     | 100 kW          |
| Grid Voltage                     | 400 V           |
| PV Open Circuit Voltage          | 907 V           |
| Filter Inductance                | 500 mH          |
| Filter Capacitance               | 500 µF          |
| Grid Frequency                   | 50 Hz           |
| Switching Frequency              | 10 kHz          |
| DC Link Capacitance              | 3277 µF         |

---

## 📈 Outcomes

- Enhanced power quality and grid support
- Intelligent MPPT control under varying irradiance
- Smooth energy transition between PV system and grid
- Validated using MATLAB/Simulink simulation

---

## 🚀 Future Scope

- Real-time hardware implementation via dSPACE or microcontroller
- Incorporate AI/ML-based MPPT for variable conditions
- Battery integration for hybrid solar-storage systems

---

## 🛠️ Tools & Technologies

- MATLAB / Simulink
- Control Systems
- Power Electronics
- Renewable Energy Systems
- Embedded Control (Theoretical)
- IEEE Standards for Grid Integration

---

## 👨‍💻 Authors

- **Abhishek Yadav** (Roll No. 221230005)  
- **Aniket Kumar** (Roll No. 221230008)  
- **Devesh Chauhan** (Roll No. 221230019)  

🧑‍🏫 Supervisor: Dr. Manoj Kumawat  
📍 Department of Electrical Engineering, NIT Delhi

---

## 📚 References

Included studies on PV modeling, boost converters, MPPT, and grid control strategies from IEEE and academic publications. Full references are available in the project documentation.

---

## 📝 License

This academic project is for learning and demonstration purposes only.

---

## ⭐ GitHub Tip

> “This repository contains the complete modeling and simulation of a grid-connected solar PV system using MATLAB. For recruiters or collaborators, the README provides an overview without exposing confidential files. Full documentation available on request.”

---

