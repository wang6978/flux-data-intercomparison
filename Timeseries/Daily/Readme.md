
# Daily Timeseries Intercomparison plot 

Author: Carlos Wang <br/>
Contact: cawang@csumb.edu

## Overview

This code uses [Plotly](https://plot.ly/python/) to graph inrercomparison between different models and flux data. The remote sensing data was retrived from a static pixel grid with a spatial resolution of 30m in the form of 3x3 or 5x5 or 7x7. <br/>
The [Jupyter Notebook](https://github.com/wang6978/flux-data-intercomparison/blob/master/Timeseries/Daily/Daily_Intercomparison.ipynb) in this folder provides an example of the code execution using a sample site. </br>
The output plot is an interactive plot with: 1) zoom with cursor scroll; 2) zoom with rangslider; 3) hover information; 4) dropdown menu of each individual model. For specific multi-model intercomparison, simply click the icon to turn off any models.

## Methodology
### For Micrometeorological Measurements 
The data were processed using the [flux-data-qaqc](https://flux-data-qaqc.readthedocs.io/en/latest/)
  
### For Remote Sensing Model Data 
