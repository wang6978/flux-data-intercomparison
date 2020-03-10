# Timeseries Plot
## Overview
This directory provides code and examples to generate timeseries plots on daily and monthly scales. The code uses [Plotly](https://plot.ly/python/) to graph inrercomparison between different models and flux data. The remote sensing data was retrived from a static pixel grid with a spatial resolution of 30m in the form of 3x3 or 5x5 or 7x7. <br/>

## Variables
### Micrometeorological Measurement
The flux data were processed using the [flux-data-qaqc](https://flux-data-qaqc.readthedocs.io/en/latest/).
In addition to correted/closed latent heat flux (LE), the uncorrected/unclosed LE was also included as a plotting variable. Note that LE values were converted to evapotranspiration (mm) before plotting. In the timeseries, we established a band (shaded) between closed and unclosed LE. As opposed to only comparing the model data to corrected LE, this provides a dimensional comparison for a better visualization. 

### Remote Sensing Data
