# Determination-of-total-carbohydrates-by-the-Anthrone-method
To perform a quantitative estimation of total carbohydrates (glucose equivalents) in a sample using the anthrone reagent (spectrophotometric method).
Anthrone Method – Standard Curve Simulation (Python)
This project provides a simple Python script to simulate the Anthrone Method experiment, generate a standard curve, and calculate the concentration of glucose in an unknown sample based on its absorbance.
The script performs the following:
Takes standard glucose concentrations and their absorbance values as input
Fits a linear regression to generate a standard curve
Accepts the absorbance of an unknown sample
Calculates its glucose concentration
Plots the standard curve (scatter + regression line)
Features: 
Easy input from user
Linear regression using NumPy
Standard curve plot using Matplotlib
Supports any number of standards
Calculates unknown sample concentration accurately
When prompted, enter:
Standard concentrations (e.g., 20,40,60,80,100)
Absorbance values (e.g., 0.05,0.08,0.12,0.18,0.25) Absorbance of the unknown sample.
The script will display:
The equation of the standard curve
The calculated concentration of the unknown sample: A graph showing the standard curve (scatter + best-fit line)
This tool helps students and researchers:
Understand the Anthrone Method. Simulate laboratory results. Practice plotting and interpreting standard curves, and Automate calculations for unknown concentrations. This project is open-source under the MIT License. 
