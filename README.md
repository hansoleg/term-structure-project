# Term Structure Project

This project examines the pricing of U.S. Treasury bills and coupon bonds, and builds the term structure of interest rates from those instruments. The aim is to draw the term structure of interest rates clean and dirty prices, discount factors, spot rates, and forward rates using standard fixed-income conventions.

The notebook also includes day-count adjustments, accrued interest calculations, and a step-by-step bootstrap of the yield curve.

## Contents
- **Yield_curve_project.ipynb** – main notebook with all calculations
- **Datasets/** – Treasury bill and bond datasets used in the project

## What the notebook does
1. Loads Treasury bill and bond data  
2. Calculates clean and dirty prices  
3. Computes discount factors and spot rates  
4. Bootstraps the term structure  
5. Derives forward rates and visualizes parts of the curve  

## Requirements
The notebook uses standard Python libraries:
numpy
pandas
matplotlib

Everything runs by executing the notebook from top to bottom.

## Notes
This was part of a school project using real Treasury data. The calculations follow standard fixed-income methods and are intended as a clean, transparent reference for term-structure bootstrapping.

