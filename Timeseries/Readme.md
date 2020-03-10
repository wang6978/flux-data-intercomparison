# Timeseries Plot
## Overview
This directory provides code and examples to generate timeseries plots on daily and monthly scales. The code uses [Plotly](https://plot.ly/python/) to graph inrercomparison between different models and flux data. The remote sensing data was retrived from a static pixel grid with a spatial resolution of 30m in the form of 3x3 or 5x5 or 7x7. <br/>

## Variables
### Micrometeorological Measurement
The flux data were processed using the [flux-data-qaqc](https://flux-data-qaqc.readthedocs.io/en/latest/) </br>

In a post closure method, the missing energy is typically being assigned to other energy components, for example, latent heat flux (LE) and sensible heat flux (H), known as the bowen ratio method (Twine et al., 2000). By using this kind of post closure method, we are able to set the flux data to a "perfect" state. However, the caveat of this is that we do not know how to distinguish the missing energy from different possible soruces, such as systematic error, heat storage term, and etc yet... 

As a result, in addition to correted/closed LE, the uncorrected/unclosed LE was also included as a plotting variable. Note that LE values were converted to evapotranspiration (mm) before plotting. As opposed to only comparing the model data to corrected LE, we established a band (shaded) between closed and unclosed LE to provide a dimensional comparison for a better visualization.

### Remote Sensing Data

