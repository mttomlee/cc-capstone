# Intrution detection using machine learning models
Capstone Project for my study in Centennial College. Course code: CBER710

## Input Data
The dataset being used in this project is obtained from Intrusion Detection Evaluation Dataset (CIC-IDS2017) given by the Canadian Institute for Cybersecurity. The whole dataset package includes information of normal and malicious network traffic which is generated from common attacks.

In the dataset there are seven dataset files in csv format containing normal and malicious network traffic. Around 5% of the whole dataset package was extracted for training and testing purpose. The extracted dataset contains 54313 data entries (26494 “normal” data and 27819 “anomaly” data) and 80 columns, which 79 columns are different network features, and one column indicates the class. The extracted dataset was saved in csv format for further
steps in the project.

## Data Scaling
In our program, `StandardScaler` and `fit_transform` function from `sklearn` library to implement Standard Scaler and transform the training and testing data.

Standard Scaler is a machine learning tool for scaling or standardising the properties of a dataset. When features are "standardised," they are changed to have a mean of zero and a standard deviation of one. It can be represented by the following equation, where x is one data sample, u is the mean of the training samples, and s is the standard deviation of the training samples:

$$
z = \frac{x-u}{s}
$$

