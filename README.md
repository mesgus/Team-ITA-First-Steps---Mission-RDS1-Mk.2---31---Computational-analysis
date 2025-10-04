# Team-ITA RocketPy Simulation: 1km Altitude Rocket Project

This repository contains the simulation code for a rocket using the **RocketPy** library. The goal is to predict flight performance, aerodynamic stability, and structural safety for a rocket designed to reach approximately **1 km in altitude** before parachute recovery.

---

##  Simulation Setup

### Environment

* **Location:** Bauru, São Paulo, Brazil area
    * Latitude: $-21.90795$, Longitude: $-48.96156$
    * Elevation: $495 \text{ m}$
* **Atmosphere:** Custom model with constant wind.
    * Wind U (E/W): $2.778 \text{ m}/\text{s}$ ($\approx 10 \text{ km}/\text{h}$)
* **Rail Length:** $4 \text{ m}$
* **Launch Angle:** Inclination $80^\circ$, Heading $0^\circ$ (North)

---


##  Requirements and Execution

### Dependencies

Install the necessary Python libraries:
```bash
pip install rocketpy pandas numpy scipy matplotlib
