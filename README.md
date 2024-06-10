# Give Life: Predict Blood Donations

## Project Description

"Blood is the most precious gift that anyone can give to another person — the gift of life." ~ World Health Organization

Accurately forecasting blood supply is a crucial and ongoing challenge for blood collection managers. For instance, in January 2019, the Red Cross reported 27,000 fewer blood donations nationwide over the holidays compared to other times of the year. Leveraging machine learning to predict future blood donations can help address this issue and ultimately save more lives.

In this project, we use data from the Blood Transfusion Service Center in Hsin-Chu City, Taiwan. This center regularly sends its blood transfusion service bus to a university in Hsin-Chu City to collect donations approximately every three months. The dataset, sourced from the UCI Machine Learning Repository, includes a random sample of 748 donors. Our task is to predict whether a donor will donate blood within a specific time window. We will explore the entire model-building process, from inspecting the dataset to utilizing the TPOT library to automate the machine learning pipeline.

### Prerequisites
To complete this project, you should have knowledge of Python, pandas, and logistic regression. Familiarity with DataCamp's courses on Manipulating DataFrames with pandas, Preprocessing for Machine Learning in Python, and Foundations of Predictive Analytics in Python (Part 1) is recommended.

## Project Tasks

### 1. Inspecting the Data File
Begin by examining the `transfusion.data` file to understand its structure and contents.

### 2. Loading the Data
Load the blood donation data into a pandas DataFrame for further analysis.

### 3. Inspecting the DataFrame
Conduct an initial exploration of the DataFrame to understand its features and structure.

### 4. Creating the Target Column
Create a target column that indicates whether a donor will donate blood within the given time window.

### 5. Checking Target Incidence
Analyze the incidence of the target variable to understand the distribution of donors who will donate within the specified time frame.

### 6. Splitting the Data
Divide the DataFrame into training and testing datasets to evaluate model performance.

### 7. Selecting the Model with TPOT
Use the TPOT library to automate the selection of the best machine learning model for this prediction task.

### 8. Checking the Variance
Assess the variance in the dataset to ensure there are no features with constant values.

### 9. Log Normalization
Apply log normalization to the features to handle skewness in the data distribution.

### 10. Training the Linear Regression Model
Train a linear regression model on the training dataset and evaluate its performance on the test set.

### 11. Conclusion
Summarize the findings and discuss the effectiveness of the model in predicting blood donations.

---

Feel free to contribute to this project by forking the repository and submitting pull requests. For significant changes, please open an issue first to discuss what you would like to modify. If you find this project helpful, consider giving it a star!