# 24 GHz CMOS LC Voltage-Controlled Oscillator (LC-VCO) Design

## Overview
This project presents the design and simulation of a **24 GHz CMOS LC Voltage-Controlled Oscillator (LC-VCO)** for mmWave applications using **Cadence Virtuoso (65 nm CMOS Technology)**. The objective was to achieve stable high-frequency oscillation with low phase noise and good power efficiency through optimized circuit design and RF analysis.

---

## Objectives
- Design a high-frequency LC-VCO operating near 24 GHz.
- Achieve stable oscillation with low phase noise.
- Optimize the LC tank and transistor sizing for improved performance.
- Evaluate oscillator performance using RF simulation techniques.

---

## Design Specifications

| Parameter | Value |
|-----------|-------|
| Technology | CMOS 65 nm |
| Supply Voltage | 1 V |
| Target Frequency | 24 GHz |
| Achieved Frequency | 23.5 GHz |
| LC Topology | Cross-Coupled NMOS |
| Inductor | 290 pH (Q = 10) |
| Capacitor | 75 fF |
| Bias Current | 2.5 mA |

---

## Methodology

- Designed an LC tank oscillator using a cross-coupled NMOS architecture.
- Selected optimized inductor and capacitor values for 24 GHz operation.
- Implemented the complete schematic in Cadence Virtuoso.
- Performed transient, PSS, harmonic balance, and phase noise simulations.
- Evaluated oscillator stability and tuning characteristics under parameter variations.

---

## Simulation Results

| Metric | Result |
|--------|---------|
| Oscillation Frequency | 23.5 GHz |
| Peak Output Voltage | 650 mV |
| Phase Noise (@1 MHz Offset) | -94 dBc/Hz |
| Figure of Merit (FoM) | -179.9 dB |

---

## Key Features

- LC Tank based CMOS VCO
- Cross-Coupled NMOS Topology
- Low Phase Noise Design
- RF Performance Optimization
- Harmonic Balance Analysis
- PSS Analysis
- Frequency Stability Verification

---

## Tools Used

- Cadence Virtuoso
- Spectre Simulator
- CMOS 65 nm Technology
- Analog/RF Design
- Harmonic Balance (HB) Analysis
- Periodic Steady-State (PSS) Analysis
- Transient Simulation

---

## Repository Structure

```
24GHz-CMOS-LC-VCO-Design/
│
├── README.md
├── Report.pdf
├── Presentation.pdf
├── images/
│   ├── schematic.png
│   ├── waveform.png
│   ├── phase_noise.png
│   ├── hb_analysis.png
│   └── pss_analysis.png
└── results/
```

---

## Future Improvements

- Improve phase noise performance.
- Increase tuning range.
- Reduce power consumption.
- Integrate automatic frequency calibration.
- Layout implementation and post-layout verification.

---

## Author

**M. Sravya**

Department of Electronics and Communication Engineering
