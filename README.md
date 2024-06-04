3flavor_matterandvaccum_survivale_e_295km

This program calculates and plots the survival probabilities of electron neutrinos (and their antineutrinos (in both matter and vacuum as a function of neutrino energy). 
The chosen baseline for the calculations is 295 km. The program uses parameters for neutrino oscillation, such as mass squared differences, mixing angles, CP-violating phase, and matter density.

Requirements:
Python 3.x
numpy library
matplotlib library

Program Explanation:
Import Libraries.
Define Constants and Parameters:
Energy range (E) in GeV.
Baseline distance (L) in km.
Mass squared differences (in eV²).
Mixing angles (in radians).
CP-violating phase (in radians).
Matter density in g/cm³.
Precomputed constants like sin(2\theta) and cos(\theta).
Initialize Lists:
Lists to store calculated values for the potential, anti-neutrino potential and survival probabilities.

Calculation Loop:
For each energy value in the defined range:
Compute the oscillation phase (\delta).
Compute the matter potential (v) and A.
Calculate survival probabilities in matter and vacuum for both neutrinos and antineutrinos.
Append these values to the respective lists.

Plotting:
Plot the calculated survival probabilities against energy using matplotlib.
