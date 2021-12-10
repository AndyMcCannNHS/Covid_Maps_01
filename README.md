# Covid_Maps_01

Map the public data case rate data at coronavirus.gov.uk including a Lancashire and South Cumbria inset map.

environment setup originally from https://github.com/MichaelAllen1966/2010_geopandas

## Run on BinderHub

(Note: This may take a while to start if it has not been used for a while)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AndyMcCannNHS/Covid_Maps_01/main)


## Set up the anaconda environment locally

Alternatively, to get the same libraries and versions I am using then you may recreate the environment. To create and activate the `geopandas` environment used:

To create environment. Navigate to the `binder` folder.

`conda env create -f environment.yml`

To activate environment:

`conda activate geopandas`

To deactivate:

`conda deactivate`

To update environment (from updated yml file):

`conda env update --prefix ./env --file environment.yml  --prune`

To remove the environemnt:

`conda env remove -n geopandas`
