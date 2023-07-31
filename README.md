# greens-function

[![DOI](https://zenodo.org/badge/155776110.svg)](https://zenodo.org/badge/latestdoi/155776110)


A netcdf file containing six Green's functions computed from CAM5 simulations of Zhou et al. (2017).

The file contains maps quantifying the globally averaged TOA radiative flux anomalies due to anomalies in the following fields that are themselves attributable to sea surface warming at each location.
1. surface + atmospheric temperature, and its break down into vertically-uniform (Planck) and vertically-nonuniform (lapse rate) components 
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

See Also
----------
CAM4 Green's functions developed by Dong et al. have been kindly provided at [Yue Dong's website](https://sites.google.com/view/yuedong-atmos/data?authuser=0).
Several other modeling groups are in the process of constructing Green's functions and an intercomparison project has been proposed to standardize the procedure. Read more at the [GFMIP website](https://gfmip.org/).
