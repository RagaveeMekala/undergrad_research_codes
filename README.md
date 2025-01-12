# undergrad_research_codes
The function of the code Analysis of azimuthal age gradients and galactic resonances are as follows. The required data sheets are in the .csv format of each galaxy. The code gifmaker.ipynb creates a gif using the png images obtained from DS9 using opened region files created by the former code.

1. Creates a region file for each/all age bins of stellar clusters as .reg which can be opened in DS9 software.
2. Computes the resonance locations of galaxies including corotation resonance, ILR, OLR and 4:1 resonances using entered rotation curve data.
3. Computes the azimuthal offsets of each star cluster in  galaxy relative to the spiral arm, and histogram plot, box plot, KDE plot and line plot will be given as the output. A similar analysis will be done for two cases; within and beyond the corotation resonance giving histogram, box plot and line plot.
4. Computation to verify whether the time taken for azimuthal offsets predicted by quasi-stationary density wave theory are aligned with the time taken for the observed azimuthal offset values for each age bin <1 Gyr.
5. Computation to compare whether the azimuthal offset values as predicted by quasi-stationary density wave theory for 1-5 Gyr are aligned with observed azimuthal offsets within the age bin 1-5 Gyr and comparison is done using box plot, kde plot and error bar plot.
6. Computation to compare whether the azimuthal offset values as predicted by quasi-stationary density wave theory for 5-13 Gyr are aligned with observed azimuthal offsets within the age bin >5 Gyr and comparison is done using box plot, kde plot and error bar plot.
7. Creates region files .reg to be opened in DS9 and images are saved as .png files and then these can be used to create a timelapse .gif using gifmaker.ipynb. These .gif files are also available in this repository.
