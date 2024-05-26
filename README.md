<h1 style="display: inline"> 
<img alt=EOmaps src=https://raw.githubusercontent.com/raphaelquast/EOmaps/dev/docs/_static/logo.png align="left" width=100px style="margin:0 2em 0 0;">
<b>GeoPython 2024</b>  Workshop 
</h1>
<br>

This repository contains the code and data for the [EOmaps](https://eomaps.readthedocs.io) workshop @[GeoPythyon2024](https://2024.geopython.net).

## Setup

First navigate to your desired working directory and clone this repository. 

You can then setup all you need with `venv/pip` or `conda/mamba`:

<br>

<table>
<tr>
<td valign="top" width="50%">

🐍 **Installation with pip / venv**  
  
> No working `python`?  Install [python](https://www.python.org/downloads/)!

---

1. Create a new environment:  
    `python -m venv "eomaps_geopython24"`
2. Activate the environment (see [python docs](https://docs.python.org/3/library/venv.html#how-venvs-work)):  
    windows: `eomaps_geopython24\Scripts\activate`  
    posix: `source eomaps_geopython24\bin\activate`  
4. Install required packages:  
   `pip install eomaps[all] jupyterlab`

</td>
<td valign="top" width="50%">

🐍 **Installation with conda / mamba**  
  
> No working `python + conda/mamba`?  Install [miniforge](https://github.com/conda-forge/miniforge)!

---

1. Ceate a new environment and install packages:  
    `mamba create -n "eomaps_geopython24" -c conda-forge eomaps jupyterlab netcdf4 ipywidgets`
2. Activate the environment:  
    `mamba activate "eomaps_geopython24"`

</td></tr>
</table>

Once the installation is done, navigate to the folder containing the cloned repository and run 
`jupyter lab`

1. [Introduction](<0_introduction.ipynb>)
2. [EOmaps Basics](<1_basics.ipynb>)
3. [Data Visualization](<2_data_visualization.ipynb>)
4. [Spatio-temporal analysis](<3_spatiotemporal_analysis.ipynb>)
6. [Irregularly sampled data](<4_irregularly_sampled_data.ipynb>)

---

<br>

### References
The example datasets are small subsets of the following (open access) datasets:

- **gridded_data**: [Copernicus Global Land - Global 0.1° gridded Soil Water Index][swi_data]
- **swath_data**: [HSAF - MetOp ASCAT Surface Soil Moisture 6.25km NRT product][ssm_data]

[ssm_data]: https://hsaf.meteoam.it/Products/ProductsList?type=soil_moisture  
[swi_data]: https://land.copernicus.eu/en/products/soil-moisture/daily-soil-water-index-global-v3-0-12-5km