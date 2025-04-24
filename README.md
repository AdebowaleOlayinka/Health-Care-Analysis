# Health Care Analysis
![medical-banner-with-doctor-wearing-goggles_23-2149611193](https://github.com/user-attachments/assets/a8b2ce65-8ee4-406f-b793-1f17f67873cf)

 ## Table of Contents   
- [About Project](#about-project)
- [Dataset Overview](#dataset-overview)
- [Problem Statement](#problem-statement)

## About Project
The Health Care project contains a dataset of 55,500 record of patients from 10 major hospitals across the U.S. It captures a view of hospital admission, Medical conditions, medications, Insurance provider and treatment cost. The goal is to uncover insight that can drive better health care decisions, optimize cost and improve patient outcomes.

## Dataset Overview
- **Record**: 55,500 Patients
- **Column Field**: Age, Gender, Blood Type, Medical Conditions, Admission and Discharge Date, Hospital, Billing Amount, Test Results, Insurance Provider
- **Data Source**: Onyx Dataset

## Problem Statement 
1. What are the most common age group, gender and blood type among patient?
2. What medical conditions are diagnosed most frequenly?
3. How long do patient stay and what affect it?
4. How much does treament cost by condition and admission type?
5. How do hospital compare in terms of patient treated and outcomes?
6. What medications are commonly used?
7. How do admission type impact stay and cost?
8. Which insurance provider cover the most patient?

## Technique Applied 
- Data Cleaning and Transformation
- Dax calculations and kpi
- Visualization

## Data Cleaning and Transformation 


![Dax Calculation](https://github.com/user-attachments/assets/4f9d5746-09e0-42ac-ad22-c5d2939e93d2)



## Dashboard 
![Health Care Dashboard Page1](https://github.com/user-attachments/assets/68feec48-5be0-412b-b0c8-fd2b7ca908a9)

![Health Care Dashboard page 2](https://github.com/user-attachments/assets/7505a59d-f33b-4214-a14d-d9c48d4c7c67)

## Insight 
- **Patient Demographic**: Patient aged 66+ form the largest group of patients highlighting that Elderly are the most frequent users of the hospital services
- **Gender & Blood type distribution**: A+ blood type is most common among patients noticebly higher numbers of female patients(11,100) compared to male(6,660)
- **Hospital based on test outcomes**: Houston Methodist Hospital has the highest number of patients with highest test results
- **Most diagnosed condition**: The top 3 most diagnosed condition are Diabetes, Hypertension and Obesity affecting over 40,000 patients
- **Medication**: Ibuprofen is the most used medication by patients accounting for 20.05% usage
- **Insurance Provider**: Medicare insurance provider covers over 50% of patients
- **length of stay by treatment cost and admission type**: Elective admission lead to the highest treatment cost of $25,602 with the average stay of 15.5 days
- Emergency lead with the highest stay if 15.6 days and urgent admission with 15.4 days
