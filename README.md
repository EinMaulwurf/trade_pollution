# Trade & Pollution

This repository contains the R code and data used for analyzing wind patterns in China and their relationship to firm-level pollution data.

## Overview

This project performs the following steps:

1. **Data Acquisition:** Downloads and processes wind data from the NOAA ISD-Lite dataset, focusing on stations within China for the period 1989-1999.
2. **Wind Data Processing:** Calculates average wind speeds and directions for each station. Interpolates these values to create a continuous raster layer of wind data across China.
3. **Firm Data Integration:** Combines the wind data with firm-level location data and pollution data from 2000 to 2006.
4. **Pollution Analysis:** Calculates various pollution metrics based on the wind data:
    -   Average and sum of PM2.5 concentrations in the 9 cells surrounding a firm.
    -   Inverse-distance-weighted average and sum of PM2.5 concentrations within a 45° downwind cone from each firm.
    -   Downwind cone calculations also considering prevalent wind speeds.

## Repository Structure

The repository is organized as follows:

- `analysis_1_wind.Rmd`: R Markdown file for downloading, processing, and interpolating wind data.
- `analysis_1_firms.Rmd`: R Markdown file for integrating firm-level data, pollution data, and wind data, and calculating the various pollution metrics.
- `data/`: Contains the downloaded data files and results of the analysis. Some of the files are not publicly available and are therefore not included in this repo.
- `plots/`: Contains the generated plots as .pdf or .jpg files.
