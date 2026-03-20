# Ellipsometry_Data_and_Fits

This repository contains research data and analysis for ellipsometry measurements used in thin-film photovoltaic and optoelectronic device characterization.

## What is Ellipsometry?

Ellipsometry is a non-destructive optical technique that measures the change in polarization state of light upon reflection from a sample surface. It is widely used to determine:
- Thin film thickness (nanometer precision)
- Optical constants (refractive index n, extinction coefficient k)
- Surface roughness and interface quality
- Material composition and uniformity

## What Type of Data

This repository contains:
- **Raw ellipsometry data**: Psi (Ψ) and Delta (Δ) angles as functions of wavelength
- **Fitted optical constants**: Refractive index (n) and extinction coefficient (k) spectra
- **Thickness measurements**: Film thickness values with error estimates
- **Multi-angle measurements**: Data collected at various incidence angles for improved accuracy

## Ellipsometry Measurements

The measurements were performed on:
- Organic semiconductor thin films
- Perovskite solar cell layers
- Transparent conductive oxides
- Multi-layer device stacks

Measurement parameters typically include:
- Wavelength range: UV-Vis-NIR (e.g., 200-1700 nm)
- Incidence angles: 55°-75°
- Spot size: ~1-3 mm

## Analysis Methods

The fitting process uses:
- **Cauchy or Sellmeier dispersion models** for transparent layers
- **Lorentz oscillator models** for absorbing materials
- **Effective medium approximation (EMA)** for mixed or porous layers
- **Multi-layer optical modeling** to account for substrate and interface effects
- **Least-squares regression** to minimize the difference between measured and modeled Ψ/Δ

## Data Format

**Raw data files** typically contain:
- Wavelength (nm)
- Incidence angle (degrees)
- Psi (Ψ) and Delta (Δ) values
- Measurement errors

**Fitted results** include:
- Layer thicknesses (nm)
- n and k spectra
- Mean squared error (MSE) of the fit
- Confidence intervals for fitted parameters

## Author

mzjswjz
