# trade_pollution

When cloning from github, take note that some large files are not included and have to be created again. For that, uncomment the following:
- `write_csv(data_isd_lite_combined, "data_isd_lite_combined.csv")` 
- `st_write(data_isd_lite_mean, "data_isd_lite_mean.gpkg", append = FALSE)`

Then, run the whole code. Be aware that this might take a while, because all the data needs to be downloaded. Also, some calculations may take long.