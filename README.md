# Adult-Census-Income
## Introduction
For this project, I used a standard imbalanced machine learning dataset referred to as the “Adult Income Census” dataset. The dataset is credited to Ronny Kohavi and Barry Becker and was drawn from the 1994 United States Census Bureau data and involves using personal details such as education level to predict whether an individual will earn more or less than $50,000 per year.
## Data Source.
I got my data for this project from kaggle. Here is the link: https://www.kaggle.com/datasets/uciml/adult-census-income

## Dataset description
The dataset used consists of 14 attributes and a class label telling whether the income of the individual is less than or more than 50K a year. These attributes range from the age of the person, the working class label to relationship status and the race the person belongs to. The dataset contained null values, both numerical and categorical values. The categorical values were both nominal and ordinal. Since the missing values were represented by ‘?’, they were replaced by NAN values and removed after detection. After necessary data manipulation and cleaning. The dataset consists of 30,139 rows and 15 columns.
## EDA
And some of the insights i could get from the report include.
•	The youngest and oldest age in the dataset is 17 and 90 respectively 
•	The mean age is 36.44
•	The workclass column contain 7 unique workclass with individuals working in the private sector representing a significant portion of our dataset.
•	85% of the individuals are white.
•	Males are twice the number of Females
## Feature Engineering
Prior to modeling, it is essential to encode all categorical features (both the target feature and the descriptive features) into a set of numerical features. Since all of the descriptive features appear to be nominal, i performed one-hot-encoding.This dataset contains a typical example of class imbalance, This problem is handled using SMOTE (Synthetic Minority Oversampling Technique).
## Machine Learning Classifiers
i used seven different type of classification models for this project and after modelling the best is the LGB model.
