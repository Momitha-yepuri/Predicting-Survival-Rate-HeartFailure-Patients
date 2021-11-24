# Predicting Survival Rate of Patients in Heart Failure Data¶


## Introduction
This [dataset](http://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records) contains information about medical records of 299 heart failure patients, and we are trying to predict the survival rate of patients through ejection_fraction with the help of factors like serum_sodium, creatinine_phosphokinase, serum_creatinine, etc. using multiple linear regression. This dataset was sourced from Krembil Research Institute, Toronto, Canada and donated to the University of California Irvine Machine Learning Repository under the same Attribution 4.0 International (CC BY 4.0) copyright in January 2020.



## Project Objective: 
Our aim is to predict the survival rate of the heart patient through ejection_fraction using multiple linear regression. Since decrease in ejection fraction indicates that the heart can not pump blood normally, it means the heart is not healthy enough. Ejection fraction is the main factor which determines whether the heart will function normally. Hence, we link the survival rate of the heart failure patients with ejection fraction.

## Target Attribute:
Our target attribute is ejection_fraction, which is a continuous numerical feature. Hence, our project is on a regression problem. Ejection fraction (EF) is a measurement, expressed as a percentage, of how much blood the left ventricle pumps out with each contraction. An ejection fraction of 60% means that 60% of the total amount of blood in the left ventricle is pushed out with each heartbeat.

## Descriptive Features:
The following are the variables in the dataset heart_failure_clinical_records_dataset:
| Name | Data Type | Units| Description|
|-------|-------|------|--------|
|age | numerical (continuous) | years | Age of the patient in years |
|anaemia | binary | NA | If a patient has anaemia (decrease of red blood cells or hemoglobin) |
|creatinine_phosphokinase | numerical (discrete) | mcg/L | level of the CPK enzyme (creatinine phosphokinase) in the blood |
|diabetes | binary | NA |  If the patient has diabetes |
|**ejection_fraction** (target)| numerical (discrete) | percentage | The percentage of blood leaving the heart at each contraction |
|high_blood_pressure | binary | NA |  If the patient has hypertension |
|platelets | numerical (continuous) | kiloplatelets/mL | The amount of platelets in the blood |
|serum_creatinine | numerical (continuous) | mg/dL | The level of serum creatinine in the blood |
|serum_sodium | numerical (discrete) | mEq/L | The level of serum sodium in the blood |
|sex | binary | NA | If the patient is a Female or Male |
|smoking | binary| NA | If the patient smokes or not |
|time | numerical (discrete) | days | Follow-up period in days |
|DEATH_EVENT | binary | NA | If the patient died during the follow-up period |
