# Inverse Taper and Edge-Coupler Design on TFLN and SiN Waveguides

*Lumerical FDTD / EME Simulations for Efficient Fiber-to-Chip Coupling in Squeezing Measurements*

This work demonstrates a general methodology for improving fiber-to-chip coupling by designing inverse tapers and edge-coupler structures. The repository provides the design, optical simulation, and lithography-oriented 3D modeling on:
- **Thin-film lithium niobate (TFLN)** platforms
- **Silicon nitride (SiN)** platforms

using a combined **Lumerical FDTD/EME** and **FreeCAD** parametric modeling workflow.

The primary objective is to enable high-efficiency coupling for balanced homodyne detection of chip-scale squeezing generation. Optimizing **transmission and mode overlap** with lensed-fiber modes.

## Output Beam-Shaping Designs
### Inverse Tapers:
<td><img src="https://github.com/user-attachments/assets/4b8409bb-92d1-4a5c-9974-e24d3622e2c9" width="800" /></td>

### Edge-lens couplers:
<td><img src="https://github.com/user-attachments/assets/e3206b23-5970-4628-918b-07856aaba85d" width="800" /></td>

#### Aspheric / Elliptical Designs
Because TFLN modes are highly anisotropic and non-circular, this project investigates:
- Aspheric lens geometries for near-circular collimation
- Elliptical collimators to reshape guided modes into target Gaussian beams
- Customized taper profiles for improved far-field symmetry

## Optimization Goals and Results

### Goal 1 - Fiber-Coupled Balanced Detection

Target Gaussian mode: 2.5 μm mode-field diameter (Typical lensed-fiber MFD)
Used for low-loss coupling from chip → lensed fiber → homodyne detector.

#### Results: 
**-1.78 dB transmission*mode overlap per facet**
<td><img src="https://github.com/user-attachments/assets/5e274c95-e55e-4f50-94f0-d6313852a0bc" width="500" /></td>

<td><img src="https://github.com/user-attachments/assets/9beeb9a5-8cac-4aec-8cea-83faa3c2a218" width="500" /></td>

### Goal 2 - Free-Space Balanced Detection

Target Gaussian mode: 1.0 μm waist in free space

Chosen to reduce diffraction and improve collection efficiency with high-NA lenses.

Used for chip → free-space → BHD setups requiring mode cleanliness.

### Goal 3 - Inverse Taper

#### Results: -2.18 dB transmission*mode overlap per facet

*This repository contains only simulation-level components and does not include any experimental or proprietary system details*




