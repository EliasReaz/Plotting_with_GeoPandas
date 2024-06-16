# Plotting_with_GeoPandas
**Plotting fish biomass density in Lake Erie**

I plot changes in densities of fish biomass in Lake Erie over every 4 year since 1990 and by locations (Latitude and Longitude). 

The intend was to help one of my friends working in a Fesheries and Oceans Canada (FOC) project. 
He had fish biomass densities by Latitude, Longitude, and year (1990 to 2018). A sample of first few rows:

|year |  Latitude| Longitude| fish_biomass_density|
|---  |---       |---       |---                   |
|1990	| 42.716354| -80.267646| 0.899300|
|1990	| 42.769625|	-80.156729 | 0.908676|
|1990|	42.770667|-80.161854 | 0.901743|

The object was to map these biomass densities into Lake Erie map over time (every 4 years) and by locations.

I downloaded the shape file of Lake Erie 'hydro_p_LakeErie.shp' from https://www.sciencebase.gov/catalog/item/530f8a0ee4b0e7e46bd300dd.
