# Sb2Se3-Solar-Cell-SCAPS1D
SCAPS-1D numerical investigation of rear-region defects and back-contact work function in n-type Sb2Se3 solar cells.
# Numerical Investigation of Rear-Region Defects and Back-Contact Work Function in n-Type Sb₂Se₃ Solar Cells Using SCAPS-1D

## Project Overview

This project investigates the influence of rear-region defect density and back-contact work function on the simulated photovoltaic performance of an n-type antimony selenide (Sb₂Se₃) solar cell.

The device was modelled using SCAPS-1D version 3.3.12 under AM1.5G illumination at 100 mW/cm² and a temperature of 300 K.

The study consists of three simulation cases:

- **R0 — Baseline device:** Reference Sb₂Se₃-based solar-cell structure.
- **R1 — Rear-region defect modification:** Rear-region defect density reduced from 10¹⁵ to 10¹⁴ cm⁻³.
- **R2 — Back-contact modification:** Back-contact work function increased from 4.81 to 4.85 eV.

## Research Objective

The objective is to compare the influence of two separate electronic parameters on photovoltaic performance:

1. Effective rear-region defect density.
2. Back-contact work function.

The study also discusses the possible relevance of rear-interface engineering to published research on Sb₂Se₃ solar cells.

## Device Structure

Back contact / Sb₂Se₃ rear region / Sb₂Se₃ bulk absorber / TiO₂ electron transport layer / Front contact

| Layer | Thickness |
|---|---:|
| Sb₂Se₃ rear region | 10 nm |
| Sb₂Se₃ bulk absorber | 490 nm |
| TiO₂ | 10 nm |

Total semiconductor thickness: 510 nm.

## Main Simulation Results

| Parameter | R0 | R1 | R2 |
|---|---:|---:|---:|
| Voc (V) | 0.572496 | 0.572513 | 0.585646 |
| Jsc (mA/cm²) | 36.7179 | 36.7179 | 36.7839 |
| Fill Factor (%) | 51.2553 | 51.2591 | 54.3217 |
| PCE (%) | 10.7743 | 10.7754 | 11.7022 |

## Key Findings

- Reducing the effective rear-region defect density produced a negligible change in simulated PCE.
- Increasing the back-contact work function produced a higher simulated PCE.
- R2 showed an absolute PCE increase of 0.9279 percentage points compared with R0.
- The ideal Schottky–Mott estimate indicated a reduction in the hole barrier from 0.32 to 0.28 eV.

## Important Scope and Limitations

The simulations do not directly model oxygen incorporation, oxygen diffusion, selenium-vacancy passivation or Sb₂O₃ formation.

The rear-region defect density is an effective model parameter and is not proof of a specific atomic defect. The back-contact work-function change is an independent electronic parameter change and does not establish an oxygen-related chemical mechanism.

All photovoltaic values are numerical simulation outputs, not experimental measurements.

## Repository Contents

- `Report/` — Consolidated scientific research report.
- `Simulation_Files/` — SCAPS-1D input definition files, where available.
- `Results/` — Numerical simulation data and parameter comparisons.
- `Figures/` — Device structure and simulation plots.
- `SCAPS_Outputs/` — Original simulation output reports.

## Software

SCAPS-1D, version 3.3.12.

## Research References

The project is informed by published research on Sb₂Se₃ photovoltaic materials, defect physics, back-contact behaviour and SCAPS-1D modelling. Full references and DOI links are provided in the scientific report.

## Author

Yusra Babar Khan  
BS Chemistry | Fatima Jinnah Women University
