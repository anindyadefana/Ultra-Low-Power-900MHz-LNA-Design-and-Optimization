# Ultra-Low-Power-900MHz-LNA-Design-and-Optimization

## Overview

This project presents the design and optimization of an ultra-low-power 900 MHz Intermediate Frequency (IF) Low Noise Amplifier (LNA) for low-power RF receiver applications.

The design is based on a reference LNA architecture and improved using:

- Bias current optimization
- Inductive Source Degeneration (ISD)
- Impedance matching techniques
- Noise figure reduction methods

The amplifier was designed and simulated using Keysight ADS (Advanced Design System).

---

## Project Objectives

- Design a low-power IF LNA operating at 900 MHz
- Minimize power consumption while maintaining acceptable gain
- Improve noise performance
- Enhance linearity and stability
- Compare optimized results against a reference design

---

## Design Methodology

### Reference Design

The initial design was based on a published low-power IF LNA architecture.

<p align="center">
  <img src="images/reference_schematic.png" width="700">
</p>

---

### Proposed Design

The circuit was modified through bias optimization and impedance matching improvements.

<p align="center">
  <img src="images/improved_schematic.png" width="700">
</p>

---

### Inductive Source Degeneration

Inductive Source Degeneration was implemented to improve input matching, stability, and noise performance.

<p align="center">
  <img src="images/inductive_source_degeneration.png" width="650">
</p>

---

## Simulation Results

### S-Parameter Performance

<p align="center">
  <img src="images/s_parameters_result.png" width="750">
</p>

Key observations:

- Improved gain performance
- Better impedance matching
- Stable operation around 900 MHz

---

### Noise Figure and Stability Analysis

<p align="center">
  <img src="images/noise_figure_and_stability_factor.png" width="750">
</p>

Results indicate:

- Reduced noise contribution
- Stable operation across the target frequency range

---

### IIP3 Analysis

<p align="center">
  <img src="images/iip3_results.png" width="700">
</p>

The amplifier demonstrates improved linearity compared with the baseline design.

---

### Performance Comparison

<p align="center">
  <img src="images/performance_comparison.png" width="750">
</p>

Performance metrics were compared between the reference and optimized designs to evaluate improvements in:

- Gain
- Noise Figure
- Stability
- Power Consumption
- Linearity

---

## ADS Simulation Files

Due to project size limitations, the complete ADS simulation project is provided separately.

See:

```
simulation/ADS_simulation_files.txt
```

for access information.

---

## Documentation

Project documentation is available in:

- `docs/Final_Report.pdf`
- `docs/Design_Theory.pdf`
- `docs/Project_Presentation.pdf`

---

## Tools Used

- Keysight ADS (Advanced Design System)
- RF Circuit Design Techniques
- Small Signal Analysis
- Noise Figure Analysis
- S-Parameter Analysis

---

## Author

**Anindya Putri Defana**

Department of Electrical Engineering  
Universitas Indonesia

---

## Keywords

Low Noise Amplifier (LNA), RF Receiver, 900 MHz, Intermediate Frequency Amplifier, Inductive Source Degeneration, Bias Optimization, ADS Simulation, Low-Power RF Design
