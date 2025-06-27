# Pipe Diameter Calculator using Manning's Equation

This Python script calculates the diameter of a circular pipe (in mm) required to carry a given flow rate based on Manning's equation. It's particularly useful for civil engineers or students working on open channel flow and stormwater drainage design.

## 📌 Features

- Accepts user inputs for:
  - Flow rate \( Q \) in m³/s
  - Manning's roughness coefficient \( n \)
  - Bed slope \( S_0 \)
- Validates inputs
- Computes diameter with precision
- Returns both exact and rounded pipe diameter in millimeters

## 📘 Formula

The calculation is based on a rearranged form of Manning's equation:




Where:
- Q: Flow rate (m³/s)
- n: Manning's roughness coefficient
- S_0: Bed slope (dimensionless)
- D: Diameter of the pipe (m), converted to mm


