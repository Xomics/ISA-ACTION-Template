# ISA-ACTION-Template
This repository contains a [Jupyter Notebook](https://github.com/Xomics/ISA-ACTION-Template/blob/main/ISA_ACTION-Template.ipynb), which serves as a possible template for the creation of ISA-Tab files for multi-omics (meta)data.
The ISA-Tab files that are produced with this Notebook can be found in the `isa_templates` folder.

## Docker environment (**Important**)

In order to run this notebook, a specific set of dependencies needs to be installed. For this purpose, we create a [Dockerized environment](https://github.com/Xomics/Isatools_environment), containing all packages (isa-api and more) that are necessary to run this Jupyter notebook.

## Run the Notebook without Docker

All dependencies can be installed using the `isa_env.yml` environment file in this repository. Install conda environment
```
conda env create isa_env -f isa_env.yml
```

## Fake IDs
The Subject IDs that can be found in the files here are not real, with respect to privacy



