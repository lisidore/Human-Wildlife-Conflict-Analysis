Comprehensive Human-Wildlife Conflict Analysis in India's National Parks

**Introduction**
This repository contains a hypothetical research project designed to demonstrate the entire data science workflow: from data collection and cleaning to exploratory analysis, visualisation, and machine learning modeling. The focus is on understanding and predicting human-wildlife conflicts in specific national parks in India.

**Hypothetical Data Collection Methods**
The data for this project was hypothetically collected through interviews with affected families and local authorities. Incident coordinates were recorded using GPS devices during site visits guided by the interviewees.

**Data Cleaning**
The repository includes an initial "unclean" dataset to demonstrate data cleaning techniques. The data cleaning script handles missing values, duplicates, and outliers to produce a clean dataset for analysis.

**Research Questions**
How can machine learning models be used to identify high-risk zones for human-wildlife conflicts within specific national parks in India?
What socio-economic and environmental variables serve as the strongest predictors for the severity of these conflicts?
How effectively can temporal patterns in human-wildlife conflicts be forecasted to implement preventative measures?

**Hypothetical Scenario**
This study focuses on incidents that could occur within the boundaries of three national parks in India: Bandipur, Kaziranga, and Sundarbans. The project aims to understand factors contributing to these conflicts and to predict future incidents in these specific locations.

**Methods**
The dataset includes 1000 records of past incidents, hypothetically sourced from local wildlife agencies and community reports.

**Exploratory Data Analysis (EDA)**: Initial visualisations are created to understand the data better, with a focus on spatial patterns.

**Machine Learning Models**: Logistic regression and random forest models are used to predict the likelihood and severity of conflicts.

**Data Description**
incident_id: Unique identifier for each incident.
date: The date the incident occurred.
species: The animal species involved in the conflict.
habitat_type: The type of habitat where the incident occurred.
distance_to_settlement: Distance from the incident to the nearest human settlement (in km).
conflict_type: The type of conflict (e.g., property damage, physical harm).
minor_injuries: Number of minor injuries to humans.
major_injuries: Number of major injuries to humans.
number_of_deaths: Number of human deaths.
economic_loss: Economic loss in USD.

Scripts and How to Run Them
Data Cleaning: data_cleaning.py - Cleans the raw data.
Data Visualisation: data_visualisation.py - Produces visualizations.
Machine Learning Models: ml_models.py - Contains machine learning code.
Results and Discussion
The initial analysis suggests that distance to the nearest settlement and species type are significant factors in predicting the likelihood and severity of conflicts.

License
This project is open source and available under the MIT License.

Contact
For more information, feel free to contact me at lennisidore@gmail.com.

