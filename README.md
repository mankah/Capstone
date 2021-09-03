# Capstone
 
**Authors**: *Manav Kahlon*
  
## Overview
- [Business Problem](#Business-Problem)
- [Data](#Data)
   - [Zillow and Realtor](./data)
- [Methods](#Methods)
- [EDA Results: Notable Features](#EDA-Results-Notable-Features) 
- [Modeling Results](#Modeling-Results)
- [Conclusions](#Conclusions)
- [For More Information](#For-More-Information)
- [Repository Structure](#Repositroy-Structure)
  

## Business Problem
A real estate investment company has asked us to select the top five US zip codes to invest in.  
 
## Data
We examined more than 30,000 records from Zillow that included house prices across different zip codes from 1997-2021. We found additional data from Realtor.com that was used in the selection of the top 5 zip codes. The Zillow dataset contained 316 columns most of which were different dates from 1996 to 2021 with house prices in that zip code. We compressed the dataset into only 10 columns with the time becoming the index column and the values melting into a single column based on their zip code. To create the dataset used for zip code selection, the Zillow and Realtor.com datasets were merged on zip code and record dates. In order to select the zip codes that would yeild the largest ROI, we considered both market and housing characteristics. 


 #### Driven Data
    * training_set_features.csv
    * training_set_labels.csv
    
   
## Methods

### Zip Code Selection

    
## EDA Results Notable Features


### House Value and Price Increase Count


### Pending Ratio and Days on Market


 
## Modeling Results

    
## Conclusions


    
    
## For More Information
Please review our full analysis in different notebooks [Aurora, CO](./notebooks/Aurora_CO_80016.ipynb), [Erie, CO](./notebooks/Erie_CO_80516.ipynb), [Jacksonville, NC](./notebooks/Jacksonville_NC_28546.ipynb), [Functions to model](./notebooks/Phase_4_functions.py), [Saratoga Springs, UT](./notebooks/Saratoga_Springs_UT_84045.ipynb), and our [Data Prep Notebook](./notebooks/zip_code_selection_and_one_model.ipynb), or our [Presentation](./Presentation.pdf).    
    
## Repositroy Structure
```
├── data                                  <- Sourced from an external source
├── images                                <- Images that were used in the presentation and notebooks
├── Notebooks                             <- The notebooks that we made
    └── Aurora_CO_80016.ipynb                  <- Data Prep Notebook
    └── Erie_CO_80516.ipynb                    <- Erie, CO, 80516 Notebook
    └── Jacksonville_NC_28546.ipynb            <- Jacksonville, NC, 28546 Notebook
    └── Phase_4_functions.py                   <- Phase 4 functions Notebook
    └── Ridgefield_WA_98642.ipynb              <- Ridgefield, WA, 98642 Notebook
    └── Saratoga_Springs_UT_84045.ipynb        <- Saratoga Springs, UT, 84045
    └── zip_code_selection_and_one_model.ipynb <- Data Prep Notebook
├── gitignore                             <- python files to ignore 
├── Presentation.pdf                      <- PDF of our project presentation  
└── README.md                             <- The README.md
```
