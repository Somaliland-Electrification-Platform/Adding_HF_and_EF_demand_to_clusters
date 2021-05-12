# Assigning HF & EF demand to clusters
An GIS-based approach of estimating electricity requirements for health abd education facilities and assigning them to the nearest population cluster. Notebook and sample data customized for Somaliland.

## Content

- **Assigning_HF_EF_demand_to_clusters.ipynb** contains the core code
- **sample_input** directory contains sample input data for testing including:
	- Somaliland_adm0.gpkg
	- Somaliland_WBPeanutButter_clusters_clipped.gpkg
	- HF_WHO_SARA_GoSL_geotagged.gpkg
	- EF_UNICEF_GoSL_geotagged.gpkg
- **sample_output** directory contains sample output data including:
	- Somaliland_WBPeanutButter_clusters_clipped_HF_EF_kWh.gpkg
- **maps** directory contains sample output maps
- **requirements.txt** dependencies info for setting up package requirements

## Setting up the environment & running the model

**Install from GitHub**

Download repository directly or clone it to you designated local directory using:

```
git clone https://github.com/Somaliland-Electrification-Platform/Adding_HF_and_EF_demand_to_clusters.git
```

**Requirements**

The notebook has been developed in Python 3. We recommend installing [Anaconda's free distribution](https://www.anaconda.com/distribution/) as suited for your operating system. 

Once installed, open anaconda prompt and move to your local "Adding_HF_and_EF_demand_to_clusters" directory using:

```
> cd ..\Adding_HF_and_EF_demand_to_clusters
```

In order to be able to run the notebook you should install all necessary packages. "requirements.txt" contains all of these and can be easily set up by creating a new virtual environment using:

```
pip install requirements.txt
```

Once completed, you can now move to the directory and start a "jupyter notebook" session by simply typing:

```
..\Adding_HF_and_EF_demand_to_clusters> jupyter notebook 
```


## Credits

**Conceptualization & Methodological review :** [Alexandros Korkovelos](https://github.com/akorkovelos)<br>
**Code development** [Alexandros Korkovelos](https://github.com/akorkovelos)<br> 
**Review, Updates, Modifications:** [Alexandros Korkovelos](https://github.com/akorkovelos)<br>
**Supervision, Review and Advisory support:** [Benjamin P. Stewart](https://github.com/bpstewar), [Ashish Shrestha](mailto:ashrestha1@worldbank.org), [Rhonda Lenai Jordan](mailto:rjordan@worldbank.org)<br>
**Funding:** The World Bank

