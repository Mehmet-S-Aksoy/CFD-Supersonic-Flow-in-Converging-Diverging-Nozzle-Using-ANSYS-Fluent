# CFD-Supersonic-Flow-in-Converging-Diverging-Nozzle-Using-ANSYS-Fluent

This repository simulates supersonic flow in a converging-diverging nozzle using ANSYS Fluent, focusing on calculating the exit pressure, Mach number, and temperature distribution to achieve supersonic flow at the nozzle exit. Results are validated with hand calculations.


## Key Features:

- Simulation of **supersonic flow** through a **converging-diverging nozzle**.
- Calculations for **exit pressure**, **Mach number**, and **static pressure/temperature**.
- Focus on **supersonic flow conditions** and the design of a nozzle to achieve these conditions.
- 2D **planar space** geometry setup for the nozzle, with fluid flow initialization and boundary conditions.
- Results including **Mach number contours**, **static pressure/temperature distributions**, and **xy plots** of velocity and pressure.


## Overview:

This simulation models the flow of gas through a **converging-diverging nozzle**, aiming to achieve **supersonic flow** at the nozzle exit. The flow accelerates through the converging section, reaches **Mach 1** at the throat, and then continues to accelerate supersonically in the diverging section. The **exit pressure** is calculated to maintain this supersonic flow.


### Key Calculations:

- **Exit Pressure Calculation**: Determined through isentropic flow tables for supersonic conditions.
- **Mach Number**: Increased through the converging part of the nozzle and continues supersonically in the diverging part.
- **Temperature and Pressure**: Calculated at various stages along the nozzle.


### Assumptions:

- **Ideal Gas** model for air with **variable density**.
- **Isentropic flow** assumptions for both subsonic and supersonic conditions.
- **Energy equation** included for compressible flow.
- **Inviscid flow** used for simplicity.


## Pre-Analysis:

1. **Mathematical Model**: The nozzle geometry and flow conditions are analyzed using isentropic relations and area ratios to calculate the **exit pressure** for supersonic flow.
2. **Hand Calculations**: Calculations for pressure and temperature ratios at various points are made based on the flow conditions and area ratios.
3. **Boundary Conditions**: Static pressures, temperatures, and flow rates are defined for the **inlet**, **outlet**, and **walls** of the nozzle.


## Files:

The **ANSYS Fluent** simulation file for this analysis is available for download via Google Drive:

https://drive.google.com/file/d/1N2wBA6I0Lu2WE2jN6X7jK2ROFDLklpbr/view?usp=sharing


## Conclusion:

This repository demonstrates the simulation of **supersonic flow** in a **converging-diverging nozzle**. The results provide insights into the **pressure** and **Mach number distribution** across the nozzle, with detailed analysis for achieving **supersonic exit flow**. The nozzle design and boundary conditions are verified to ensure the desired flow characteristics.


## Contact:

- LinkedIn: https://www.linkedin.com/in/mehmet-sabri-aksoy/
- Email: maksoy@uab.edu
