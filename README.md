# greens-function

[![DOI](https://zenodo.org/badge/155776110.svg)](https://zenodo.org/badge/latestdoi/155776110)

The following Green's functions are provided in the [data directory](https://github.com/mzelinka/greens-function/tree/master/data):
- Zhou_etal_2017_GreensFunction.nc: computed from 5-year CAM5 simulations of Zhou et al. (2017)
- Zhou_etal_2020_GreensFunction.nc: computed from 40-year CAM5 simulations of Zhou et al. (2020)

Zhou_etal_2017_GreensFunction.nc contains maps quantifying the globally averaged TOA radiative flux anomalies due to anomalies in the following fields that are themselves attributable to sea surface warming at each location:
1. vertically-uniform (Planck) temperature response
2. vertically-nonuniform (lapse rate) temperature response
3. atmospheric water vapor
4. clouds

Zhou_etal_2020_GreensFunction.nc contains maps quantifying the globally averaged TOA radiative flux anomalies due to anomalies in the following fields that are themselves attributable to sea surface warming at each location:
1. vertically-uniform (Planck) temperature response, for both the conventional and constant-RH breakdown
2. vertically-nonuniform (lapse rate) temperature response, for both the conventional and constant-RH breakdown
3. atmospheric water vapor, both the change in absolute humidity and the change in RH
4. clouds + their LW and SW components
5. surface albedo

Convolving these Green's functions with sea surface temperature anomalies provides an estimate of the global mean change in radiation due to changes in temperature, water vapor, or clouds.

Each netcdf file also contains a surface temperature Green's function, which quantifies the globally averaged surface temperature anomaly due to sea surface warming at each location.

References
----------
- Zhou, C., M. D. Zelinka, and S. A. Klein, 2017: Analyzing the dependence of global cloud feedback on the spatial pattern of sea surface temperature change with a Green’s Function approach, *J. Adv. Model. Earth Syst.*, **9**, 2174-2189, [doi:10.1002/2017MS001096](http://onlinelibrary.wiley.com/doi/10.1002/2017MS001096/abstract).
- Zhou, C., Y. Hu, J. Lu, and M. D. Zelinka, 2020: Responses of the Hadley Circulation to regional sea surface temperature changes, _J. Climate_, **33**, 429-441, [doi:10.1175/JCLI-D-19-0315.1](https://journals.ametsoc.org/view/journals/clim/33/2/jcli-d-19-0315.1.xml).

Figure
----------
See the [images directory](https://github.com/mzelinka/greens-function/tree/master/images) for maps of the Zhou et al. (2020) Green's functions.

See Also
----------
CAM4 Green's functions developed by Dong et al. have been kindly provided at [Yue Dong's website](https://sites.google.com/view/yuedong-atmos/data?authuser=0).
Several other modeling groups are in the process of constructing Green's functions and an intercomparison project has been proposed to standardize the procedure. Read more at the [GFMIP website](https://gfmip.org/).
