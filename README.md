# Two-Stage Miller Operational Amplifier Design

## Overview
This repository contains the design documentation and simulation results for a **CMOS Two-Stage Operational Amplifier** with Miller compensation. The project focuses on achieving high stability and gain through rigorous optimization of transistor sizing and compensation capacitance using **Cadence Virtuoso**.

## Key Specifications & Results
Based on final simulations and optimization:

| Parameter | Value | Note |
|-----------|-------|------|
| **Open-Loop Gain** | 72.07 dB | |
| **Phase Margin** | 62.94° | Stable (>60°) |
| **Bandwidth (BW)** | 2.14 MHz | |
| **Miller Capacitor** | 2.5 pF | Optimized for best settling time |
| **Load Capacitor** | 0.1 pF - 1 pF | Tested under varying loads |

## Project Contents (PDF)
The uploaded report includes:
* **Schematic Design:** Detailed transistor-level implementation of the differential pair and gain stages.
* **DC Analysis:** Operating point verification and saturation range analysis (I_ref = 2uA).
* **Transient Analysis:** Step response simulations to determine stability and settling time.
* **Optimization Process:** Comparison between theoretical calculations (Sansen's model) and simulation results to find the optimal Miller capacitor and transistor width.
* **Bode Plots:** Frequency domain analysis validating the Phase Margin and Gain.

## Tools Used
* **Cadence Virtuoso** (Schematic Editor & Analog Design Environment)
* **Spectre Simulator**

