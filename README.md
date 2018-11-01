# greens-function
A netcdf file containing six Green's functions computed from CAM5 simulations of Zhou et al. (2017).

The file contains maps quantifying the globally averaged TOA radiative flux anomalies due to anomalies in the following fields that are themselves attributable to sea surface warming at each location.
1. atmospheric temperature, and its break down into vertically-uniform (Planck) and vertically-nonuniform (lapse rate) components 
2. atmospheric water vapor
3. clouds

Convolving these Green's functions with sea surface temperature anomalies provides an estimate of the global mean change in radiation due to changes in temperature, water vapor, or clouds.

The netcdf file also contains a surface temperature Green's function, which quantifies the globally averaged surface temperature anomaly due to sea surface warming at each location.

Reference
----------
Zhou, C., M. D. Zelinka, and S. A. Klein, 2017: Analyzing the dependence of global cloud feedback on the spatial pattern of sea surface temperature change with a Green’s Function approach, *J. Adv. Model. Earth Syst.*, **9**, 2174-2189, [doi:10.1002/2017MS001096](http://onlinelibrary.wiley.com/doi/10.1002/2017MS001096/abstract).

Figure
----------
See the [images directory](https://github.com/mzelinka/greens-function/tree/master/images) for maps of the six Green's functions.
