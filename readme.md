# Introduction

The repository played the primary backbone of the product presented at a prestigious international competition - [Teknofest](https://teknofest.org/en/). We developed a satellite-driven solution primarily powered by a semi-empirical model called [Dubois (1995)](https://ieeexplore.ieee.org/document/406677). The product takes the input of radar imagery and estimate soil moisture distribution across the given farm. The radar data was provided by [Sentinel 1](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Sentinel-1). We also integrate multi-spectral data from [Sentinel 2](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Sentinel-2) to visually represent the farm so that the user can analyze predictions along with the visible view. The sample data is available in the repository. 

Moreover, the product takes the advantage of weather predictions to interpret potential future soil moisture variation that may be influenced by the upcoming weather parameters. The idea is to provide daily update to farmers by analyzing possible future impacts while reducing the gap between each revisit time of the satellite. Sentinel 1 and 2 have 6-10 days of period to revisit the given location. The revolutionary approach shows the promising aspect of satellites in precision agriculture to be used in large farms. Hence, we use IBM **historical** weather data as a scenario of available weather forecasting data to interpret the impact on soil moisture distribution.

The product not only considers soil moisture but also suggests predicting NPK distribution of the farm with multispectral satellite data. However, at this moment, we do not use a model for this, yet.
