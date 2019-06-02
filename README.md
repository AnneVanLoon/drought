# drought
Drought analysis with the threshold method

TOTAL SCRIPT:

- Drought_total.r: Script to calculate a threshold, do drought analysis and plot droughts

OR SEPERATE SCRIPTS:
(use if you want to use other data (e.g. other catchment / other time period) to calculate threshold or if you only want to execute part of the script with pre-saved data)

- Threshold.r: Script to calculate a fixed or variable threshold from duration curves and write to file (if threshold level is pre-determined, skip this, and make threshold file manually) 
- Drought_analysis.r: Script to calculate drought charactersitics from threshold and write to file 
- Drought_plots.r: Script to plot droughts & drought charactersitics with threshold (can also be done after pooling)
- Drought_pooling.r: Script to pool droughts & remove minor droughts
- Drought_characteristics.r: Script to calculate average & maximum drought characteristics (can be done on pooled/unpooled droughts, with minor droughts in/out)

FUNCTIONS:
(functions need to be in same directory)

- Threshold_functions.r
- Drought_functions.r
- Pooling_functions.r
- Characteristics_functions.r

For information about the threshold level method, please refer to Van Loon, A.F. (2015). Hydrological drought explained. Wiley Interdisciplinary Reviews: Water, 2(4), 359-392.
