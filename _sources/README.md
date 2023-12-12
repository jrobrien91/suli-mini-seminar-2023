# suli-mini-seminar-2023
Intro to Python - CROCUS Air Quality Investigation SULI Mini-Seminar 2023

## Notebooks:  
1. An introduction to python  
2. The available open-source resources of the python community  
3. Investigation of the CROCUS Air Quality Dataset for a Canadian WildFire Smoke Event

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
If you are interested in running this material locally on your computer, you will need to follow this workflow:   

1. Clone the `https://github.com/jrobrien91/suli-mini-seminar-2023` repository:

   ```bash
    git clone https://github.com/jrobrien91/suli-mini-seminar-2023.git
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
