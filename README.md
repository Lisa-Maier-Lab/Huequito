# Huequito

Jacobo de la Cuesta-Zuluaga. July 2025.

`Huequito` is the workflow for the base calling and genome assembly
of Oxford Nanopore reads of the Maier Lab. For base calling it uses 
the `dorado` case caller available [here](https://dorado-docs.readthedocs.io/en/latest/).
For genome assembly, it implements the `nf-core` pipeline `bacass` available
[here](https://nf-co.re/bacass/2.4.0).

The notebooks walk you through the download of the software, the
creation of files and the execution of the pipelines.

## Requirements for Running the Notebooks
### Jupyter Notebook
To successfully execute the notebooks in this repository, you 
will need to have Jupyter Notebook installed on your system. 
You can run Jupyter Notebooks in two ways:

* Using VSCode (Recommended): you can also run Jupyter Notebooks
    within Visual Studio Code, which provides a user-friendly 
    interface for working with notebooks. If you use this, make
    sure to install the `Remote - SSH` and `Jupyter` extensions

* Standalone Installation: You can install Jupyter Notebook 
    independently on your machine. This allows you to open 
    and run notebooks directly from your local environment.

### Conda
In addition to Jupyter Notebook, you will need to have the 
ability to create and manage Conda environments. Conda is a 
package and environment management system that allows you to 
install dependencies and manage different project environments
easily.

### IRkernel

To execute R notebooks, you must also have the IRkernel available
in the Conda environment you create to run the notebooks. 

## Why `Huequito`?
Huequito means small hole in Spanish. I know, it is not my best joke.
