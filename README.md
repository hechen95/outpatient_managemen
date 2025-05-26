# Study case 
## outpatient_management

### Data Set Information:
The dataset is Electronic Health Record Predicting collected from a private Hospital in Indonesia. It contains the patients laboratory test results used to determine next patient treatment whether in care or out care patient. The task embedded to the dataset is classification prediction. 
Attribute Information:
Given is the attribute name, attribute type, the measurement unit and a brief description. The number of rings is the value to predict: either as a continuous value or as a classification problem. 

Name / Data Type / Value Sample/ Description
----------------------------- 
HAEMATOCRIT /Continuous /35.1 / Patient laboratory test result of haematocrit
HAEMOGLOBINS/Continuous/11.8 / Patient laboratory test result of haemoglobins
ERYTHROCYTE/Continuous/4.65 /  Patient laboratory test result of erythrocyte
LEUCOCYTE	/Continuous /6.3 / Patient laboratory test result of leucocyte
THROMBOCYTE/Continuous/310/ Patient laboratory test result of thrombocyte
MCH/Continuous /25.4/ Patient laboratory test result of MCH
MCHC/Continuous/33.6/ Patient laboratory test result of MCHC
MCV/Continuous /75.5/ Patient laboratory test result of MCV
AGE/Continuous/12/ Patient age
SEX/Nominal – Binary/F/ Patient gender
SOURCE/Nominal/ {in,out}/The class target in.= in care patient, out = out care patient

# Assignment 
## Prediction on Diabetes Patient's Hospital Readmission
Problem Statement and Objective: A hospital readmission is when a patient who is discharged from the hospital, gets re-admitted again within a certain period of time. Hospital readmission rates for certain conditions are now considered an indicator of hospital quality, and also affect the cost of care adversely. For this reason, Centers for Medicare & Medicaid Services established the Hospital Readmissions Reduction Program which aims to improve quality of care for patients and reduce health care spending by applying payment penalties to hospitals that have more than expected readmission rates for certain conditions. Although diabetes is not yet included in the penalty measures, the program is regularly adding new disease conditions to the list, now totaling 6 for FY2018. In 2011, American hospitals spent over $41 billion on diabetic patients who got readmitted within 30 days of discharge. Being able to determine factors that lead to higher readmission in such patients, and correspondingly being able to predict which patients will get readmitted can help hospitals save millions of dollars while improving quality of care. So, with that background in mind, we used a medical claims dataset (description below), to answer these questions:

- What factors are the strongest predictors of hospital readmission in diabetic patients?

- How well can we predict hospital readmission in this dataset with limited features?
