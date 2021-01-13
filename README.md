# PredictingUSPermanentVisaApplicationDecisionsUsingMLmodels
Using classification ML models to predict US permanent visa application decisions

The objective of our project is to design a machine learning based system that could help in predicting US visa application decisions based on various input features like employer name, class of admission, country of citizenship etc.

This system will be useful for the employers who actively file for visa applications for their international employees every year

We will also try to identify what are the most important factors that help in predicting if a certain application will be certified or denied

Dataset Description
The US Permanent Visa Applications dataset has been collected and distributed by US Department of Labor. This dataset is available on Kaggle and contains a detailed information on 374k visa decisions between 2011-2016. The target variable consists of ‘Certified’ and ‘Denied’ decisions for each application. The dataset is highly imbalanced and consists of input features like employer name, employee education, class of admission etc.

Target attribute: case_status (0-Denied) and (1-Certified)

Some input features:
case_number: contains the case number for the visa application
class_of_admission: contains the class of admission like H1-B, F1, J1, L1 etc
country_of_citizenship: consists of country of citizenship of employees
decision_date: consists of date on which visa decision was made - employer_city: contains employer city
employer_country: contains the employer country
employer_name: contains the employer name
employer_num_employees: consists of total number of employees under an employer
employer_phone: contains the employer phone number - employer_postal_code: contains the employer postal code
pw_soc_code: consists of the ocuupation code assoicated with the job - pw_unit_of_pay_9089: consists of income associated with the job

