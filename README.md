# MSc-Automotive-Engineering-Portfolio
Collection of MSc Automotive Engineering projects. Focus on EM4HEV, Vehicle Control Systems, CFD and FEM Structural Analysis.

# Automotive Engineering Portfolio

Welcome to my academic portfolio! This repository collects the key technical projects I developed during my MSc in Automotive Engineering at **Politecnico di Torino**.

Here you will find detailed reports and presentations covering three main areas of vehicle engineering: Energy Management, Control Systems, Aerodynamics and Structural Analysis.

## Repository Contents

### 1. HEV Energy Management Systems (EM4HEV)
*Tools used: MATLAB, Dynamic Programming, Quasi-static Modelling*
Development of control strategies for a Series Hybrid Electric Vehicle (HEV) to minimize fuel consumption and battery aging.
* **Rule-Based Control:** Implementation of a deterministic strategy on a quasi-static HEV model tested on WLTP cycles.
* **ECMS (Equivalent Consumption Minimization Strategy):** Real-time optimization algorithm balancing fuel and electrical energy usage (tested on Artemis cycles).
* **Adaptive-ECMS (A-ECMS):** Advanced strategy with SOC feedback control to adapt the equivalence factor to real-world driving conditions (WLTP, Turin Test Cycle).
* **Dynamic Programming (DP):** Global optimization algorithm used to find the theoretical benchmark for fuel economy and battery lifetime extension.

### 2. Vehicle Control & ADAS
*Tools used: MATLAB/Simulink*
* **ACC & LKA Design:** Development of **Adaptive Cruise Control** and **Lane Keeping Assist** systems.
* **Controller Comparison:** Performance analysis of PID vs. Stanley controllers in different driving scenarios to optimize safety and responsiveness.

### 3. Aerodynamics & CFD Analysis
*Tools used: STAR-CCM+, CFD simulation*
* **Alfa Romeo Mito CFD Analysis:** A comprehensive study of the vehicle's aerodynamic performance, focusing on Drag (Cd) and Lift (Cl) coefficients.
* **Rim & Tyre Influence:** Investigation into how rotating wheels and tyre deformation affect the overall vehicle aerodynamics compared to stationary conditions.

### 4. Dynamic EV Charging Routing & Reservation
*Tools used: FESTA Framework, FOT methodology, 4G LTE / 5G network analysis*
* **Design of a V2N service for proactive EV charger discovery and reservation across urban and motorway scenarios.** The architecture follows a TCU → MSP Cloud → CPO pipeline with uplink telemetry every 10–30 s and downlink latency < 100 ms. Three Technical Research Questions (TRQs) are defined and mapped to measurable KPIs: Age of Information (30–60 s), Coverage Probability (99%), and Service Reliability (99%, < 5 s). Communication technology selection justifies 4G LTE as the current standard (99% highway coverage, 30–50 ms latency), with 5G SA (Stand Alone) as the future-proof evolution. Validation follows the FESTA framework with Naturalistic Field Trials and statistical KPI analysis.

### 5. Numerical Modelling & FEM
*Tools used: FEM solvers, Mesh optimization*
* **Structural Component Analysis:** Finite Element Method (FEM) analysis of critical components including:
    * **Engine Rod:** Stress distribution and mesh convergence studies.
    * **Vehicle Frame:** Torsional and bending stiffness evaluation.
    * **T-Joints & Cantilever Beams:** Analysis of welding spacing and structural integrity.

---
### Contact
Feel free to browse the files to see the methodology and results of my work.
Connect with me on [LinkedIn Profile](https://www.linkedin.com/in/tommaso-massone-237baa1ab/) | massonetommaso0@gmail.com
