# Aerospace Engineering Toolkit

A Python-based interactive toolkit for aerospace engineering calculations covering **propulsion**, **aerodynamics**, and **flight mechanics**.  
It provides a **menu-driven CLI interface** for quick engineering calculations and visualization.

---

## Features

### Propulsion Tools
- **Isentropic Flow Solver** → Calculates total-to-static temperature, pressure, and density ratios.
- **Jet Engine Calculator** → Computes thrust, TSFC, thermal, propulsive & overall efficiencies.
- **Rocket Engine Calculator** → Computes thrust, Isp, characteristic velocity (C*), thrust coefficient (CF), nozzle efficiency.
- **Solid Rocket Motor Calculator** → Calculates burn rate, total impulse, and average thrust.

### Aerodynamics Tools
- **Aerodynamic Parameters** → Lift, drag, dynamic pressure, aspect ratio, induced drag, total drag.
- **Earth Atmosphere (ISA)** → Temperature, pressure, and density up to 32 km altitude.
- **Wind Tunnel Nozzle Design** → Nozzle area ratio for given Mach number.
- **Normal Shock Wave Calculator** → Post-shock flow properties and total pressure ratio.

### Flight Mechanics Tools
- **NACA 4-Digit Airfoil Generator** → Plots airfoil shape and exports coordinates.
- **Aerodynamic Coefficients Plotter** → Example plots of CL, CD, CM vs Angle of Attack.
- **Range & Endurance Calculator** → Breguet equations for jet and propeller aircraft.
- **Gliding Flight Calculator** → Glide speed, glide angle, L/D ratio, and sink rate.

---

## Requirements

- **Python 3.x**
- Required Libraries:  
  - `numpy`  
  - `matplotlib`

Install dependencies using:
```bash
pip install numpy matplotlib
```

---

## How to Run

1. **Download or clone this repository**  


2. **Run the toolkit**  
```bash
python Aerospace_Engineering_Toolkit.py
```

3. **Select from the menu**:
```
=== Aerospace Engineering Toolkit Main Menu ===
1. Propulsion Tools
2. Aerodynamics Tools
3. Flight Mechanics Tools
q. Exit Toolkit
```

4. **Navigate submenus**:
- Propulsion Tools → Isentropic Solver, Jet Engine, Rocket Engine, Solid Rocket Motor  
- Aerodynamics Tools → Aerodynamic Params, Atmosphere, Nozzle Design, Normal Shock  
- Flight Mechanics Tools → Airfoil Generator, Aero Coefficients Plot, Range/Endurance, Gliding Flight  

---

## Example CLI Navigation

### Propulsion Menu
```
--- Aerospace Propulsion Toolkit ---
1. Isentropic Equation Solver
2. Jet Engine Parameter Calculation
3. Rocket Engine Parameter Calculation
4. Solid Rocket Motor Calculation & Analysis
b. Back to Main Menu
```

### Aerodynamics Menu
```
--- Aerospace Aerodynamics Toolkit ---
1. Aerodynamic Parameter Calculation
2. Earth Atmosphere Calculation (ISA)
3. Wind Tunnel Nozzle Design Calculation
4. Normal Shock Wave Calculation
b. Back to Main Menu
```

### Flight Mechanics Menu
```
--- Aerospace Flight Mechanics Toolkit ---
1. Airfoil Generator (NACA 4-digit)
2. Plot Aerodynamic Coefficients (Example)
3. Range and Endurance Calculation
4. Gliding Flight Parameter Calculation
b. Back to Main Menu
```



