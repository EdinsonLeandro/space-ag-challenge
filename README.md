# Space AG: Challenge

This challenge was part of a technical job interview for the company [Space AG](https://www.spaceag.co/)

## NDVI.
NDVI is a vegetation index that measures plant vigor, essentially an indirect measurement of plant health. The values of this index range from -1 to 1. Higher NDVI values in a given image pixel suggest higher crop biomass, meaning a healthier crop. Lower NDVI values suggest lower biomass or an unhealthy vegetation or crop area.

Generally, vegetation values fall between 0.2 and 1 on the NDVI scale. Soil typically has negative NDVI values up to 0.2. It's important to note that cloud cover over the area being assessed can affect the average NDVI.

Some avocado farmers believe there might be a relationship between NDVI and crop yield (Kg/Ha).

## The Challenge.

1. Extract satellite bands from Sentinel 2, for a specific study area and set of dates, using Sentinel Hub.
2. Extract average NDVI values.
3. Save the NDVI images.
4. Analyze the data to evaluate the NDVI behavior over time in the study area.
