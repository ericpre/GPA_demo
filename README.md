[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ericpre/GPA_demo/HEAD)

Repository to demonstrate the simulation of STEM images.

### Setup conda environment

If you don't already have a Miniconda-like distribution, we recommand to install [MambaForge](https://github.com/conda-forge/miniforge/#mambaforge)

Clone or download this repository, go the folder containing the file of this repository and run the following command line in the Anaconda command prompt (Windows) or a terminal (Linux and MacOS)

```
conda env create -n GPA_demo --file environment.yml
```

If mamba is installed, `conda` can be replace by `mamba` for faster installation.

Activate the environment created in the previous step and run `jupyter notebook`

```
conda activate GPA_demo
jupyter notebook
```

### Acknowledgement

This work has been carried out within the framework of the EUROfusion Consortium and has received funding from the Euratom research and training program 2014-2018 and 2019-2020 under grant agreement No 633053. The views and opinions expressed herein do not necessarily reflect those of the European Commission.
