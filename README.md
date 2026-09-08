# Firewall Development – UTRON AutoSport (Formula Student)

**Author:** Jan Moreno Feldkämper  
**Team:** UTRON AutoSport – Universitat de Vic (UVIC-UCC)  
**Season:** 2025–2026  
**Tools:** CATIA V6 / 3DEXPERIENCE, FEM Thermal Simulation (Mechanical Scenario Design)

---

## Overview

Full engineering development of the firewall for UTRON AutoSport's first 
combustion-engine Formula Student car. The firewall is a safety-critical component 
that separates the cockpit from the powertrain, fuel system, and all flammable 
elements, in compliance with Formula Student Germany regulations (FSG T4.8.x, 
T4.6.2).

This project covered the entire development cycle — from regulation analysis and 
benchmarking to CAD design, thermal simulation, and iterative redesign.

---

## Documents

| File | Description |
|------|-------------|
| `01-Benchmarking_firewall.pdf` | Regulation analysis (FSG T4.8.x), material benchmarking (9 materials, 5 configurations), comparison with other FS teams |
| `02-Final_firewall_design_and_bracket.pdf` | Final material configuration (Al–Aerogel–Al), design decisions, support bracket design, thermal bridge mitigation strategy |
| `03-Insulation_material_alternative.pdf` | Cost-optimized insulation alternative (ceramic fibre blanket vs. aerogel) |
| `04-Firewall_simulation.pdf` | Transient heat transfer FEM simulation in 3DEXPERIENCE — setup, boundary conditions, results and conclusions |
| `05-Firewall_redesign.pdf` | Iterative redesign based on simulation results — air gap configuration (25 mm), cost reduction ~€150 vs. aerogel solution |

---

## Key Results

- Final configuration: Aluminium (3 mm) – 25 mm air gap – Aluminium (3 mm) with fire-retardant coating, fully compliant with FSG T4.6.2
- Validated via transient FEM simulation: cold-side temperature below 60°C after 20 minutes at 220°C source temperature
- Iterative redesign eliminated the aerogel insulation and the silicone bonding, reducing material cost from ~€300 to ~€80
- Full compliance with FSG T4.8.1 – T4.8.6 firewall regulations

---

## Related Project

[Design and transient FEM thermal analysis of a ventilated brake disc](https://github.com/jan-moreno-feldkamper/brake-disc-thermal-analysis-porsche-992)
— the same workflow applied to a component with a considerably more demanding thermal duty.
