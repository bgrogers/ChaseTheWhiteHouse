This folder has our implementation of the Linzer Model for presidential election forecast.

http://www.tandfonline.com/doi/abs/10.1080/01621459.2012.737735

This code is borrowed and adapted from Pierre-Antoine Kremp's implementation: http://www.slate.com/features/pkremp_forecast/report.html

The polls were taken from Economist.com as was the 2016 election results (to update the priors)

To run, you'll need to change line 76 of runmodel2020.R from _all_polls <- read.csv('/Users/matthewthomas/UVa_DS/Capstone/Economist_Model/data/2020polls.csv')_
to your own directory
