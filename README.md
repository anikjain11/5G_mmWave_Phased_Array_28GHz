**28 GHz 5G mmWave Phased Array Antenna**
**Project Overview**
This project focuses on the design and optimization of a high-performance microstrip patch antenna element for 5G mmWave applications at 28 GHz. The primary objective was to achieve a professional-grade impedance match (S11 < -20 dB) while maintaining precise resonance at the 28 GHz frequency band. The design was modeled and simulated using CST Studio Suite 2025.

**Design Methodology**
The antenna was designed on Rogers RT/duroid 5880 substrate to minimize dielectric losses. A Microstrip Inset Feed technique was utilized to provide a 50-ohm impedance match without the need for additional matching transformers.

**Optimized Design Parameters**
Through iterative parametric sweeps, the following dimensions were finalized to achieve the target resonance:

Substrate Thickness (h): 0.254 mm

Patch Length (L_patch): 3.26 mm

Inset Feed Depth (Inset_L): 0.93 mm

Feed Gap (Inset_G): 0.4 mm

**Performance Validation**
The design was verified through frequency domain analysis, demonstrating a highly efficient energy transfer.

Resonant Frequency: 28.0 GHz

Return Loss (S11): -28 dB

Impedance Matching: Excellent (Return loss significantly below the -10 dB industry standard).

**Supporting Documentation**
Detailed simulation reports and visualization plots are available for review:

1. [S-Parameter Analysis (PDF)](28GHz_S11_Plot.pdf)
2. [3D Radiation Pattern Plot (PDF)](Farfield_Plot_3D.pdf)

Developed as part of RF and Analog Front-End research initiatives.

## Phase 2: 1x2 Phased Array System
To demonstrate electronic beam steering, a 1x2 finite array was constructed utilizing the optimized unit cell with a λ/2 element spacing (5.35 mm). 

### Array Performance Metrics
- **Element Matching (S11 / S22):** -37 dB at 28 GHz
- **Mutual Coupling (S21 / S12):** -37 dB (High Isolation)
- **Boresight Gain (0° Phase Shift):** 7.44 dBi
- **Steered Gain (90° Phase Shift):** 8.49 dBi

### Active Impedance Analysis
While individual port matching was exceptional, the array demonstrated significant Active Impedance variation during simultaneous excitation. The active S-parameters (`S1,1[Active]`) approached 0 dB, resulting in a total efficiency drop to -8.6 dB. This highlights the critical impact of mutual coupling and spatial field interactions in mmWave phased array active states, presenting a clear path for future matching network optimization.

### Array Validation Documentation
1. [Array S-Parameters & Active Matching](Combined_1x2_S11_Plot.pdf)
2. [Boresight Radiation Pattern (0°)](Boresight_Farfield_Plot_3D.pdf)
3. [Steered Radiation Pattern (90°)](Steered_Farfield_Plot_3D.pdf)
