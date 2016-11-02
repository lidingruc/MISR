# MISR
Code for processing, integrating, mapping, and modeling local mode (4.4 km) MISR satellite data with air quality and meteorological data.

**File list**:

1. Data Processing
  * EPA Data Processing.R    Code to process downloaded EPA AQS air monitoring data (PM2.5, PM10, STN PM2.5)
  * MISR Data Processing.R   Code to extract local mode aerosol data from MISR netcdf files
  * NCDC Data Processing.R   Code to wget and process NOAA weather station data

2. Spatio-temporal Modeling and Mapping (See Franklin, Kalashnikova, Garay RSE 2016)
  * MISR AQS MET Match.R     Code to spatially and temporally link MISR AOD with AQS and meteorology data
  * MISR Mapping.R           Code to create maps and visualizations of MISR data
  * MISR PM2.5 Modeling.R    Code to conduct sptio-temporal modeling of MISR and PM2.5 
  * MISR PM10 Modeling.R     Code to conduct spatio-temporal modeling of MISR and PM10
  * MISR PM10-PM25 Modeling.R Code to conduct spatio-temporal modeling of MISR and PM10-PM2.5
  * MISR STN PM2.5 Modeling.R Code to conduct spatio-temporal modeling of MISR and PM2.5 chemical speciation 
