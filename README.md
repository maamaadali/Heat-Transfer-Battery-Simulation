# Heat-Transfer-Battery-Simulation
A MATLAB project for simulating transient heat conduction in a cylindrical battery using FDM.
[README.md](https://github.com/user-attachments/files/21706387/README.md)# Heat Transfer Project – Cylindrical Battery Thermal Modeling

## 📌 Overview
This project was developed as the final project for the **Heat Transfer** course at **Sharif University of Technology**, supervised by **Dr. Akbar Shojaei**.

The main objective was to **model and simulate the transient temperature distribution** in a cylindrical battery cell during the discharge phase using the **Finite Difference Method (FDM)**.

Two numerical methods were implemented:
- **Explicit FDM**
- **Crank–Nicolson Method**

A numerical stability analysis was performed to determine the **critical Fourier number (K parameter)**.

---

## 🎯 Key Objectives
- Solve the transient heat conduction equation in **cylindrical coordinates**.
- Implement and compare **Explicit** and **Crank–Nicolson** numerical schemes.
- Perform **empirical stability analysis**.
- Develop the simulation **from scratch** in MATLAB.

---

## 🛠️ Technical Details
- **Programming Language:** MATLAB
- **Numerical Methods:** Explicit FDM, Crank–Nicolson
- **Stability Analysis:** Critical Fourier number evaluation
- **Physical Model:** Radial heat conduction with internal heat generation

---

## 📂 Repository Structure
```
├── Heat-Transfer-Project.rar             # Full project report and MATLAB code
└── README.md                             # Project documentation
```

---

## 📊 Results
- **High agreement** between Explicit and Crank–Nicolson methods for stable time steps.
- Identified **critical stability limit** at K ≈ 0.25.
- Clear temperature rise during discharge phase with radial distribution patterns.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/maamaadali/Heat-Transfer-Battery-Simulation
   ```
2. Open MATLAB and navigate to the project folder.
3. Run `explicit_method.m` or `crank_nicolson.m` to simulate.
4. Use `stability_analysis.m` for stability evaluation.

---

## 📄 Full Report
The detailed **mathematical derivations**, **model assumptions**, and **simulation results** can be found in (https://github.com/maamaadali/Heat-Transfer-Battery-Simulation/blob/main/Heat-Transfer-Project.rar).

---

## 📬 Contact
Feel free to reach out for questions, collaborations, or feedback:
- **Email:** izadiali278@gmail.com
- **LinkedIn:** (www.linkedin.com/in/mohammad-ali-izadi-7a2a15315)

---

**#HeatTransfer #NumericalMethods #MATLAB #FiniteDifference #CrankNicolson #Engineering #Simulation #ThermalManagement #Battery**

