# WIM NPBN GUI

The Graphical User Interface NPBN WIM computes synthetic WIM data. The observations corresponding to April 2013 for three Dutch locations in both the right (-R) and the left (-L) driving directions. The measurements were taken in highways A12 (km 42) Woerden, A15 (km 92) Gorinchem and A16 (km 41) Gravendeel. Additionally an hypothetical highway was created which is a combination of all six available WIM locations in the model. Therefore, each simulated vehicle randomly choose one of the locations to compute the synthetic data.

The 26 codes (Vehicle types) used in the GUI WIM consist of a letter and a number that define number of axles. The letter represent the vehicle configurations: Buses (B), Tractor---Semitrailer---Trailer ( R), Tractor---Semitrailer (T), Single unit multi axle vehicle and/or Single unit multi axle vehicle - Semitrailer (V) and Others vehicles (O). For example, a seven axle vehicle with the configuration Tractor---Semitrailer is coded as T7.

In the main window of the GUI. The user can choose between the 26 vehicle types and the 7 locations (A12-L, A12-R, A15-L, A15-R, A16-L, A16-R and Hypothetical). To compute the desired amount of WIM Observation and the desired units. 

There are, three main check boxes: 1) vehicle type subset, 2) correlation matrix plot and 3) Bayesian network plot.

1. If the vehicle type subset check box is selected the user need to select at least 4 of the available 26 vehicle types and provide their corresponding proportions. Otherwise 26 vehicle types will be use to generated synthetic observations.
2. Correlation matrix plot shows a color map of the rank correlation matrix. 
3. Bayesian network plot shows the Non Parametric Bayesian Network (NPBN) direct acyclic graph.

Once al the values are set by pressing the button “compute” the synthetic WIM observations will be generated and exceedance probability plots of total weight and total vehicle length will be shown.  The computed data can be stored in a csv file by pressing the button “save CSV” 

More information can be found in the Quick User Guide file 

## Installation
Download and extract WIM_NPBN_GUI.rar file. Double click on the file extracted file (in some cases it is needed to add an exception in your antivuris). 


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GNU](https://choosealicense.com/licenses/gpl-3.0/)
