# Characterization-of-LDR-Response-to-LED-Illumination

This repository contains experimental data and analysis scripts for characterizing the resistance behavior of a Light Dependent Resistor (LDR) under varying LED illumination.

## 📁 Contents

- `LDR_EXP - RvsI_LDR - Sheet1.csv` — Measured LDR resistance vs LED current data.
- `ldr_analysis.py` — Python script to fit a power-law model and plot results.
- Plots: Resistance vs Current (linear scale), optional log–log fit.
- LaTeX report sections (procedure, results, conclusion) — optional.

## 📊 Experiment Summary

An LDR and a white LED were mounted inside a black PVC tube at a fixed 3 cm distance. The LED was powered with a variable external supply, and its current was measured directly. The corresponding resistance of the LDR was recorded using a digital multimeter.

A power-law model of the form:

was fitted using `scipy.optimize.curve_fit`, where:
- `R` is the LDR resistance in kΩ  
- `I` is the LED current in mA

## 🔧 Requirements

- Python 3.x  
- `numpy`, `pandas`, `matplotlib`, `scipy`




