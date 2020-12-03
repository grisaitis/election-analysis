# election-analysis

this repo contains code for producing maps of election results in Python

uses the following libraries
- [tabula-py](https://github.com/chezou/tabula-py) for parsing PDF files
- pandas and geopandas for geospatial data manipulation
- plotly for visualization

<img src="https://raw.githubusercontent.com/grisaitis/election-analysis/main/figures/choropleth_margin_frac_twoway_dem_2020.jpg" width="80%">

### set up environment

```
conda env create --file conda-environment.yml
conda activate election-analysis
jupyter labextension install jupyterlab-plotly@4.12.0
```

```
jupyter lab
```

### view notebooks

https://nbviewer.jupyter.org/github/grisaitis/election-analysis/tree/main/
