# Methylation data simulation

This directory contains the code to simulate methylation data based on the realworld dataset. 
It is written in Python and leverages popular scientific computing libraries such as NumPy, Pandas, and SciPy.
It is advised to use a virtual environment to run the code in order to avoid conflicts with the dependencies of other projects.
You can use the **Conda** environment manager — follow [these instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) to install it for your operating system.

## Create a virtual environment
In the terminal, run the following command to create a new virtual environment:
```bash
conda create --name realart-tutorial python=3.11
```
Next, activate the environment:
```bash
conda activate realart-tutorial
```
Install the required packages:
```bash
pip install -r requirements.txt
```

## Explore the code
All the scripts needed to simulate methylation data are located in the `methylation_simulation.py`. 
Exemplary realworld data is stored as a tsv file–`realworld_data.tsv`.
In the jupyter notebook `methylation_simulation_tutorial.ipynb`, you can find a step-by-step guide on how to read your dataset, simulate artificial data, and transform it to M scale.
