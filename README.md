# Time Series Plots

This repository contains tutorials dedicated to plotting time series of climate data taken from climate model simulations.

Contents are as follows:

1. Read in Climate Data + Plot a Regionally Averaged Time Series: Walks the user through the process of loading in a file already located on a local machine, constructing a mask to filter regions within a desired area of interest, calculating a regional average, and plotting the resulting time series. No area weighting is applied to the grid cells.

2. Annual Averaging and Fit Trend Line: Performs the same file loading and regional averaging steps as tutorial 1, then performs an annual average on the time series and fits a trend line (line of best fit) to the data.

3. Weight Grid Cells + Plot Global Average: Provides instructions on computing weights based on the area of grid cells in a given model, so that areas with more points are not "overcounted". Shows the impact of area weighting on estimates of global-mean temperature.
