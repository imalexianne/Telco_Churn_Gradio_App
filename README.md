---
title: Telco_Churn_Gradio_App
app_file: gradapp.py
sdk: gradio
sdk_version: 3.34.0
---

## Description

This repository contains a machine learning-powered web application built using Gradio that predicts customer churn in the telecommunications industry. The app utilizes a pre-trained machine learning model to analyze input features such as customer tenure, monthly charges, and internet services to predict whether a customer is likely to churn or not.

Churn prediction is crucial for businesses to understand customer behavior and take proactive measures to retain valuable customers. This model takes into account a range of factors such as customer demographics, services used, billing information, and contract details to provide a prediction.

The application offers an intuitive and user-friendly interface for predicting customer churn, which can be a critical business challenge for telecommunications companies. The prediction model is based on historical customer data, making it a valuable tool for companies seeking to optimize their customer retention strategies.


# Interface Input Features
* Tenure: The number of months the customer has been with the company.
* Partner: Whether the customer has a partner (Yes/No).
* Dependents: Whether the customer has dependents (Yes/No).
* Internet Service: Type of internet service (DSL/Fiber optic/No).
* Multiple Lines: Whether the customer has multiple phone lines (Yes/No).
* Contract: Type of contract the customer has (Month-to-month/One year/Two year).
* Monthly Charges: Amount of monthly charges.
* Total Charges: Total amount charged to the customer.
* Paperless Billing: Whether the customer uses paperless billing (Yes/No).
* Payment Method: Payment method used by the customer (Electronic check/Mailed check/Bank transfer/Credit card).
* Online Security: Whether the customer has online security service (Yes/No).
* Online Backup: Whether the customer has online backup service (Yes/No/None).
* Device Protection: Whether the customer has device protection service (Yes/No).
* Tech Support: Whether the customer has tech support service (Yes/No).
* Streaming TV: Whether the customer uses streaming TV service (Yes/No).
* Senior Citizen: Whether the customer is a senior citizen (Yes/No).
* Streaming Movies: Whether the customer uses streaming movies service (Yes/No).

# Article 



# Usage

### 1. Clone this repository to your local machine.
Start by cloning the GitHub repository containing the App by running the following command in your terminal:
```
git clone https://github.com/imalexianne/Telco_Churn_Gradio_App.git
```

2. Navigate to the project directory.

 ### 2. Setup Virtual Environment
You need Python3 on your system to setup this app. Then you can clone this repo and being at the repo's root ::... follow the steps below:
* Windows
```python
    python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt 
``` 
* Linux & MacOs
```python
    python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

```
### 3. Install Dependencies:
Install the required Python packages within your virtual environment:
```
pip install -r requirements.txt
```

 # To run the Application Script
 ``````
 python gradapp.py
``````
# Pretrained Model and Analysis
To better understand the modeling and analysis behind the app, you can explore the Analysis and Modeling directory [here](https://github.com/imalexianne/churn-prediction). It contains detailed information about the data preprocessing, feature engineering, model training, and evaluation that contributed to the creation of the app's predictive capabilities.

# Feedback and Support

Email: imalexianne@gmail.com

# Author
Alexianne Imanirakarama
