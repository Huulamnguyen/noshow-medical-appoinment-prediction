# No-show Medical Appoinment Reseach
#### By Lam Nguyen
#### Institution: Adelphi University

## Introduction
- “Missed appointments cost the U.S. healthcare system $150B each year”, according to Jamie Gier, Chief Marketing Officer at SCI solution. 
- Nowadays, we manage a professional responsibility for ourselves and with friends and family, in addition to our professional obligations, it’s no surprise that some appointments, meetings, and reservations just get missed. 
- We understand the impact these missed opportunities have on our personal lives, but in the professional world (especially healthcare), the impact can be costly in both time and money. 
- The total cost of missed healthcare appointment in the United States every year is $150 billion and individual physicians an average of $200 per unused time slot. 
- Whether or not patients show up, healthcare organizations and medical practices still have to pay their staffs and cover expenses like rent and the cost of equipment. 
- But above and beyond the economic implication, no-shows have a direct impact on individual’s health. 
- A missed medical appointment could pose serious health risks for patients as it could mean the difference between catching a disease early on or too late. 
- In addition, an inefficient scheduling process can wreak havoc and raise stress levels for both a health systems’ staff and patients. 

### Problem Description
- Previous research indicates patients who miss appointments tend to be, and of lower socioeconomic status. 
- Historically, they also often have a history of failed appointments, government-provided health benefits, and psychosocial problems. 
- They are also less likely to understand the purpose of the appointment. 
- No-show rates increase with increasing time between scheduling and the actual appointment. 
- Longer waiting times have been shown to be related to lower satisfaction, which, in turn, leads to less reliable appointment keeping. 
- In addition to forgetting appointments, patients have provided several reasons for no-shows. 
- Logistical issues include trouble getting off work, childcare, transportation, and cost. 
- In addition, both patients who felt better and patients who felt too unwell to come failed to show.
### Background
- This report also considers some methods which were utilized in the past. 
For instances, I will list some previous researching reports in the same scope of this research in order to highlight the methods in the past. 
- First, I have chosen research article named “Why We Don’t Come: Patient Perceptions on No-Shows” by Naomi L. Lacy, Audrey Paulman, Matthew D. Reuter and Bruce Lovejoy (November 2004). 
They chose a qualitative design to allow broader exploration of issues and to limit the impact of the researchers’ preconceptions of the causal basis for failed appointments. 
The participants were patients at an urban, university-affiliated family practice clinic. 
The clinic is located in an ethnically diverse neighborhood and serves a predominantly low-income population. 
Interviews, conducted in the clinic’s examination rooms, were tape recorded and later transcribed verbatim. 
- The second research article is “Time and Money: Effects of No-Shows at a Family Practice Residency Clinic” by Charity G. Moore, PhD; Patricia Wilson-Witherspoon, MD; Janice C. Probst, PhD (2001). 
The method of this research article is Schedule information was retrieved for 4,055 visits over 20 business days. Data were collected on appointment status (show, no-show, cancel, walk-in), time allocated for the appointment, charges for visit, date and time of the visit, and other appointment information. 
- The third article research is ”No-shows in appointment scheduling – a systematic literature review” by Leila F.Dantas, Julia L.Fleck, Fernando L.Cyrino Oliveira, Silvio Hamacher. This research utilized data collection from Scopus database, which is the largest online database of peer- reviewed literature. 
Additionally, the analysis of surveyed studies followed a stepwise approach that included pre-analysis, material exploration, and treatment, inference and interpretation of results. 
- The fourth research article is “The Effectiveness of Outpatient Appointment Reminder Systems in Reducing No-Show Rates”, its method they surveyed patients who arrived in at the clinic. 
- The next article is “Predicting No-Shows in Radiology Using Regression Modeling of Data Available in the Electronic Medical Record”. The purpose of this research to test whether data elements available in the electronic medical record (EMR) can be effectively leveraged to predict failure to attend a scheduled radiology examination. 
They used descriptive statistics and logistic regression models to test whether these data elements could predict failure to attend a scheduled radiology examination. 
### Dataset Description
- The dataset for the capstone project is obtained from Kaggle.com, which is a healthcare provider dataset from the state in Brazil. Kaggle.com is known to hold data science project competitions.
- The dataset is on Moodle. In this dataset, there are 72,607 cases (patients) and 16 variables in total (See Table 1). Two of these 15 variables are the ID (patient and appointment ID) variable while one of them is the dependent (outcome) variable (Show up).
- Table 1. Dataset Description

Variables | Definition | 
--- | --- |
Age | Patient age | 
Gender | Patient sex | 
Month | Month of the appointment |
Appointment day | Day of the appointment | 
Lead time | Waiting time for the appointment in minute |
Calling time | The hour of calling to schedule an appointment | 
Appointment reminder | Status of receiving reminder message or call |
Alcoholism | Status of being an alcoholic | 
Financial aid | Status of having a financial support |
Handicap | Status of being handicap | 
Hypertension | Status of having high blood pressure |
Diabetes | Status of being diabetic | 
Time between appointments | Number of days between two consecutive scheduled appointments |

### Research Questions:
1.	Can we predict the no-show statuses using data analytical techniques?
2.	What are the important features in order to predict the no-show status?
3.	What is the importance of the features?
4.	How do the different sampling techniques affect the prediction of no-show statuses?
5.	How do the different feature selection methods affect the prediction of no-show statuses?
6.	How does the prediction performance for the no-show statuses change for more complex analytical models?
7.	How does the presence of outliers change the prediction performance for the no-show statuses?

### Method:
This report applies CRISP-DM, which stands for CRoss-Industry Standard Process for Data Mining
