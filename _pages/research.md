---
title: "Research"
permalink: /research/
layout: single
classes: wide
author_profile: true
---

I develop scalable modeling, optimization, and intelligent control frameworks for building and district energy systems. My work focuses on improving energy efficiency, operational flexibility, and electrification readiness of HVAC&R infrastructure through physics-based simulation, predictive control, and techno-economic analysis.

---

## Research Areas

- Building and district energy system modeling  
- Intelligent control and optimization (Model Predictive Control)  
- HVAC&R energy efficiency and system performance  
- Heat pump technologies and system integration  
- Thermal energy storage (TES) optimization  
- Electrification and decarbonization of the built environment  

---

## Selected Federally Funded Projects

### PIRE: Building Decarbonization via AI-empowered District Heat Pump Systems
**Sponsor:** National Science Foundation (NSF PIRE)  
🔗 [Award Details](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2309030)

- Built a physics-based Modelica virtual testbed of district heat pump systems and led analysis of network designs and operating strategies.
- Developed a unified physics-based framework for system-level fault impact analysis in fifth-generation district heating and cooling systems; manuscript under review at *Energy & Buildings*.
- Developed reversible water-to-air heat pump models with compressor-speed control, validated against manufacturer data and physical testbed measurements. The open-source [heatpump-models library](https://github.com/BE-HVACR/heatpump-models) accompanies the American Modelica Conference 2024 Best Student Paper.
- Designed Model Predictive Control (MPC)-based optimal control frameworks for intelligent district energy system operation.
- Applied the framework to assess renewable and waste heat integration (e.g., data center recovery), demonstrating improved efficiency and carbon reduction potential.


**Technical Focus:** hybrid modeling • MPC • system optimization • flexibility analysis  

---

### Demonstration of Building Energy Efficiency through Thermal Microgrids in Fort Hood - Phase I Feasibility Study
**Sponsor:** U.S. Department of Defense – SERDP / ESTCP  
🔗 [Award Details](https://serdp-estcp.mil/projects/details/5561805a-f46a-4854-8f74-cc252917fa0c)

- Conducted technical modeling and analysis for a DoD-funded study on district heating and cooling system retrofit.
- Built Modelica virtual testbeds for 30+ Fort Hood buildings and reconstructed hourly heating and cooling loads with XGBoost.
- Developed and evaluated model predictive control strategies for plant operation and temperature reset in Modelica digital-twin simulations.
- Compared retrofit concepts; one building cluster showed nearly 68% lower modeled annual district thermal-system energy input than its existing-system baseline.
- Supported NIST BLCC life-cycle cost comparisons of retrofit alternatives with different study periods.


**Technical Focus:** digital twin modeling • predictive control • lifecycle cost modeling  

---

### Demonstration of a Solar-Geothermal District Heating and Cooling System with a Single Pipe Loop in Citizen Potawatomi Nation
**Sponsor:** U.S. Department of Energy (DOE)  
🔗 [Award Details](https://www.energy.gov/nepa/articles/cx-028810-demonstration-solar-geothermal-district-heating-and-cooling-system-single)

- Developed the Modelica system model for a proposed all-electric, single-pipe geothermal district network, integrating borefields, building heat pumps, and the distribution loop.
- Analyzed annual borefield thermal balance and compared pumping and loop-temperature control strategies in simulation to support Phase I design decisions.
- Developed photovoltaic-thermal (PVT) collector models for a separate Denver 5GDHC virtual testbed, documented in a 2025 conference paper; this was distinct from the Citizen Potawatomi Nation Phase I case.
- Phase I simulations projected about 38% lower electricity use than the existing heating, cooling, and domestic-hot-water systems and elimination of on-site natural-gas use for the proposed design.


**Technical Focus:** renewable integration • system-level simulation • electrification modeling  

---

## National Lab Experience

### Thermal Energy Storage Optimization – Pacific Northwest National Laboratory (PNNL)

- Built a Python workflow for DOE's Thermal Energy Storage (TES) Sizing Tool, generating 240 case configurations to compare storage capacities and time-of-use tariff options.
- Developed chilled-water TES control strategies and compared modeled daily utility costs against schedule-based TES control across four representative-day simulations.
- Contributed to [DOE Stor4Build consortium](https://www.energy.gov/eere/buildings/stor4build) on grid-interactive efficient buildings (GEBs)  

**Technical Focus:** tariff optimization • control strategy design • parametric analysis  

---

## Tools & Technical Stack

**Modeling & Simulation:** Modelica/Dymola, FMI/FMU co-simulation, EnergyPlus/OpenStudio  
**Optimization & Control:** Model Predictive Control (MPC), machine learning for thermal systems, numerical optimization  
**Programming & Development:** Python, Git, MATLAB  
**Applications:** District heating and cooling (5GDHC), heat pumps, thermal energy storage, geothermal and PVT systems, grid-interactive efficient buildings, fault detection and diagnostics, life-cycle cost analysis
