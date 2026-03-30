# 50Ω Microstrip Transmission Line Design at 1.2 GHz

**King Abdulaziz University | EE424 | 2024**

## Overview
Designed and simulated a 50-ohm microstrip transmission line operating at 1.2 GHz. The design utilizes an FR4 substrate with a dielectric constant ($\epsilon_r$) of 4.3 and a thickness of 0.7 mm, targeting an electrical length of $\pi/4$.

## Methods Implemented
- Analytical calculation of effective dielectric constant ($3.265$) and TL dimensions (Width = 1.36 mm, Length = 17.293 mm).
- 3D Electromagnetic Simulation to verify signal integrity and power transmission.
- S-Parameter analysis to ensure matched ideal performance.

## Results
The simulation results demonstrated an ideal performance of a matched microstrip transmission line with no power losses:

| Parameter | Simulated Result | Performance Indication |
|--------|----------|----------------------|
| Operating Frequency | 1.2 GHz | - |
| S11 & S22 | ~ -54 dB | Perfect matching (No reflection) |
| S12 & S21 | ~ 0 dB | Strong power transmission |

## Tools
- CST Studio Suite (3D EM Simulation)
- Theoretical Hand Calculations
