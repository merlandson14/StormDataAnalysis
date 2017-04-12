# StormDataAnalysis
Storm Data Analysis of Injuries, Death and Crop, Property Damage

## Synopsis:
This is a very basic analysis of NOAA’s National Weather Service Storm Data for dates 1950 to November 2011. We are interested in looking at the effects of storms on population health and economic impact. We wish to examine which storm event causes the most fatalies and injuries and which storm types inflict the most property and crop damages.

## Methodology:
Reading through NOAA's documentation gives us a feel for the variables and storm types. For public health we are looking at `Fatalities` and `Injuries` and for economic impact we are looking at `PropDMG` and `CropDMG` with their associated exponential fields. We converted the exponential characters `K` and `M` to 1000 and 1000000, respectively, and then multipied them with the damage field to get actual values. Next we summarized the data values we wanted. Then we plotted the two sets, one for public health and one for economic loss. Finally, we gave our results, which ended up being `Tornado` in both cases.
