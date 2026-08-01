# Instrumentation Amplifier — 3-Op-Amp Design with PVT Corner Analysis

Brief 1-2 line description: 3-op-amp instrumentation amplifier designed in 
Cadence Virtuoso (180nm CMOS), validated across process/voltage/temperature 
corners for product-binning-grade robustness.

## Architecture
- Two-stage CMOS op-amp core, three-op-amp in-amp topology
- Brief explanation of buffer stage + difference amplifier stage
- Gain equation: A_D = (R2/R1)(1 + 2Rf/RG)
- [Insert block diagram image]

## Transistor Sizing
- Table of W/L ratios (M0/M8, M1/M3, M4/M7, M2, M5) — pull directly from your PPT table

## Simulation Results
- Transient response (input/output waveforms) — image
- AC analysis: gain ≈ 20 dB, bandwidth ≈ 1.9 MHz — image
- PVT corner summary table (FF/SS/TT/FS/SF, 1.78-1.82V, 0-80°C) — image or table

## Tools Used
Cadence Virtuoso, LTspice, 180nm CMOS PDK

## Key Results
- ~20 dB differential gain, stable within 19.65–19.81 dB across all 5 process corners
- Bandwidth: 1.46–1.91 MHz across PVT

## Team
Group project (MNIT Jaipur, VI Sem Minor Project, 22ECW351) — 5 members.
Contributed across all stages: architecture, transistor sizing, schematic 
design, PVT corner simulation, and results analysis.
