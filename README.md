<h1 style="display: inline"> 
<img alt=EOmaps src=https://raw.githubusercontent.com/raphaelquast/EOmaps/dev/docs/_static/logo.png align="left" width=100px style="margin:0 2em 0 0;">
<b>GeoPython 2024</b>  Workshop 
</h1>
<br>

## Setup

> First navigate to your desired working directory and clone this repository with   
> `git clone https://github.com/raphaelquast/EOmaps_GeoPython2024.git`


You can then setup all you need with `venv/pip` or `conda/mamba`:

<details><summary><font size=4>venv / pip</font></summary>

> No working `python` on your system?  
> Install [python](https://www.python.org/downloads/)!

1. Create a new virtual environment:  
    `python -m venv "venv_folder_path"`
2. Activate the environment:  
    `venv_folder_path\Scripts\activate`
3. Install required packages:  
   `pip install eomaps[all] jupyterlab`
4. Navigate to your working directory and start Jupyter Lab:  
   `jupster lab`
</details>

<details><summary><font size=4>conda / mamba</font></summary>

> No working `python + conda/mamba` on your system?  
> Install [miniforge](https://github.com/conda-forge/miniforge)!

1. Ceate a new virtual environment:  
    `mamba create -n "name_of_environment"`
2. Activate the environment:  
    `mamba activate "name_of_environment"`
3. Install required packages:  
   `mamba install -c conda-forge eomaps jupyterlab`
4. Navigate to your working directory and start Jupyter Lab:  
`jupster lab`

</details>
