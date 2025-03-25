# Time Series Plots

This repository contains tutorials dedicated to plotting time series of climate data taken from climate model simulations.

Contents are as follows:

1. Read in Climate Data + Plotting a Time Series: Walks the user through the process of loading in a file already located on a local machine, calculating a global average, and plotting the resulting time series. No area weighting is applied to the grid cells.

2. Regional Average Tutorial: Explains how to construct a mask to filter regions within a desired area of interest, then compute the average over that region and plot the resulting time series. Again, no area weighting is applied.

3. Weight Grid Cells + Plot Global Average: Provides instructions on computing weights based on the area of grid cells in a given model, so that areas with more points are not "overcounted". Shows the impact of area weighting on estimates of global-mean temperature.
