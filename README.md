# Data Labs notebooks

Python notebooks demonstrating time series analysis with NDBC and OOI data. They can be used as stand alone notebooks or in a live coding tutorial. Exercises are included throughout to reinforce concepts and promote interactivity.

* [NDBC wind analysis](NDBC_wind_analysis.ipynb)
  * Plotting time series vector data
  * Converting wind data from speed/direction to eastward/northward components
  * Rotation of wind vectors into new coordinate system
  * Principal axis analysis (2D example of principal component analysis)
  * [Background material](https://github.com/mlmldata2020/course-notes/blob/master/week07a-PCA-EOF.ipynb) (from course notes)

* [OOI ADCP analysis](OOI_ADCP_analysis.ipynb)
  * Introduction to xarray datasets (with depth and time coordinates)
  * Masking bad data
  * Depth averaging current meter data
  * Spectral analysis
