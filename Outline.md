# EMISSION MAPPING FOR MULTISPECIES OF ATMOSPHERIC POLLUTANTS OVER THE CONUS

### Aasma Acharya
### CLIM 680

## INTRODUCTION
My CLIM680 project will explore the emission pattern for different species of atmospheric pollutants basically to see how the emission varies spatially within the CONUS. This project will analyze annual total emissions for VOCs, NOx, PM2.5, SO2, CO, and NH3 measured in terms of ton/km2/yr.


## DATA
Neighborhood Emission Mapping Operation : The NEMO (http://air.csiss.gmu.edu/) provides  annual, monthly and hourly
fine scale emissions data at 1km spatial resolution.

And, I will be using the geo registration data of this dataset which provides the  latitude and longitude coordinates for the visual representation. 


## PROPOSED ANALYSIS
I plan to use the data sets above to conduct the following analysis:

Calculate annual mean and climatology of the emissions for the given species

Calculate composites based on Air quality Index

Compare the emissions plots of remaining species with PM2.5 mainly to see the responses of increase or reduction of SO2, NO2 emission on the PM2.5 concentration. Maybe with a regression analysis

Calculate the anomaly in emission of PM2.5


## Functions
I will create a set of functions in clim_utils.py for doing common tasks used throughout my analysis, including:

a. Labelling plots

b. calculating climatology, anomalies and composites etc.



## Conda environment
  The environment.yml file is provided to define the environment needed to run all codes.
 

                      
