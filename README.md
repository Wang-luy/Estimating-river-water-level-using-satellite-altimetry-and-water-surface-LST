# Estimating-river-water-level-using-satellite-altimetry-and-water-surface-LST

River water level (RWL) is an important parameter for evaluating hydrologic regimes. In recent years, RWL estimation based on remote sensing techniques has drawn great attention to the hydrologic community even with relatively low temporal resolution but acceptable accuracy. The techniques adapt well in wide rivers with little disturbance, while they have not been fully tested in heavily regulated rivers. In this study, we tested two methods for RWL estimation in the subtropical Dongjiang River. One is based on satellite altimetry data, and the other is based on day-night water temperature gradients. After elaborate data processing and algorithm selection, we found that the Jason data with a ~10-day revisit period were insightful, and can be used well for daily RWL simulations. Meanwhile, the temperature-based seasonal linear model reproduced well the daily observations in this regulated river.

The Jason satellite altimetry datum and AMSR-2 datum were processed by Panoply and Matlab-R2022a, 
the MODIS and surface reflectance images were processed by the Google Earth Engine platform, 
the daily water level observations were processed by Excel. 

The Jason series satellites dataset are download in (ftp://avisoftp.cnes.fr/AVISO/pub/jason-2/sgdr_d/ and ftp://avisoftp.cnes.fr/AVISO/pub/jason-3/sgdr_d/).

The AMSR2 dataset are download in https://search.earthdata.nasa.gov/search.

And there are some code of data processing methods.


