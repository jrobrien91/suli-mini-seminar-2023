<img src="images/ANL_RGB-01.png" alt="thumbnail" width="300"/>

# Student Undergraduate Laboratory Internships (SULI) > Mini Semester - CROCUS Investigations

[![nightly-build](https://github.com/jrobrien91/suli-mini-semester/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/jrobrien91/suli-mini-semester/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/jrobrien91/suli-mini-seminar-2023/main)

## Motivation

During the [Student Undergraduate Laboratory Internship (SULI)](https://science.osti.gov/wdts/suli) Mini-Semester, potential interns are introduced to research conducted at Argonne National Laboratory. These notebooks cover an introduction to the Python programming language and serves as an example of a potential research topics, which involve CROCUS observations and scenarios.

The [Community Research on Climate and Urban Science (CROCUS)](https://www.anl.gov/crocus) project aims to investigate the localized climate zones of Chicago. 
A recent field campaign, CROCUS Urban Canyons, investigated airflow through densely packed city streets. As a part of this field campaign, atmospheric observations were collected over various land surface types. An investigation into these observations for various surface types can provide insight into how the city is affecting the atmospheric and driving localized circulations. 

## Authors

[Joe O'Brien](https://github.com/jrobrien91)

### Contributors

<a href="https://github.com/jrobrien91/suli-mini-semester/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jrobrien91/suli-mini-semester" />
</a>

## Structure

### Introduction to Python
Students are introduced to my career path and given an quick python introduction. 
Follow-up Python tutorials can be found at [Project Pythia - Foundations](https://foundations.projectpythia.org/landing-page.html) 

### CROCUS Air Quality Investigation
Students are introduced to the CROCUS project and the Chicago Micro-Net.
The python introduction is expanded to include reading CROCUS data and investigate air quality within Chicago during a Canadian Wildfire event from 2023.
Follow-up CROCUS examples can be found in the [CROCUS Instrument Cookbooks](https://github.com/CROCUS-Urban/instrument-cookbooks)

### CROCUS Land Surface Interactions Investigation
Students are introduced to the CROCUS Urban Canyons field experiment. 
Utilziing the previous notebooks, students are tasked with comparing two 10 meter tower instrumented sites at the University of Illinois Chicago to investiate the role of local surface conditions on atmospheric conditions. 

## Running the Notebooks
You can either run the notebook using [Binder](https://binderhub.readthedocs.io/en/latest/#) or on your local machine.

### Running the Jupyter

After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine
If you are interested in running this material locally on your computer, you 
will need to follow this workflow:   

1. Clone the `https://github.com/jrobrien91/suli-mini-semester` repository:

   ```bash
    git clone https://github.com/jrobrien91/suli-mini-semester.git
    ```  
1. Move into the `notebooks` directory
    ```bash
    cd notebooks
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate suli-seminar
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
