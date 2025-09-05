# VAMPIRE: Van Allen belt Multi-day Predictions by Implementing a Random forest for Electrons

An outer Radiation Belt forecasting model, predicting if the maximum daily 1.8MeV Electron Flux or daily 1.8MeV Electron Fluence will exceed set thresholds.

The model uses a random forest methodology and uses selected inputs from the OMNI dataset, with the flux measurements from Van Allen Probe,

Within the Example Notebooks folder there are several python notebooks. Firstly one for VAMPIRE-X and VAMPIRE-E, with thresholds at the 60th percentile as first described in Weston et al. 2025 ![DOI:10.22541/essoar.175611399.91318861/v1](https://essopenarchive.org/users/956407/articles/1325373-vampire-using-a-random-forest-to-forecast-earth-s-outer-van-allen-radiation-belt)] where the threshold is set and downloads datasets and pretrained forests from https://zenodo.org/records/15130352.
There is also an example notebook demonstrating the performance of a suite of VAMPIRE-X models, thresholds set at the 60th, 70th, 80th, 90th, and 95th Percentiles, also downloading the data and pre-trained forests from a zenodo repository (https://zenodo.org/records/17062872)

Each Notebook is designed to run in google colab and will import each of the required package versions. 
