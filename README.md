# Capstone
 
**Author**: *Manav Kahlon*
  
## Overview
- [Business Problem](#Business-Problem)
- [Data](#Data)
   - [*TDB*](./data)
- [Methods](#Methods)
- [EDA Results: Notable Features](#EDA-Results-Notable-Features) 
- [Modeling Results](#Modeling-Results)
- [Conclusions](#Conclusions)
- [For More Information](#For-More-Information)
- [Repository Structure](#Repositroy-Structure)
  

## Business Problem  
 
## Data


 #### Driven Data
    * training_set_features.csv
    * training_set_labels.csv
    
   
## Methods

    
## EDA Results Notable Features


### H1N1 Vaccine

#####
![image](./images/H1N1_and_race.png)
When comparing the vaccination status for H1N1 and the level of concern we find there is a difference between the level of concern of those who did receive the vaccine and those who did not. Looking at those individuals who had did not receive the H1N1 vaccine we see that $13.59%$ had no concern, $32.23%$ had very little concern, $38.66%$ were somewhat concerned and only $15.51%$ were very concerned. Comparing that to those people who did receive the vaccine we see that their rate of concern was $7.90%$, $24.69%$, $43.71%$, and $23.70%$ respectively for each group. For people who received the vaccine, their rate of not being concerned at all was $5.69%$ lower than those who did not receive the vaccine. This makes sense intuitively since people who are not concerned about an illness are less likely to take precautions to prevent or lower their chances of getting severely sick because of that illness. For people who received the vaccine, their rate of not very concerned was $7.54%$ lower than those who did not receive the vaccine. Again, people who are not concerned about an illness are less likely to take a vaccine that will help to prevent serious illness or death against that very illness. Those two groups provide no surprise to the difference between those individuals who were vaccinated and those who were not. Now, if we look at the two groups of people who were at least somewhat concerned we should expect the difference in group sizes to be larger than those who were not vaccinated. Looking first at people who were somewhat concerned we see that this group is $5.05%$ larger than the same group in non-vaccinated people. Finally looking at the difference for people who are very concerned we see that the difference is $8.19%$, the largest of all the groups between vaccinated and non vaccinated people.

![image](./images/H1N1_concern_vaccination.png)



### Seasonal Flu Vaccine

 
## Modeling Results

    
## Conclusions


    
    
## For More Information
Please review our full analysis in different notebooks [Aurora, CO](./notebooks/Aurora_CO_80016.ipynb), [Erie, CO](./notebooks/Erie_CO_80516.ipynb), [Jacksonville, NC](./notebooks/Jacksonville_NC_28546.ipynb), [Functions to model](./notebooks/Phase_4_functions.py), [Saratoga Springs, UT](./notebooks/Saratoga_Springs_UT_84045.ipynb), and our [Data Prep Notebook](./notebooks/zip_code_selection_and_one_model.ipynb), or our [Presentation](./Presentation.pdf).    
    
## Repositroy Structure
```  
├── data                                       <- Sourced from an external source
├── images                                     <- Images that were used in the presentation and notebooks
├── Flu_analysis_models                        <- The Notebooks for Seasonal Flu Analysis and Models
    ├── Seasonl_Flu_Analysis.ipynb             <- Analysis of Seasonal Flu Vaccine
    ├── *TBD*                                  <- First set of models
    ├── *TBD*                                  <- Random Forest and Gradiant Boost Models
    ├── *TBD*                                  <- XGBoost Model
    └── *TBD*                                  <- *WILL BE A KERAS MODEL* 
├── H1N1_analysis_models                       <- The notebooks that for H1N1 Analysis and Models
    ├── 00_H1N1_Analysis.ipynb                 <- Analysis of H1N1 Vaccine
    ├── 01_Data_Cleaning_H1N1.ipynb            <- Data Cleaning and Prep for H1N1
    ├── 02_Logistic_KNN_SVC_H1N1.ipynb         <- The first set of models
    ├── 03_Random_Forest_Gradiant_Boost.ipynb  <- Random Forest Model
    ├── 04_XGBoost.ipynb                       <- XGBoost Model
    └── 05_TBD                                 <- *WILL BE A KERAS MODEL*
├── gitignore                                  <- python files to ignore 
├── Presentation.pdf                           <- PDF of our project presentation  
└── README.md                                  <- The README.md
```
