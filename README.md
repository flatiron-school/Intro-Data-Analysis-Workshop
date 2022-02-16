# Visualizing and Deploying Data Analysis Workshop

A code-along Jupyter notebook and accompanying app file for the Visualizing and Deploying Data Analysis Workshop - first run on June 30, 2021.

A version of the final Streamlit app is available online: https://austin-animal-center-data.herokuapp.com/

## Data Source:

[Austin Animal Center Intakes Data](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Intakes/wter-evkm/)

*Please note* - I used the Python library [geopy](https://geopy.readthedocs.io/en/stable/) to gather some specific location data (zipcodes, latitudes and longitudes) to augment the original data - full credit to the OpenStreetMap contributors, [who make the data available under the Open Database License!](https://www.openstreetmap.org/copyright)

## Workshop Files in this Repository:

`codealong_blank` is the blank version of the notebook, without pre-written code, which will be live-coded during the workshop session.

`codealong_complete` is a complete version of the notebook, although it may differ slightly from what is live-coded.

`app.py` is a version of the visualization code, adapted to be run as a Streamlit app.

## Accessing the Code:

The easiest way to follow along with the code is by clicking here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flatiron-school/Visualizing-Deploying-Data-Analysis-Workshop/HEAD)

*Please note* - it can take a few minutes for Binder to create the correct environment for the notebook. There's a non-interactive view if you scroll down while the environment loads.

If you do want to run the code on your own, download Jupyter Notebook and run these lines in your terminal:

1. `git clone https://github.com/flatiron-school/Visualizing-Deploying-Data-Analysis-Workshop.git`
2. `cd Visualizing-Deploying-Data-Analysis-Workshop`
3. `jupyter notebook`

## Thanks for attending!

[Feel free to connect with me!](https://www.linkedin.com/in/lindseyberlin/)
