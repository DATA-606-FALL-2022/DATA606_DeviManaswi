# DATA606_DeviManaswi

### Credit Card Predictive Analysis

Dataset link: https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

Youtube link: 

![image](https://user-images.githubusercontent.com/56863026/208313306-fafacc27-c165-49cd-ba01-102a14bc64c0.png)

## Background:

Even though the cash has more value than anything in this world, people prefer credit cards for payments. As we know that people use credit cards for many reasons. Most of the people use credit cards as it is safe and easy to carry around. Some of them find it easy to track their spending and get better rewards without changing their spending limits. And there is also a major reason that anyone can build their credit histories. So, with good credit history a person can get another card or housing, educational loans, insurance approved.  

Credit card applications are frequently sent to banks. In a variety of circumstances, service providers must first consider their customers' credit histories before determining whether to offer the service. Many of the applications are turned down for a variety of reasons, including large loan balances, low-income levels, or an applicant's credit report having too many enquiries. It is tedious, time-consuming, and prone to error to manually analyze these applications. In this project, we will automate the process of predicting credit card approval and credit scoring using Machine Learning algorithms. Though this it will be easy to understand what factors affect these target variables the most.

## Dataset:

Data Source: https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

There are two datasets, one is application record (54.34MB) consisting of 438557 observations and 18 variables and the other one which is credit record(15.37MB) and it has 1048575 rows and 3 columns. Common column is client id which connects both the files.  Application record consists of client’s personal and bank information. Credit record consists of client’s credit card usage information.

## Variables

1.	ID                    -     Applicant ID

2.	CODE_GENDER           -     Gender

3.	FLAG_OWN_CAR          -     Does the applicant have a car?

4.	FLAG_OWN_REALTY       -     Have Property?

5.	CNT_CHILDREN          -     Number of Children

6.	AMT_INCOME_TOTAL      -     Annual Income

7.	NAME_INCOME_TYPE      -     Income type

8.	NAME_EDUCATION_TYPE   -     Education level

9.	NAME_FAMILY_STATUS    -     Mariatal status

10.	NAME_HOUSING_TYPE     -     House type

11.	DAYS_BIRTH            -     Day of Birth

12.	DAYS_EMPLOYED         -     Start date of Employement
 
13.	FLAG_MOBIL            -     Does the applicant have a Mobile?

14.	FLAG_WORK_PHONE       -     Does the applicant have a work phone?

15.	FLAG_PHONE            -     Does the applicant have a phone?

16.	FLAG_EMAIL            -     Does the applicant have an email?

17.	OCCUPATION_TYPE       -     Occupation

18.	CNT_FAM_MEMBERS       -     Nummber of family members

19.	MONTHS_BALANCE        -     month of the extracted date

20.	STATUS                -  
    
    •	X: No loan for the month;
    
    •	C: paid off that month;
    
    •	0: 1-29 days past due;
    
    •	1: 30-59 days past due;
    
    •	2: 60-89 days overdue;
    
    •	3: 90-119 days overdue;
    
    •	4: 120-149 days overdue;
    
    •	5: Overdue or bad debts, write-offs for more than 150 days 
    
 
## Observations:

•	Understood the factors that contribute for credit card approval prediction using application records and credit records datasets through correlation, heatmap and the  FLAG_MOBIL column which doesnot have correlation was removed .

•	Identified the good and bad applicants through countplot

•	Driven insights from few univariant, bivariant distribution graphs using countplots.

•	Built models to predict credit card approval.


## Models and Approach:

•	Logistic Classification

•	Xgboost

•	SVC Classification

•	KNN Classification

•	Random Forest Classifications

•	Naive Bayes

•	Decision Tree


## Results 

The accuracy of the Logistic Regression algorithm is about 57%.

The accuracy of the Xgboost algorithm is about 87%.

The accuracy of the Random forest algorithm is about 94%. 

The accuracy of the Decision Tree algorithm is about 78%.

The accuracy of the KNN Classification algorithm is about 69%.

The accuracy of the SVC Classifier algorithm is about 73%. 

The accuracy of the Naive Bayes algorithm is about 69%.



##Reference:   

https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/discussion/119320
