# Coursera_Capstone
## Models to Predict Severity of a Traffic Accident (STA) based on Weather, Road and Light Conditions
Applied Data Science Final Project
K. Giraldo, 2020

## Introduction - Business Problem
Traffic accidents are, in modern times, a great cause of health issues for many developed and under-developed countries with the latest one having the highest rates in the world and usually producing high numbers of deaths[1,2] and/or Property Damage.
Many papers have been published during the last years predicting traffic accidents severity, however, most of them come from datasets from developed countries. Available information from countries in development is limited, incomplete or segmented [3] where weather or road conditions are not taken fully into account[4] with other factors being considered as more important[4].
This work pretends to create Supervised Machine Learning Classification Models from Vehicle Collision Dataset from the City of Seattle as an example and initial starting point to show the importance of Weather and Road Conditions to estimate the STA in other regions.
The dataset to be used contains a Labeled attribute, Severity, describing the severity of an accident such as Injuries and Property Damage for the City of Seattle between the years of 2005 to 2020, however, itt doesn't contain any other information about severity such as deaths or level of Injury or damage. It includes attributes such as number of people involved, type of vehicles, type of road,  date and time of incident, Weather, Road and Light conditions. The total number of records are approximately 200,000 that need to be cleaned and prepared for the models.


K-Nearest Neighbors, Logistic Regression and Support Vector Machines will be used as classification algorithms to create the models. An effort to balance the dataset will be done.

Evaluation methods such as Jaccard Index and F1-Score will be used to assess the models.



## References
----------------------------------
[1] Accident Severity Prediction Using data Mining Methods. S Ramya et al; International Journal of Scientific Research in Computer Science, Vol 5, Issue 2, 2019

[2] High-Resolution Road Vehicle Collision Prediction for the City of Montreal, Antoine H'ebert et al, Preprint, 2019

[3] After personal research on the web.

[4] Ibero American Report for Traffic Safety, 2015,2016, In Spanish.
