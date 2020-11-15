### The /analysis directory contains all jupyter notebook files used for the project.

The /scripts subdirectory includes the jupyter notebook project_function as well as the notebooks to visualize the data for each ski hill.

>The *analysis* directory contains the project function (*project_function*) used to clean and wrangle the data as well as 
individual notebooks (*ski resort scripts*) for each ski resort in the *scripts* subdirectory. In each notebook, the ski resort data gets
analyzed, cleaned and visualized using the same code. The specific conclusions and comments are 
results of the graphs in each individual notebook. The graphs are saved in the *images* directory for further comparison.
Since I wrote the code while analyzing data for data from Whistler, the file **Whistler_analysis** contains very specific explanations,
comments and interpretations of my code and data. All the other notebooks are simply copies of said code that analyze the
data from a different locations. Hence the explanations are not quite as detailed in these additional notebooks.

## Variables of interest in the analyzed data.
Key to variables that are used in the analysis.

*annual:*
- MAT - mean annual temperature (°C)
- MWMT - mean warmest month temperature (°C)
- MCMT - mean coldest month temperature (°C)
- DD<0 - degree-days below 0°C, days multiplied by the amount of degrees below freezing.
- PAS - precipitation as snow (mm). Covers timeline August(previous year) - July (current year)
- MAR - mean annual solar radiation (MJ m^(-2) d^(-1))
- RH - mean annual relative humidity

*seasonal:*
- Tave_wt - winter mean temperature (°C)
- Tmax_wt - winter mean maximum temperature (°C)
- Tmin_wt - winter mean minimum temperature (°C)
- PPT_wt - winter precipitation
- RAD_wt - winter solar radiation (MJ m^(-2) d^(-1))
- DD_0_wt - winter degree-days below 0°C
- DD5_wt - winter degree-days above 5°C
- NFFD_wt - number of frost-free days
- PAS_wt - winter precipitation as snow (mm)
- RH_wt - winter relative humidity (%)

*monthly:*
- Tmax(XX) - max termperature in month XX (°C)
- Tmin(XX) - min termperature in month XX (°C)
- Tave(XX) - mean termperature in month XX (°C)
- Prec(XX) - precipitation in month XX (mm)
- DD<0(XX) degree-days below 0°C in month XX
- PAS(XX) - precipitation as snow in month XX (mm)
- RH(XX) - relative humidity in month XX (%)
