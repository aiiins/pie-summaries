# Summary Stats of Pie Chart Studies
This is a re-processing of the data we collected in [three studies on pie charts](https://eagereyes.org/papers/a-pair-of-pie-chart-papers) for a talk and a blog posting.
The idea is to present the data in a way that's readable to most people. In particular, use signed and absolute error instead of log error, and 95% confidence intervals instead of p-value testing and violin plots.

This repository contains all the data (copied from the original sources, see below), an R script to create the images, and a collection of images in three different formats.

## What's Where?
* `pie-summaries.R`: the R script that does all the magic
* `data`: the raw datasets
* `raw-pdf`: the PDFs exported from R, as well as the iDraw/Graphic files I used to create all the other images
* `pdf`: nice PDFs for each chart, with small images for the legend
* `svg`: SVGs of all of the charts with small images for the legend
* `png`: PNGs of all of the charts with small images for the legend

## Data Set Origin
The datasets in the `data` directory are copies of the files in the following repositories:
* `arcs-angles-areas-merged.csv` is a copy of the `merged-data.csv` file from https://github.com/dwskau/arcs-angles-area
* `donut-radii-merged.csv` is a copy of the `merged-data.csv` file from https://github.com/dwskau/donut-radii
* `pie-variations-enriched.csv` is a copy of the file of the same name from https://github.com/dwskau/pie-variations



