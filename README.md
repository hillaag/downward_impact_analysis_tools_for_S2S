#

This code is for scientific processing and analysis of netCDF data. 
It is used for analysis of the surface response to extreme events in Earth's stratosphere, known as Sudden Stratospheric Warmings (SSW) and strong polar vortex evnets. We use two types of datasets:
* ECMWF forecasts issued for the S2S (Subseasonal to seasonal) prediction ongoing research project (https://www.ecmwf.int/en/research/projects/s2s)
* ERA-5 reanalysis
#
---------------------------------------

## Required data:
* Extratropical cyclone frequency in ECMWF ensemble forecasts, based on mean sea level pressure and detecteed using the Wernli and Schwierz (2006) detection algorithm, refined in Sprenger et al. (2017).
* Extratropical cyclone frequency in ERA-5 (Hersbach et al., 2020), detected by the same methodology.
* Other atmospheric fields used: U10, U850, Z100.
* 

## more details:
* For the majority of our analysis, we use ECMWF reforecasts from the model cycle 46R1 with 24-hourly instantaneous output,
* For full cyclone track life cycles, we use 6-hourly output from several model versions with the cycles 47R1, 47R2 and 47R3.

## For questions and further data requests, please contact:
Dr. Hilla Afaragn-Gerstman (ETH, Zurich)
Hilla.Gerstman@env.ethz.ch

## How to cite
If you use this code or parts of it for your published work, please include a citation to this repository or to our paper DOI (currently under revision in WCD): https://wcd.copernicus.org/preprints/wcd-2022-58/
