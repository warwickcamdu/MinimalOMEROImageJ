# MinimalOMEROImageJ

Based on the OMERO guide: https://omero-guides.readthedocs.io/projects/fiji/en/latest/imagej_python.html

## Setup:

Create a new conda environment and activate it
```
$ conda create -n imagej_python python=3.6
$ conda activate imagej_python
```
Install the required packages
```
$ conda install -c conda-forge pyimagej
$ conda install -c ome omero-py
$ conda install -c conda-forge notebook
```
Start jupyter notebook
```
$ jupyter notebook
```
In the first function you will need to change the path to your local Fiji application.
