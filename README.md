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

<details><summary>Installation with <code>venv / pip</code> <b>[click to show]</b> </summary>

> No working `python` on your system?  >>> Install [python](https://www.python.org/downloads/)!

1. Navigate to your desired working directory and create a new virtual environment:  
    `python -m venv "eomaps_geopython24"`
2. Activate the environment (see [python docs](https://docs.python.org/3/library/venv.html#how-venvs-work) for details on different platforms and shells):  
    `eomaps_geopython24\Scripts\activate`
3. Install required packages:  
   `pip install eomaps[all] jupyterlab`
</details>

<br>

<details><summary>Installation with <code>conda / mamba</code> <b>[click to show]</b> </summary>

> No working `python + conda/mamba` on your system?  >>> Install [miniforge](https://github.com/conda-forge/miniforge)!

1. Ceate a new virtual environment:  
    `mamba create -n "eomaps_geopython24" -c conda-forge eomaps jupyterlab netcdf4 ipywidgets`
2. Activate the environment:  
    `mamba activate "eomaps_geopython24"`
</details>


--- 

Once the installation is done, navigate to the folder containing the cloned repository and run 
```
jupyter lab
```
