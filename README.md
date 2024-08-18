# Spam Detector
# Overview
This project involves building and evaluating two models to detect spam: a Logistic Regression model and a Random Forest Classifier. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

# Instruction

**Data Retrieval**

The dataset can be accessed via the following link:

Spam Data

**Importing the Data**

The data is imported using Pandas. Here’s the code to load and display the DataFrame:


![image](https://github.com/user-attachments/assets/ea9b9fd7-36a7-4463-b839-159946dd075f)

The dataset contains features related to word frequencies and other attributes, and the target variable is spam.

**Data Preparation**

**Creating Labels and Features**

The target label y is the spam column, and X includes all other features.

![image](https://github.com/user-attachments/assets/f37f7588-7ca4-4b0d-b6de-86dc2074edc9)

**Checking Label Balance**

It’s important to check the balance of the labels to understand the distribution:

![image](https://github.com/user-attachments/assets/1d01d2aa-b895-48f3-b236-f21c3a9cb5e8)

**Splitting the Data**

The data is split into training and testing sets:

![image](https://github.com/user-attachments/assets/11f1ff34-4f31-4b14-8400-e0f1767e3729)

**Scaling the Features**

Standardize the feature values using StandardScaler:

![image](https://github.com/user-attachments/assets/43ff5d6d-2879-43a4-86fb-6c48b2a4024c)

**Model Training and Evaluation**

**Logistic Regression**

Train a Logistic Regression model, make predictions, and calculate accuracy:

![image](https://github.com/user-attachments/assets/fdc3ec9a-f12e-40b5-b3b5-c93f8e68aa19)

**Random Forest Classifier**

Train a Random Forest Classifier model, make predictions, and calculate accuracy:

![image](https://github.com/user-attachments/assets/49b59477-a894-4c13-9cf3-0e1b4016e330)

# Conclusion 

![image](https://github.com/user-attachments/assets/4e72ab33-5570-4f33-9abe-a53d1977af18)


















