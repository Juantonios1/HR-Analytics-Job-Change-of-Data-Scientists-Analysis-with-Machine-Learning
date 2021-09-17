# PandasGroup_JC_DS_BSD_JKT_13_FinalProject
# HR Analysis

## Problem Statement
**Context**  
A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses which conduct by the company. Many people signup for their training. Company wants to know which of these candidates are really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates signup and enrollment.

0 : Not looking for job change  
1 : Looking for a job change  

**Problem Statement :**

Hiring process could be time and resource consuming if company targets all candidates only based on their training participation. Company wants to increase recruitment efficiency by knowing which candidates are looking for a job change in their career so they can be hired as data scientist.

**Goals :**

Company can categorized candidates who are looking and not looking for a job change so they can focus the recruitment for people who are willing to work for the company.

**Metric Evaluation**
Type 1 error : False Positive  
Consequences: loss of recruitment cost, time and resource

Type 2 error : False Negative  
Consequences: loss of potential candidate  

Based on that consequences we want to minimize type 1 error and also type 2 error but we are interested in positive class only. So we will use F1-score 

## Data Understanding
***
* enrollee_id : Unique ID for candidate 
* city: City code (unknown) 
* city_ development _index (CDI): Developement index of the city (scaled). Ranks cities according to their Infrastructure, Waste Management, Health, Education, and City Product
* gender: Gender of candidate 
* relevent_experience: Relevant experience of candidate 
* enrolled_university: Type of University course enrolled if any
* education_level: Education level of candidate 
* major_discipline :Education major discipline of candidate 
* experience: Candidate total experience in years
* company_size: No of employees in current employer's company 
* company_type : Type of current employer
* lastnewjob: Difference in years between previous job and current job 
* training_hours: training hours completed 
* target: Candidates who decide looking for a job change or not

## Exploratory Data Analysis (EDA)
* Data distribution
* Data Correlation
* Identify Missing Value
* Identify Duplicate Data
* Identify Data Imbalance

## Data Analytics
* Data Proportion
* Independent Test With Chi Square

## Data Preprocessing
* Fill Missing Value
* Data Inconsistency
* Feature Engineering
* Feature Selection

## Model Selection
* Model Benchmark
* Imbalance Data Handling
* Hyperparameter Tuning

## Explainable and Interpretable Machine Learning
* SHAP 
* Model Somulation to Data Test

## Conclusion and Recommendation
We conclude our result and give recommendation based on it

Contributors:
Abdul Hamid - abdulhamidwinoto@gmail.com  
Juan Antonio Suwardi - antonio.juan.suwardi@gmail.com  
Agatha Putri Algustie - agthaptri@gmail.com
