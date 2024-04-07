# trade_pollution

When cloning from github, take note that some large files are not included and have to be created again. These are `data_isd_lite_combined.csv` (and the whole `data_isd_lite` subdirectory) and `grid_small_final.nc`. However, for the calculations with the firm data, these are not needed as everything important is inside `data_isd_lite_mean.gpkg`.

Just run the last chunk from `# Save raster` as well as the two first chunks in `# Calculations with firm data`. Then you should be good to go to run the remaining chunks.