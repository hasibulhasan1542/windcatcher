This repository contains the simulation files for a **two-sided windcatcher**, developed as part of a validation study in Computational Fluid Dynamics (CFD). The project focuses on assessing the ventilation performance and aerodynamic efficiency of traditional passive cooling architecture using modern numerical methods.

The project is built using **OpenFOAM**, the industry-standard open-source toolbox for fluid flow simulation.

**Key Features:**
*   **OpenFOAM Case Structure:** Includes the standard directory setup:
    *   `0/`: Initial and boundary conditions (pressure, velocity, etc.).
    *   `constant/`: Physical properties, turbulence modeling, and mesh data.
    *   `system/`: Simulation control settings, discretization schemes, and solver configurations.
    *   **Time Directories:** (e.g., `10`, `20`, ..., `100`) contains solved field data at specific intervals.
*   **Validation-Focused:** Specifically configured to validate numerical results against experimental data or established benchmarks for windcatcher performance.
*   **Visualization Ready:** Includes a `p.FOAM` file, allowing users to immediately import the simulation results into **ParaView** for post-processing and analysis.

### **Technical Details:**
*   **Primary Tool:** OpenFOAM (Open-source CFD)
*   **Language:** C++ (Solver and dictionary configurations)
*   **Application:** Natural ventilation, passive cooling, and building aerodynamics.

### **Who Is This For?**
This repository is a valuable resource for:
*   **CFD Engineers:** Looking for a pre-configured OpenFOAM case for ventilation studies.
*   **Architects/Researchers:** Interested in the performance of sustainable, wind-driven cooling systems.
*   **Students:** Learning how to set up and validate complex airflow simulations in OpenFOAM.
