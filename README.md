# CLEWs GIS processing script
This repo contains code bundles related to the GIS (and other) work done for the UN CLEWs team

## Steps to run the CLEWs GIS processing script:

### 1. Create a new environment and activate it
```
conda env create -f clews_gis_work.yml
conda activate clews_gis_work
```

### 2. Setting up connection between new environment and Jupyter Notebook
```
conda config --env --add channels conda-forge
conda config --env --set channel_priority strict
conda install python=3 geopandas
conda install python=3 jupyter
python -m ipykernel install --user --name clews_gis_work
conda install nb_conda
```

### 3. Open the CLEWs GIS processing Jupyter Notebook
```
jupyter notebook CLEWs GIS Processing.ipynb
```

### 4. Select the environment within Jupyter Notebook 
Click on `Kernel` -> `Change Kernel` -> `clews_gis_work`

