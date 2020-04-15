# Project_HEOM
The working files and examples from HEOM in Libra are contained here.
## HEOM Tutorial
This Jupyter notebook serves as a tutorial for generating both population dynamics and absorbance spectra using the HEOM method. The population dynamics, dipole-dipole autocorrelation function (ACF), and the Fourier transform of the AFC are calculated and plotted. Figures 4, 5, 8, 9, and 10 from the manuscript are generated here.
## Comparative Analysis
This Jupyter notebook illustrates how the different bath characteristics affect the population dynamics for two different energy gaps. It both calculates the population dynamics and plots the results. All panels of figure 6 are generated here.
## Timings
The initialization timings and time per step of the population dynamics were compared for different hierarchy complexities. The hierarchy complexity was controlled by the level of the hierarchy (LL) and the number of Matsubara frequencies (KK + 1). Figure 11 from the manuscript is generated here.

## Seven state system
The population dynamics of a seven level system is calculated using HEOM, and the results are plotted. The parameters of the system were obtained from Adolphs and Renger<sup>1</sup>. This models a subunit in the FMO complex, which transfers electrons from the light harvesting complex to the reaction center in green sulfur bacteria. Figure 7 is generated here.

[1] Adolphs, J.; Renger, T. How Proteins Trigger Excitation Energy Transfer in the FMO Complex of Green Sulfur Bacteria. Biophys. J. 2006, 91 (8), 2778–2797. https://doi.org/10.1529/biophysj.105.079483
