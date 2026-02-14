# VTOL FPV Fixed-Wing UAV Project

## Overview

This project is a 3d printed VTOL (Vertical Take-Off and Landing) fixed-wing UAV with FPV ( First Person View )  
It combines quad lift motors for vertical flight ( kinda like a drone ) but with a additional forward propulsion motor for efficient cruise.

The objective is to design, build, and validate a structurally robust aircraft capable of stable hover, controlled transition, and forward flight.

---

## Key Features

- High-wing configuration for passive roll stability  
- 3d printed fuselage and wings  
- Quad vertical lift motors for VTOL capability  
- Nose-mounted motor for cruise propulsion  
- V tail configuration  
- Back fin designed for stability in forward flight at moderate speed
- easy access and mounting servo in the fuselage thanks to a BWD canopy

---

## Design Objectives

- Stable hover and smooth transition to forward flight  
- High structural stiffness with minimal weight  
- Efficient cruise performance  
- Predictable aerodynamic behavior at low Reynolds numbers  
- Modular architecture for maintenance and upgrades  

---

## Technical Specifications (Preliminary)

- **Wingspan:** 1300mm
- **Wing Area:** 0.286 m²
- **Wing loading:** 59 g/dm²
- **estimated stall speed:** 26 km/h ( quite high but its understandable you have 4 unused motor on your wing ) 
- **Airfoil:** SS ( Semi-Symmetrical)
- **Estimated Weight:** 1700g  
- **Lift Motors:** 4 × A2212 
- **Cruise Motor:** 1 × A2212
- **Battery:** 3s 2200mah 30C ( estimated flight time: 17min )  
- **Flight Controller:** Dakefpv f722 X6 ( any flightcontroller will work )  

---

## Structure

- 3d printed fuselage  
- Carbon fiber cantilever motor arms  
- Fully 3d printed wing structure  
- mechanical aileron rolling on axis

---

## Development Roadmap

- [ ] Airfoil validation (XFOIL / CFD analysis)  
- [ ] Structural deflection testing of motor outriggers  
- [ ] Center of Gravity calculation and validation  
- [ ] Hover stability tuning  
- [ ] Transition control implementation  
- [ ] Flight testing and data collection  

---

## Engineering Challenges

- Drag from exposed lift motors during cruise  
- Structural vibration and resonance of motor arms  ( simulation ) 
- Stable hover-to-cruise transition ( hard ) 
- Accurate CG placement ( moderate ) 

---

## Future Improvements

- Custom flight controller board 

---

## Disclaimer

This project is experimental and intended for research and educational purposes.  
All flight testing must be conducted in safe and controlled environments.
