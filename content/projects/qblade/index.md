---
title: "Numerical Study of a Horizontal-Axis Wind Turbine using QBlade"
summary: "Aerodynamic, structural and techno-economic optimisation of HAWT blades using QBlade (BEMT, XFoil, QFEM, FVW) for a Mediterranean wind site."
date: 2025-06-30
tags: ["Wind Energy", "QBlade", "BEMT", "Aeroelasticity", "Techno-economic Analysis"]
weight: 1

# Optional: if you later add an image in this folder (e.g. qblade.png)
# uncomment and set the filename:
# feature:
#   image: "qblade.png"

links:
  - icon: "file-pdf"
    name: "Full Master Thesis (PDF)"
    url: "https://drive.google.com/file/d/1RG3fKTwvXBXO4jonWnuZwXTfSY8L88K4/view?usp=sharing"
---

## Abstract

This project presents a numerical study of a three-bladed horizontal-axis wind turbine (HAWT)
using **QBlade CE v2.0.8**. The work combines aerodynamic, structural and techno-economic
analysis in order to design efficient and durable blades for a wind site located in **Essaouira,
Morocco**. Airfoil polars for several families (DU21–DU40 and NACA64) are generated with the
integrated **XFoil** module, then used in the **Blade Element Momentum Theory (BEMT)**
solver to evaluate the influence of **Reynolds number**, **angle of attack** and blade geometry
(chord and twist distributions) on lift, drag and power coefficients.   

Two blade concepts are investigated:

- a **homogeneous** blade based on a single optimised DU25 airfoil,  
- a **heterogeneous** blade combining DU and NACA profiles distributed along the span
according to local aerodynamic and structural requirements.   

The simulations show that the optimised homogeneous DU25 rotor achieves the **highest
aerodynamic performance** (maximum \(C_p \approx 0.47\) and about **27% more annual energy
production** than the heterogeneous design). However, **QFEM structural analysis** reveals
critical von Mises stresses and a predicted lifetime of only **1.5 years**, whereas the heterogeneous
blade reduces stresses by roughly **47%** and reaches a **27.4-year lifetime**, fully compliant with
IEC 61400-1 requirements. The long-term techno-economic assessment (CAPEX, OPEX, LCOE,
NPV and IRR) over 20 years demonstrates that only the heterogeneous configuration is
economically viable, with a **positive net present value and a payback time of about 5.8 years**. :contentReference[oaicite:2]{index=2}  

Overall, the project highlights the importance of **multi-objective optimisation** that balances
aerodynamic efficiency, structural integrity and economic performance for modern wind turbine
blade design.

---

## Key Skills & Tools

- **Wind turbine aerodynamics**
  - Blade Element Momentum Theory (BEMT)
  - Airfoil selection and optimisation (DU and NACA families)
  - Analysis of lift, drag, moment and power/thrust coefficients

- **Numerical simulation with QBlade**
  - XFoil polar generation and 360° polar extrapolation  
  - BEM and Free Vortex Wake (FVW) simulations  
  - Aero-structural analysis with **QFEM** (stress, deflection, fatigue and lifetime)

- **Energy yield & site assessment**
  - Modelling of the wind regime for the Essaouira site (Weibull distribution)
  - Computation of **Annual Energy Production (AEP)** for different blade concepts

- **Techno-economic evaluation**
  - Estimation of CAPEX, OPEX and LCOE for onshore wind turbines  
  - Long-term cash-flow modelling, **Net Present Value (NPV)** and **payback time**  
  - Compliance with IEC 61400-1 design requirements and lifetime criteria   

- **General competencies**
  - Advanced use of **QBlade** for HAWT design and optimisation  
  - Interpretation of aero-structural results and decision-making for blade concepts  
  - Scientific reporting and technical writing (master thesis in wind energy engineering)   

---

## Download

You can read the full master thesis here:

👉 [Download the full QBlade report (PDF)](https://drive.google.com/file/d/1RG3fKTwvXBXO4jonWnuZwXTfSY8L88K4/view?usp=sharing)

