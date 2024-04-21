# Socioeconomic aspects versus accessibility to subway stations of the city of são paulo

## Problem description

Measuring socioeconomic aspects versus accessibility to subway stations in big cities is important because it can provide insight into how transportation infrastructure and services are impacting different communities. Socioeconomic factors, such as income, education, and occupation, can influence a person's access to transportation and opportunities. By comparing the socioeconomic characteristics of neighborhoods with varying levels of subway station accessibility, it can be determined if certain groups are being disproportionately affected by a lack of transportation options. This information can then be used to inform policy and investment decisions to promote greater equity in transportation access.

## Skills

`python` `pandas` `geopandas` `geojson` `git` `github` `google colab`

## Running the Project

This project is designed to run in Google Colab, a cloud-based Python development environment that provides free access to computing resources. Follow these steps to set up and execute the project:

### Prerequisites
Ensure you have access to Google Colab. If not, visit [Google Colab](https://colab.research.google.com/) and log in with your Google account.

### Installation Steps
To install the necessary Python packages for this project, execute the following cell in your Google Colab notebook. This will install several libraries essential for handling geographical data and making HTTP requests.

```python
# Install the required packages
!pip install fiona geojson osgeo geopandas geojsonio geoplot requests
```

### Note
- Each `pip install` command fetches and installs packages from the Python Package Index (PyPI), ensuring you have the latest versions compatible with your project.
- Running the installation commands may take a few minutes depending on your internet connection and server availability.

Proceed with running the rest of your notebook cells once the installations are complete.

## Conclusion

* In this notebook, we analysed data from the following data sources: IBGE and Geosampa. We used geolocation data and used the python library geopandas in order to analyse them.

* The main conclusion of the analysis is:
> The accessibility of metro stations is directly related with income. Other analysis could be done with train, bus, bicycle, etc which is available at Geosampa. Instead of income, it could be used age, sex, race and multiple other socioeconomical varibles avaliable at IBGE.

* Multiple data and variables were found in those data bases. Just a few of them were used in this work as a sample of what is possible to do with this data and tools.