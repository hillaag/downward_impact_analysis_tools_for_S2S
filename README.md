#

This code is for scientific processing and analysis of netCDF data. 
It is used for analysis of the surface response to extreme events in Earth's stratosphere, known as Sudden Stratospheric Warmings (SSW) and strong polar vortex evnets. We use two types of datasets:
* ERA-5 reanalysis
* ECMWF forecasts issued for the S2S (Subseasonal to seasonal) prediction ongoing research project (https://www.ecmwf.int/en/research/projects/s2s)
  
#
---------------------------------------

## Required data for the code:
* Extratropical cyclone frequency in ERA-5 (Hersbach et al., 2020), detected using the Wernli and Schwierz (2006) detection algorithm, refined in Sprenger et al. (2017).
* Extratropical cyclone frequency in ECMWF S2S ensemble forecasts, based on mean sea level pressure and detected by the same methodology.
* 
* Other atmospheric fields used: U10, U850, Z100.

## more details:
* For the majority of our analysis, we use ECMWF reforecasts from the model cycle 46R1 with 24-hourly instantaneous output.
* For full cyclone track life cycles, we use 6-hourly output from several ECMWF model versions with the cycles 47R1, 47R2 and 47R3.
* SSWs are defined as a reversal of the zonal mean zonal winds at 60$^\circ$N and 10 hPa from westerly to easterly during the extended winter period from November to March, excluding final warming events. The central date of the SSW is defined as the first day on which the daily zonal mean zonal winds are easterly. This definition follows  Charlton and Polvani (2007) and is commonly used in the literature Butler et al., 2017.
* For more details on the downward impact after SSW events, see: Afargan-Gerstman and Domeisen, 2020 and Afargan-Gerstman et al., 2022.

## For questions and further data requests, please contact:
Dr. Hilla Afaragn-Gerstman (ETH, Zurich)
Hilla.Gerstman@env.ethz.ch

## How to cite
If you use this code or parts of it for your published work, please include a citation to this repository or to our paper DOI (currently under revision in WCD): https://wcd.copernicus.org/preprints/wcd-2022-58/

# References 
* Afargan‐Gerstman, H. and Domeisen, D.I.V, 2020. Pacific modulation of the North Atlantic storm track response to sudden stratospheric warming events. Geophysical Research Letters, 47(2), p.e2019GL085007.
* Afargan-Gerstman, H., Jiménez-Esteve, B. and Domeisen, D.I.V, 2022. On the Relative Importance of Stratospheric and Tropospheric Drivers for the North Atlantic Jet Response to Sudden Stratospheric Warming Events. Journal of Climate, 35(19), pp.2851-2865.
* Butler, A.H., Sjoberg, J.P., Seidel, D.J. and Rosenlof, K.H., 2017. A sudden stratospheric warming compendium, Earth System Science Data, 9, 63–76.
* Charlton, A.J. and Polvani, L.M., 2007. A new look at stratospheric sudden warmings. Part I: Climatology and modeling benchmarks. Journal of climate, 20(3), pp.449-469.
* Hersbach, H., Bell, B., Berrisford, P., Hirahara, S., Horányi, A., Muñoz‐Sabater, J., Nicolas, J., Peubey, C., Radu, R., Schepers, D. and Simmons, A., 2020. The ERA5 global reanalysis. Quarterly Journal of the Royal Meteorological Society, 146(730), pp.1999-2049.
* Sprenger, M., Fragkoulidis, G., Binder, H., Croci-Maspoli, M., Graf, P., Grams, C.M., Knippertz, P., Madonna, E., Schemm, S., Škerlak, B. and Wernli, H., 2017. Global climatologies of Eulerian and Lagrangian flow features based on ERA-Interim. Bulletin of the American Meteorological Society, 98(8), pp.1739-1748.
* Wernli, H. and Schwierz, C., 2006. Surface cyclones in the ERA-40 dataset (1958–2001). Part I: Novel identification method and global climatology. Journal of the atmospheric sciences, 63(10), pp.2486-2507.

# Acknowledgement
This work is based on S2S data. S2S is a joint initiative of the World Weather Research Programme (WWRP) and the World Climate Research Programme (WCRP). The original S2S database is hosted at ECMWF as an extension of the TIGGE database”. For dataset source, please cite: Vitart et al.,The Sub-seasonal to Seasonal (S2S) Prediction Project Database. Bull. Amer. Meteor. Soc., 98(1), 163-176. doi: http://dx.doi.org/10.1175/BAMS-D-16-0017.1.
