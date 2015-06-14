# Poster-on-Spatial-Statistics-2015
This repository contains my poster presented at Spatial Statistics: Emerging Patterns 2015 conference, in Avignon, France on June 12, 2015. The title of the poster is "Estimating pooled within-time series variograms with spatially shifted temporal points", reference number:  P3.03, abstract sequel: SPAT2015_0024. The poster was created using Latex a0poster and multicol packages.

#Abstract
Pooled within-time series (PTS) variograms are frequently used for geostatistical interpolation in spatial data-scarce regions if time series are available. The only available method for PTS variograms estimation averages semivariances computed for individual time steps over each spatial lag within a pooled time series. However, semivariances computed by a few paired comparisons in individual time steps are erratic and hence they may hamper precision of PTS variogram estimation. We developed an alternative method for estimating PTS variograms by spatializing temporal data points and shifting them. The pooled spatial data point sets from different time steps were assigned to different coordinate sets on the same space. Then a semivariance was computed for each spatial lag by comparing all point pairs separable by that spatial lag within a pooled time series. Finally, a PTS variogram was estimated by controlling the lower and upper boundary of spatial lags. Our method showed higher precision than the available method for PTS variogram estimation and was developed by using the freely available R open source software environment.

An article on this topic is currently under review in Hydrology and Earth System Sciences. Please refer to the "SSTP" repository to access the tool.
