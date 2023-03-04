<div align="center">
    <h6>Environmental Data Science Book</h6>
</div>

<p align="center">
<img src="https://github.com/alan-turing-institute/environmental-ds-book/blob/master/book/figures/logo/logo.png?raw=True" alt="thumbnail" width="200"/>
</p>

<div align="center">
    <h1>Concatenating a gridded rainfall reanalysis dataset into a time series</h1>
</div>

<p align="center">
    <a href="https://github.com/Environmental-DS-Book/general-preprocessing-rainfall_noaa/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
    <a href="https://notebooks.gesis.org/binder/v2/gh/Environmental-DS-Book/general-preprocessing-rainfall_noaa/main?labpath=general-preprocessing-rainfall_noaa.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://github.com/Environmental-DS-Book/general-preprocessing-rainfall_noaa/actions/workflows/publish.yml/badge.svg">
        <img alt="Continuous integration badge" src="https://github.com/Environmental-DS-Book/general-preprocessing-rainfall_noaa/actions/workflows/publish.yml/badge.svg">
    </a>
    <br/>
</p>

<p align="center">
    <a href="https://w3id.org/ro-id/ea34568e-d86e-4720-be2f-3f826f66a26c">
        <img alt="RoHub" src="https://img.shields.io/badge/RoHub-FAIR_Executable_Research_Object-2ea44f?logo=Open+Access&logoColor=blue">
    </a>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/13321552/222931377-25ffc6e7-e141-48d4-85ff-f14090edf446.png?raw=True" alt="thumbnail" width="500"/>
</p>

# How to run

## Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

## Running locally
You may also download the notebook from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone https://github.com/Environmental-DS-Book/general-preprocessing-rainfall_noaa.git
    ```

4. Move into the cloned repository
    ```bash
    cd general-preprocessing-rainfall_noaa
    ```

5. Create and activate your environment from the `.binder/environment.yml` file
    ```bash
    conda env create -f .binder/environment.yml
    conda activate general-preprocessing-rainfall_noaa
    ```  

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`

# Credits
The **How to run** section was adapted from the [Project Pythia Cookbook](https://cookbooks.projectpythia.org/) project.
