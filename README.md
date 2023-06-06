# HR-Analytics-Employee-Attrition

# Analysis of Exploratory Data (EDA)

**Abstract:**
The present study aims to investigate the factors that influence employee attrition in a company. To achieve this, a dataset containing relevant variables was used. This report describes the exploratory analysis conducted to understand the relationship between these factors and employee attrition in the company. This dataset is fictional and was created by IBM data scientists.

**Introduction:**
Data science is a rapidly growing field, and data scientists play a crucial role in analyzing and interpreting large volumes of data. As the demand for data scientists continues to increase, it is important to understand the factors that can influence employee attrition in a company. This analysis focuses on investigating these factors and their impact on employee attrition.

**Methodology:**
To conduct this analysis, a dataset containing relevant information about the company's employees was used.

**Exploratory Analysis:**
Firstly, a descriptive analysis of the variables available in the dataset was performed. Measures of central tendency such as mean and median were calculated, along with measures of dispersion such as standard deviation. Additionally, graphs and tables were constructed to visualize the distribution of the data and identify possible outliers.

Next, correlation analyses were conducted to investigate the relationship between independent variables and the target variable, i.e., the employee attrition rate. Statistical techniques were used to calculate correlation coefficients, and graphs were generated to visualize these relationships.

Correlation matrix
![image](https://github.com/JorgeMiGo/HR-Analytics-Employee-Attrition/assets/127945994/f209c924-afbe-4067-badd-a279406577b9)


Main variables
![image](https://github.com/JorgeMiGo/HR-Analytics-Employee-Attrition/assets/127945994/0c7ea05f-cf40-4ffb-8c2f-ce10b8f4eaf2)


Distance from home to work
![image](https://github.com/JorgeMiGo/HR-Analytics-Employee-Attrition/assets/127945994/13eb4f63-c0e8-4691-8099-67dc75a35204)


Total working years
![image](https://github.com/JorgeMiGo/HR-Analytics-Employee-Attrition/assets/127945994/4a6d6c0a-b75b-4533-a250-c9eefa4a1d33)


Montly income by job role
![image](https://github.com/JorgeMiGo/HR-Analytics-Employee-Attrition/assets/127945994/efd9475d-f22e-4716-8734-4dac82f4db35)


**Results:**
The results of the exploratory analysis revealed several interesting trends and relationships among the variables studied:

- The department with the highest attrition rate is Sales Representative.
- Unmarried employees are the group with the highest attrition rate.
- Attrition rate increases beyond a distance of 10 km from the workplace.
- Employee attrition is primarily observed within the first 5 years of employment.
- Manager and Research Director positions have the highest salaries, while Sales Representative has the lowest salary and the narrowest salary range. This could be one of the reasons for the higher attrition rate in this category.

# Predictive Analysis

In this study, we conducted predictive analysis using machine learning models to forecast employee attrition in the company. Two models, Logistic Regression and Random Forest, were employed to determine which model provides better predictive performance.

**Methodology:**

**Data Preprocessing:**
Before applying the models, the dataset underwent preprocessing steps to ensure data quality and model compatibility. This included handling missing values, encoding categorical variables, and scaling numerical features if necessary.

**Model Training and Evaluation:**

**Logistic Regression:**

- Logistic Regression is a popular classification algorithm that models the probability of an event occurring.
- The dataset was split into training and testing sets, with the training set used to train the model.
- The Logistic Regression model was trained using the training data, optimizing the model's parameters through the maximum likelihood estimation.
- The trained model was then evaluated using the testing set to assess its predictive performance.
- Evaluation metrics such as accuracy, precision, recall, and F1 score were computed to measure the model's effectiveness in predicting employee attrition.

**Random Forest:**

- Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions.
- Similar to Logistic Regression, the dataset was divided into training and testing sets.
- The Random Forest model was trained on the training data, with each decision tree in the ensemble learning from different subsets of the data.
- The trained Random Forest model was then evaluated using the testing set.
- Evaluation metrics, including accuracy, precision, recall, and F1 score, were calculated to assess the model's performance in predicting employee attrition.

**Results:**

After analyzing the performance of both models, it was determined that the Logistic Regression model outperformed the Random Forest model in predicting employee attrition.

- Logistic Regression achieved an accuracy of 88%, indicating that the model correctly classified 88% of the instances.
- The F1 score, which considers both precision and recall, was calculated to be 87%, demonstrating a good balance between predicting both positive and negative instances.
- Precision measures the proportion of correctly predicted positive instances, while recall assesses the proportion of actual positive instances correctly identified by the model.


Confusion Matrix Logistic Regression
![image](https://github.com/JorgeMiGo/HR-Analytics-Employee-Attrition/assets/127945994/d170aa6d-0cd1-4a62-a8ad-2b226df23b8a)


Classification Report Logistic Regression
![image](https://github.com/JorgeMiGo/HR-Analytics-Employee-Attrition/assets/127945994/54a2f467-45db-4e08-8280-00d2d30e15fe)


These results indicate that the Logistic Regression model provides reliable predictions for employee attrition. The findings from this predictive analysis can assist organizations in identifying factors and patterns that contribute to employee turnover, enabling them to take proactive measures to improve employee retention and organizational success.

## References
- https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
