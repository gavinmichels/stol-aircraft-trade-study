# STOL Aircraft Optimization Trade Study

MATLAB-based trade study investigating the effects of key aircraft design parameters on Short Takeoff and Landing (STOL) performance.

![MATLAB](https://img.shields.io/badge/MATLAB-R2025a-orange)
![Status](https://img.shields.io/badge/Status-Development-yellow)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## Overview

This project evaluates how several aerodynamic and design variables influence the performance of a STOL aircraft. The Aviat Husky A-1C was used as the baseline aircraft, while MATLAB models estimated the aircraft performance across hundreds of possible configurations.

The goal was to identify a configuration that minimizes takeoff and landing distance while maintaining acceptable cruise performance, climb capability, payload, and structural practicality.

---

## Objectives

- Reduce takeoff distance
- Reduce landing distance
- Lower stall speed
- Improve climb performance
- Maintain useful cruise performance
- Select the optimal design using a weighted trade study

---

## Design Variables

The following parameters were investigated:

- Wing Area
- Aspect Ratio
- Engine Power
- High-Lift Device (Plain, Slotted, Fowler)
- Taper Ratio

---

## Performance Metrics

Each configuration was evaluated using analytical performance models for:

- Stall Speed
- Ground Roll
- Takeoff Distance over a 50-ft Obstacle
- Rate of Climb
- Cruise Efficiency
- Wing Loading
- Power Loading

---

## Methodology

1. Define performance requirements
2. Establish a baseline aircraft
3. Generate candidate aircraft configurations
4. Predict aircraft performance using MATLAB
5. Compare alternatives using a weighted decision matrix
6. Perform sensitivity analysis
7. Select the optimum configuration

---

## Repository Structure

```
STOL-Aircraft-Trade-Study
|
├── README.md
└── LICENSE
```

---

## Results

...

## Skills Demonstrated

- MATLAB Programming
- Aerospace Vehicle Performance
- Aircraft Design
- Trade Studies
- Decision Matrix Analysis
- Engineering Optimization
- Sensitivity Analysis
- Technical Documentation

---

## References

Aircraft data and references are listed in the accompanying report.



