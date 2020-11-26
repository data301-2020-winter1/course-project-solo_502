[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=311722&assignment_repo_type=GroupAssignmentRepo)
# Group 502 - {Climate Change in ski resorts of the West}

- Your title can change over time.

## Milestones

Details for Milestone are available on Canvas (left sidebar, Course Project) or [here](https://firas.moosvi.com/courses/data301/project/milestone01.html).

## Describe your topic/interest in about 150-200 words

>Climate change is affecting our environments in unprecedented ways and changes are happening faster than ever. 
My research is trying to observe which of these changes can be measured and shown in western North America, notably at ski resorts, 
with the help of meteorological data dating back to 1901. For this analysis, 
I have chosen a few locations for which I will thoroughly analysize the climate data of the past and projected climate trends in the future for now. 
The main focus lays on climatic data which is important for the ski industry such as snowfall and temperature.
The python code will then be used to organize and evaluate data for multiple other locations of ski resort in western North America.
I'm interested in what climate trends are observable with the given data for the last 120 years and 
which changes are projected to occur in the observed variables until the year 2085. This means that examined trends 
in the data must be found and subsequently tested on their statistical significance.
General trends in climate can be seen as a warming of the atmosphere, overall more, 
heavier precepitation events but also more frequent regional droughts. Climate change often presents itself 
as a shift in regional climates and I would like to see which of these changes are manifesting at the chosen locations in the region.
I expect to observe a decline in precipiation (snow) at coastal ski resorts in more recent times while continental 
ski resort will be less affected.

## Describe your dataset in about 150-200 words

>The dataset is provided by ClimateBC and ClimateNA, meteorological websites managed by Dr. Wang of the University of British Columbia. 
The websites provide the opportunity to generate and download historic meteorological data taken by weather stations 
for any location in British Columbia and North America respectively. 
The data is a yearly analysis between 1901 and 2019 of meteorological phenomena such as temperature, 
precipitation, evaporation, solar radiation and many more. It also provides highly detailed analysis for each year 
for the amount of days above a certain temperature, temperature extremes and precipitation for each season. 
Additionally, the data from ClimateBC and ClimateNA provides estimates of all the above variables for the years 2025, 
2055 and 2085 under the official Representative Concentration Pathways (RCPs) RCP4.5 and RCP8.5 
from the Intergovernmental Panel on Climate Change (IPCC).
I chose to analyze the mentioned data at two standpoints (to write the Python code for now): 
At the Big White ski resort and the Whistler Blackcomb ski resort.
because of my personal interest in those two standpoints. I would be happy to observe typical changes in the two locations, 
but of course the conclusions of my analysis are limited by only investigating mentioned standpoints at this point in my project.

## Team Members

Wendelin Giesler: I'm a German graduate student studying climatology with a background in environmental sciences and in economics.

## References

[ClimateBC](http://climatebc.ca/)
[ClimateNA](http://climatena.ca/)

## Organization of the Project

>The *data* directory contains the raw and the processed data. 
The *analysis* directory contains the project function (*project_function*) used to clean and wrangle the data as well as 
individual notebooks (*ski resort scripts*) for each ski resort in the *scripts* subdirectory. In each notebook, the ski resort data gets
analyzed, cleaned and visualized using the same code. The specific conclusions and comments are 
results of the graphs in each individual notebook. The graphs are saved in the *images* directory for further comparison.
Since I wrote the code while analyzing data for data from Whistler, the file **Whistler_analysis** contains my main analysis in the form of
very specific explanations, comments and interpretations of my code and data. 
All the other notebooks are simply copies of said code that analyze thedata from a different locations. 
Hence the explanations are not quite as detailed in these additional notebooks.

## Future work

> Depending on the nature of the future milestones I will adapt the analysis of this project. This could include investigation of more ski 
resorts, detailed comparisons of the analyzed ski resorts or simply an extension of the current analysis with different or additional graphs.
