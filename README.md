# Predicting Medical Specialties - Data Analytics Bootcamp Final Project  

## Overview  

Machine learning in healthcare is one such area which is seeing gradual acceptance in the healthcare industry. Many companies are entering the field not because they want to, but because they have to, one of many examples available is the Google medical AI for disease detection (https://www.technologyreview.com/2020/04/27/1000658/google-medical-ai-accurate-lab-real-life-clinic-covid-diabetes-retina-disease/).  
The top three machine learning applications for healthcare currently are:  

* Diagnoses of diseases considered hard to diagnose,  
-Early drug discovery process and manufacturing, and  
-Medical imaging diagnosis. 

Nowadays, and specially in the current COVID-19 pandemic situation every country is facing, it is important to be able to aid healthcare workers redirect each patient to the specific medical specialty just by knowing their symptoms or medical transcriptions. This would greatly reduce the contact between patients and workers, the attendance time, and probably save many lives.  

For my final project, I used a dataset(available in Kaggle) that mainly contained medical transcriptions and the respective medical specialty for approximately 6000 patients. The main objective was to implement a supervised machine learning model for Natural Language Processing (NLP), that predicts the medical specialty to which each patient belongs based on the medical transcriptions. 
I tried to simulate as much as possible the workflow data analysts and data scientists follow inside a company. For this, I followed many steps, starting by performing an ETL(extract, transform, load) pipeline, selecting and saving the supervised machine learning model that better fitted my dataset, while also constructing a Tableau Dashboard for a better visualization of my results, and as an Extra, implementing a Flask app that clearly shows how the medical specialty predictions would be performed.

## URLs
Dataset: https://www.kaggle.com/tboyle10/medicaltranscriptions?select=mtsamples.csv
Tableau Dashboard: https://public.tableau.com/profile/joan.concha#!/vizhome/Predicting-medical-specialties/Final_product
Note: The prediction performed in this Dashboard is just an example. Since the Flask app runs only locally, it is not available.

