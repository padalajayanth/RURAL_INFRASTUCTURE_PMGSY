# RURAL_INFRASTUCTURE_PMGSY
I built a machince learning model for PMGSY Scheme Classification (RURAL INFRASTUCTURE) . 
# 🛣️ PMGSY Scheme Classification using IBM AutoAI

This project solves Problem Statement 35 (SB4Academia 2025), which aims to classify rural infrastructure projects (like roads/bridges) into correct PMGSY schemes (PMGSY-I, PMGSY-II, RCPLWEA) using machine learning.

##  Objective
Automate the classification of PMGSY projects based on physical and financial attributes to support government planning and monitoring.

##  Dataset
- Source: [AI-Kosh PMGSY Dataset](https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html)
- Features: Project length, cost, duration, location, contractor type

## Tools Used
- IBM Watson Studio (AutoAI)
- IBM Cloud Object Storage
- Watson Machine Learning
- Python (for data prep)

##  Steps
1. Uploaded dataset to IBM AutoAI
2. Configured target as `PMGSY_SCHEME`
3. Trained multiple models, selected the best one
4. Deployed model via Watson ML as a REST API

I also attached the orediction result in json format. i provided the ppt for this project and also uploaded the project pdf and their implemantion.

