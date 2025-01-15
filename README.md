# Thyroid_Cancer_Recurrence_Analysis-Data_Analysis

## Table of Contents Project 
- Overview
- Data Sources 
- Tools
- Data Cleaning and preperation
- EDA
- Data Analysis
- Results
- Conclusion
- Recommendations
- Future Scope


### Overview
In this project, I have analyzed a dataset that contains clinical and demographic data of patients with differentiated thyroid cancer, focusing on factors that may influence the recurrence of cancer after treatment. 
The objective was to identify patterns and correlations between various medical and lifestyle factors and the likelihood of recurrence. Using Python,I performed data cleaning, exploratory analysis, and visualization. And use libraries such as pandas, NumPy, Matplotlib, and Seaborn for the analysis.


### Data Sources : 
The dataset is collected from Kaggle and the dataset is attached in this repository 
##### Dataset Overview:

The dataset includes the following columns:

•	Age: Age of the patient at the time of diagnosis.

•	Gender: Gender of the patient (Male, Female).

•	Smoking: Current smoking status (Yes, No).

•	Hx Smoking: History of smoking (Yes, No).

•	Hx Radiotherapy: History of receiving radiotherapy (Yes, No).

•	Thyroid Function: Thyroid function test results (Normal, Hypothyroid, Hyperthyroid).

•	Physical Examination: Results from the physical examination (Normal, Abnormal).

•	Adenopathy: Presence of enlarged lymph nodes (Yes, No).

•	Pathology: Type of cancer (e.g., papillary, follicular).

•	Focality: Single or multiple tumor foci (Unifocal, Multifocal).

•	Risk: Risk stratification for recurrence (Low, Intermediate, High).

•	T: Tumor size/stage (T1, T2, T3, T4).

•	N: Lymph node involvement (N0, N1).

•	M: Distant metastasis (M0, M1).

•	Stage: Overall cancer stage (I, II, III, IV).

•	Response: Response to initial treatment (Complete, Partial, Progressive).

•	Recurred: Whether the cancer recurred (Yes, No).


### Tools
- Python

    - Pandas
    
   -  Numpy
    
    - Matplotlib
    
    - Seaborn
    
### Data Cleaning and preperation

- There were no null values and  missing values
- There is object type data type of our dataset 
- We had categorical data so we converted it using Label Encoder and by using Def function. 

The data preprocessing techniques had a positive impact on the dataset, improving its quality and enhancing the performance of the analysis


### EDA

1.	Descriptive Analysis:

2.	Clinical Factors:

3.	Impact of Treatment History:

4.	Risk Stratification:

5.	Demographic and Lifestyle Factors:

6.	Visualization of Results:


### Data Analysis
 Descriptive Analysis
-  Recurrence Rate: The overall recurrence rate of thyroid cancer in the dataset is 28.19%.
- Age and Recurrence: Younger patients (15-20 years old) have a lower recurrence rate compared to older patients.
- Gender and Recurrence: Males have a higher recurrence rate compared to females.
- Smoking and Recurrence: Smokers have a higher recurrence rate compared to non-smokers.
- Tumor Characteristics and Recurrence: Larger tumors, lymph node involvement, and advanced-stage tumors increase the recurrence risk.


### Results
Key factors to be monitored in patients at high risk of thyroid cancer recurrence:
T [Tumor]
N [Lymph]
Smoking 
Age
Gender
Recurred
Thyroid Function
This list of key factors to be monitored  can be used to inform treatment decisions and monitoring strategies for patients at high risk of thyroid cancer recurrence.

### Conclusion
The project analysis on thyroid cancer recurrence based on clinical, lifestyle, and demographic factors. It identified risk factors, including age, gender, and smoking status, and proposed optimization strategies to reduce recurrence risk. The approach can be used to develop personalized treatment plans, informing treatment decisions and improving patient outcomes. The project's findings have clinical relevance, making significant contributions to thyroid cancer research and treatment.


### Recommendations

- Quit Smoking: Smoking is a significant risk factor for thyroid cancer recurrence. Quitting smoking can reduce the risk of recurrence.
  
- Healthy Diet: A healthy diet rich in fruits, vegetables, and whole grains can help reduce the risk of recurrence.
  
- Regular Exercise: Regular exercise can help reduce the risk of recurrence by improving overall health and reducing stress.
  
- Maintain a Healthy Weight: Maintaining a healthy weight can reduce the risk of recurrence.
  
- Regular Follow-up: Regular follow-up with a healthcare provider can help detect recurrence early, when it is more treatable.
  
- Thyroid Hormone Replacement Therapy: Thyroid hormone replacement therapy can help reduce the risk of recurrence in patients with hypothyroidism.
  

### Future Scope
- Thyroid Cancer Recurrence Risk Calculator: Develop a web application that allows clinicians to input patient data and receive predictions on the likelihood of recurrence.

- Thyroid Cancer Patient Dashboard: Develop a dashboard that provides clinicians with a comprehensive view of patient data, including recurrence risk, treatment history, and lifestyle factors.

- Thyroid Cancer Predictive Model: Develop a predictive model that forecasts the likelihood of recurrence based on various factors such as patient demographics, tumor characteristics, and treatment history.






