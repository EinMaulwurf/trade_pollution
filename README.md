# trade_pollution

When cloning from github, take note that some large files are not included and have to be created again. These are `data_isd_lite_combined.csv` and `grid_small_final.nc`. However, for calculations, only the second file is needed. To get it, first run `data_isd_lite_mean <- st_read("data_isd_lite_mean.gpkg")` and then continue with the `# Interpolation` section and uncomment the `writeCDF(…)` function at the end.

There is no need to rerun the `# Download data` section, everything is already in `data_isd_lite_mean.gpkg`.