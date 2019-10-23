# Try GRASS GIS in Jupyter Notebook with Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wenzeslaus/try-grass-in-jupyter/master?filepath=notebook.ipynb)

Jupyter Notebook for trying GRASS GIS in *Binder*.

## Running locally

The repository is meant to run through Binder,
but you can run it locally which is relatively easy to do
especially on Linux because that's where it on runs on Binder.
To run the notebook locally, you need to install the required software
and download the data. The following files in the repository specify
(for Binder) what needs to be prepared for the notebook to run:

* apt.txt (system packages)
* runtime.txt (Python version)
* requirements.txt (Python packages)
* postBuild (data downloads)

## Branches (suggestion)

Branches in this repository mirror branches in the OSGeo/grass
repository. The latest (and potentially any former) GRASS GIS release
branch has its specific code here in the corresponding branch.
The master branch in this repository can reflect the latest improvements
in GRASS GIS.
