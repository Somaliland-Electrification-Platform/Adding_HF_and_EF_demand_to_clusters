# gep_health_facilities
An exploratory geo-spatial approach of estimating electricity requirements for health facilities

## Rationale

Globally, it is estimated that ~789 million people live without access to electricity. This is a critical service gap that affects socio-economic development and human well-being, especially in poor, rural populations in least developed areas. At the same time, COVID-19 has brought into sharp focus the importance of electricity in the health sector. Access to electricity, in health clinics and posts, keeps people connected, allows for information management, the refrigeration of medicines and other services to protect vulnerable populations. Therefore, the lack of reliable power is undermining the quality of health care for millions of people. This creates an urgent need to "energize" health facilities so that there is a timely response to the COVID-19 crisis.

This notebook serves as an exploratory geo-spatial approach of estimating electricity requirements for health facilities, in areas where detailed data of this kind is scarce. It leverages existing open access datasets (and models) in order to provide a high level picture of annual electricity requirements in those facilities and later on indicate how these can be met as part of a least-cost electrification and/or prioritization plan. The sample input data focus on the district of Mecanhelas in Mozambique. However, the code can be scaled up at national or even regional level.


## Content

- **HF_demand_estimation.ipynb** contains the core code
- **Testing_Sample** directory contains sample input data for testing including:
	- mecanhelas_admin.gpkg
	- mec_health_index.gpkg
	- mecanhelas_clusters.gpkg
- **maps** directory contains sample output maps 
- **requirements.txt** dependencies info for setting up package requirements

## Setting up the environment & running the model

**Install from GitHub**

Download repository directly or clone it to you designated local directory using:

```
git clone https://github.com/akorkovelos/gep_health_facilities.git
```

**Requirements**

The notebook has been developed in Python 3. We recommend installing [Anaconda's free distribution](https://www.anaconda.com/distribution/) as suited for your operating system. 

Once installed, open anaconda prompt and move to your local "gep_health_facilities" directory using:

```
> cd ..\gep_health_facilities
```

In order to be able to run the notebook you should install all necessary packages. "requirements.txt" contains all of these and can be easily set up by creating a new virtual environment using:

```
pip install requirements.txt
```

Once completed, you can now move to the directory and start a "jupyter notebook" session by simply typing:

```
..\gep_health_facilities> jupyter notebook 
```


## Credits

**Conceptualization & Methodological review :** [Alexandros Korkovelos](https://github.com/akorkovelos)<br>
**Code development** [Alexandros Korkovelos](https://github.com/akorkovelos)<br> 
**Review, Updates, Modifications:** [Alexandros Korkovelos](https://github.com/akorkovelos)<br>
**Supervision, Review and Advisory support:** [Benjamin P. Stewart](https://github.com/bpstewar), [Ashish Shrestha](mailto:ashrestha1@worldbank.org), [Rhonda Lenai Jordan](mailto:rjordan@worldbank.org)<br>
**Funding:** The World Bank

