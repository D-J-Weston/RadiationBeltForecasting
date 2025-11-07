# VAMPIRE: Using a Random Forest to Forecast Earth’s Outer Van Allen Radiation Belt
 **V**an **A**llen Belt **M**ulti-day **P**redictions by **I**mplementing a **R**andom Forest for **E**lectrons
 [![DOI](https://zenodo.org/badge/950518739.svg)](https://doi.org/10.5281/zenodo.17552557)
An outer Radiation Belt forecasting model, predicting if the maximum daily 1.8MeV Electron Flux or daily 1.8MeV Electron Fluence will exceed set thresholds.

The model uses a random forest methodology and uses selected inputs from the OMNI dataset, with the flux measurements from Van Allen Probe,

Within the Example Notebooks folder there are 2 python notebooks. One for VAMPIRE-X and one for VAMPIRE-E, with thresholds at the 60th percentile as first described in Weston et al. 2025 [![DOI10.22541/essoar.175611399.91318861/v1](http://img.shields.io/badge/DOI-10.22541/essoar.175611399.91318861/v1-B31B1B.svg)](https://doi.org/10.22541/essoar.175611399.91318861/v1) where the threshold is set and downloads datasets and pretrained forests from https://zenodo.org/records/15130352.

Example notebooks demonstrating the performance for a suite of VAMPIRE-X models, thresholds set at the 60th, 70th, 80th, 90th, and 95th Percentiles, also downloading the data and pre-trained forests from a zenodo repository (https://zenodo.org/records/17062872) can be found here: https://github.com/D-J-Weston/RadiationBeltForecastingSuite/ 

Each Notebook will import each of the required package versions. 
