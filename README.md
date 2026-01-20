# climate-teleconnections-paper2025
Repository for the Teleconnections paper from Cataldi et al. (2025)

This repository contains data processing and analysis scripts used in a research project funded by CNPq, focused on identifying ocean–atmosphere teleconnections associated with extreme drought and precipitation events.

## Scientific context
The project analyzes existing and newly developed climate indices to assess their influence on climate extremes, using observational and reanalysis datasets.
Paper URL: https://doi.org/10.3390/atmos16060699

## Data
Due to data volume and licensing constraints, raw datasets are not included.

Main datasets:
- NOAA OI SST v2 (0.25°, daily)
- ERA5 reanalysis (0.25°, hourly)
- NCEP R2 (2.5°, monthly)
- BR-DWGD (0.1°, daily)
- NOAA Climate indices

Data can be accessed via:
- [NOAA servers](https://psl.noaa.gov/data/gridded/data.noaa.oisst.v2.highres.html)
- [ERA5](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=overview)
- [NCEP servers](https://psl.noaa.gov/data/gridded/data.ncep.reanalysis2.html)
- [BR-DWGD](https://sites.google.com/site/alexandrecandidoxavierufes/brazilian-daily-weather-gridded-data)
- [NOAA servers](https://psl.noaa.gov/data/climateindices/list/)

## Methods
- Data preprocessing using xarray and Dask
- Feature construction from SST anomalies
- Statistical analysis using MK trend, correlation
- Evaluation across historical periods

## Repository structure
- `data/`: processed data
- `notebooks/`: exploratory analysis
- `shapes/`: shapefiles used for analysis and figures

## Disclaimer
This repository is provided for transparency and reproducibility of the scientific workflow. Some components are simplified for public release.



