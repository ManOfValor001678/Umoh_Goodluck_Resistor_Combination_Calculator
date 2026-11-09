# Resistor Combination Calculator

## What it does
This Python command-line tool calculates the total equivalent resistance for any number of resistors connected in both series and parallel configurations. Additionally, it features an advanced tolerance analysis mode to compute worst-case minimum and maximum resistance variations based on component tolerances.

## How to run it
Install Python 3, then run:
```bash
python resistor_calculator.py

==========================================
   RESISTOR COMBINATION CALCULATOR        
==========================================
Enter the number of resistors you have: 3
Enter value for resistor 1 (in Ohms): 100
Enter value for resistor 2 (in Ohms): 220
Enter value for resistor 3 (in Ohms): 330

--- Resistor Summary ---
Stored Resistor Values: [100.0, 220.0, 330.0] Ohms
Total Series Resistance: 650.00 Ohms
Total Parallel Resistance: 54.10 Ohms

--- [TWIST FEATURE] Tolerance Analysis ---
Standard resistor tolerances: 1%, 5%, 10%
Enter the resistor tolerance percentage (e.g., 5 for 5%): 5
Do you want tolerance analysis for [S]eries or [P]arallel? S

Series Circuit Tolerance Range (5%):
Minimum Possible Resistance: 617.50 Ohms
Maximum Possible Resistance: 682.50 Ohms

Thank you for using the Resistor Calculator!

