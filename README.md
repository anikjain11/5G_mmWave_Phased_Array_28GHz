# 28 GHz 5G mmWave Phased Array Antenna

## Project Overview
This repository contains the physical design, simulation data, and performance metrics for a 28 GHz mmWave antenna array designed for 5G communication systems. The design was modeled and simulated using CST Studio Suite (Time Domain Solver).

## Phase 1: Single Element Design
Before constructing the array, a single rectangular patch antenna was optimized for a 50-ohm match at exactly 28 GHz. 

### Design Parameters
* **Substrate:** Rogers RT/duroid 5880 (Loss Free)
* **Dielectric Constant (εr):** 2.2
* **Substrate Thickness (h):** 0.254 mm
* **Patch Dimensions:** W = 4.24 mm, L = 3.47 mm
* **Feeding Technique:** Microstrip Inset Feed

### Performance Metrics (Pending Simulation)
* **Resonant Frequency:** 28 GHz
* **Return Loss (S11):** [We will insert your dB value here]
* **VSWR:** [Insert value]
* **Directivity:** [Insert dBi value]

## Repository Structure
* `/CST_Project_Files`: Contains the raw `.cst` modeling files.
* `/Exported_Data`: Contains the raw S-parameter Touchstone files for external verification.
* `/Images`: Visual documentation of the radiation patterns and physical layout.
