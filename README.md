## WIM NPBN GUI
## A Non-parametric Bayesian Network for multivariate probabilistic modelling of Weigh-in-Motion System Data

The Graphical User Interface WIM NPBN computes synthetic Weigh-in-Motion (WIM) data. The synthetic observations are similar to those observed in April 2013 in three Dutch highway WIM locations in both, the right (R) and the left (L), driving directions. The measurements were taken in highways A12 (km 42) Woerden, A15 (km 92) Gorinchem, and A16 (km 41) Gravendeel. Additionally, a hypothetical highway was created which is a combination of all six available WIM locations in the model. Therefore, each simulated vehicle randomly chooses one of the locations to compute the synthetic data.

The 26 codes (Vehicle types) used in the GUI NPBN WIM consist of a letter and a number that define the number of axles. The letter represents the vehicle configurations: Buses (B), Tractor - Semitrailer - Trailer ('R), Tractor - Semitrailer (T), Single-unit multi-axle vehicle and/or Single unit multi-axle vehicle - Semitrailer (V) and Others vehicles (O). For example, a seven-axle vehicle with the configuration Tractor - Semitrailer is coded as T7. 

In the main window of the GUI. The user can choose between the 26 vehicle types and the 7 locations (A12-L, A12-R, A15-L, A15-R, A16-L, A16-R and Hypothetical). To compute the desired amount of WIM Observation and the desired units (kN, kg, t, m, cm).   

There are, three main check boxes: 1) vehicle type subset, 2) correlation matrix plot and 3) Bayesian network plot.

1. If the _vehicle type subset_ check box is selected, the user needs to select the desired vehicles types and provide their corresponding proportions (or the probability of observing each vehicle type). Otherwise, 26 vehicle types will be used to generate synthetic observations. 
2. If the _correlation matrix plot_ check box is selected, the rank correlation matrix plot will be shown as a colour map. 
3. If the _Bayesian network plot_ check box is selected, the Non-Parametric Bayesian Network (NPBN) direct acyclic graph will be shown.

Once all the values are set by pressing the _compute_ button the synthetic WIM observations will be generated and histograms of total vehicle weight and total vehicle length will be shown, as well as, the exceedance probability plots (Fig. 5 and 6).  The computed data can be stored in a CSV file by pressing the _save CSV_ button.  

More information can be found in the Quick User Guide file. 

## Installation
Download and extract WIM_NPBN_GUI.rar file. Double click on the file extracted file (in some cases it is needed to add an exception in your antivuris). 


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GNU](https://choosealicense.com/licenses/gpl-3.0/)
