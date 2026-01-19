# Two-Stage Miller Operational Amplifier Design

## Overview
This repository contains the design documentation and simulation results for a **CMOS Two-Stage Operational Amplifier** with Miller compensation. The project focuses on achieving high stability and gain through rigorous optimization of transistor sizing and compensation capacitance using **Cadence Virtuoso**.

## Key Specifications & Results
Based on final simulations and optimization:

| Parameter | Value | Note |
|-----------|-------|------|
| **Open-Loop Gain** | [cite_start]72.07 dB | [cite: 165] |
| **Phase Margin** | 62.94° | [cite_start]Stable (>60°) [cite: 164] |
| **Bandwidth (BW)** | [cite_start]2.14 MHz | [cite: 126] |
| **Miller Capacitor** | 2.5 pF | [cite_start]Optimized for best settling time [cite: 125] |
| **Load Capacitor** | 0.1 pF - 1 pF | [cite_start]Tested under varying loads [cite: 16, 162] |

## Project Contents (PDF)
The uploaded report includes:
* [cite_start]**Schematic Design:** Detailed transistor-level implementation of the differential pair and gain stages[cite: 14, 15].
* [cite_start]**DC Analysis:** Operating point verification and saturation range analysis ($I_{ref} = 2\mu A$)[cite: 25, 26].
* [cite_start]**Transient Analysis:** Step response simulations to determine stability and settling time[cite: 74].
* [cite_start]**Optimization Process:** Comparison between theoretical calculations (Sansen's model) and simulation results to find the optimal Miller capacitor ($C_m$) and transistor width ($W$)[cite: 17, 23, 134].
* [cite_start]**Bode Plots:** Frequency domain analysis validating the Phase Margin and Gain[cite: 155].

## Tools Used
* [cite_start]**Cadence Virtuoso** (Schematic Editor & Analog Design Environment) [cite: 37]
* **Spectre Simulator**

## Authors
* [cite_start]Noam & Rom [cite: 6]
