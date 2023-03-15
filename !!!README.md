# 163B Group-4: Repository
https://github.com/MechaKaradi/163B-Repository-Group-4.git

Authors: 
Lala Sayyida Millati Nadhira		5844266 
Kaninik Baradi 			5216664 
Rezzy Yolanda Wulandhari		4779487 
Kelvin Engee				4664043
Philippe Almeida Mirault		5898803

# Introduction
The relationship between green spaces and crime rates is debated, with some studies suggesting that greenery can have a calming effect and attract foot traffic to deter criminal activity (Kuo & Sullivan, 2001). However, the relationship is not always clear-cut and may be influenced by various factors. In certain contexts, green spaces may even increase crime rates by providing cover for criminal activity or attracting individuals more likely to engage in crime. 
Understanding the factors that may have contributed to the crime would be helpful in predicting the likelihood of future crimes occurring. 

This repository handles the import, cleaning, and visualisaton of data from the NYC Open Data repository to develop the descriptive and predictive analytics for the model.

# Requirements
The `environment.yml` file provides the list of conda dependencies required to run the notebooks. 
Relative to the root folder of the repository, the following files are needed: 
- `..\\NYPD_Complaint_Data_Historic.csv` : [source](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i)
- `..\\data\\2015 Street Tree Census - Tree Data.geojson` : [source](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/pi5s-9p35)
- `..\\data\\Police Precincts.geojson` : [source](https://data.cityofnewyork.us/Public-Safety/Police-Precincts/78dh-3ptz)

# Notebooks Structure
To run the analysis, the `Data Clean Final.ipynb` notebook must be run first to generate a `data.pickle` file with cleaned data. This file serves as input to the other notebooks.

The `count_trees.ipynb` notebook file generates reduced analytics for the number of trees in each precinct. 

The remaining notebooks generate visualisations and analytics. 