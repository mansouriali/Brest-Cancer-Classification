# Brest-Cancer-Classification

In this project, I used Breast Cancer Wisconsin (diagnostic) dataset, imported from Scikit Learn and applied different ML algorithms to diagnose cancer scans.
The label is binary (benign or malignant)  and relatively balanced. 62.74% are positive and 37.26 are negative cases and the datset has 569 samples with 30 features;
 
I compared the performance of different classification algorithms including:

    1) Support Vector Machine
    2) Logistic Regression
    3) Decision Tree
    4) Random Forest
    5) Gradient Boosting Tree

The steps were:

    1) Dividing the data into Training and Testing sets (Train 85%-Test 15% split)
    2) Scaling the data using StandardScaler
    3) Defining the model and fitting the data; (Cross Validation was used to find the best parameters)
    4) Calculating the performance metrics
