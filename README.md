# EDA-and-Statistical-analysis
Exploratory Data Analysis (EDA) uncovers patterns through visuals and summaries. Statistical Analysis applies math to draw inferences. Together, they reveal insights, test hypotheses, and inform decisions, forming a robust data analysis foundation.

![images](https://github.com/Ashuk2810/EDA-and-Statistical-analysis/assets/97400304/b380aa62-fc98-4464-9014-d3cf02d4999a)


# Introduction to the Problem Statement.

● Part -I is concept based and walks through various concepts of descriptive
statistics, probability distributions and inferential statistics including confidence
intervals and hypothesis testing.

● Part -II on the other hand is dataset based and exploring various data cleaning
options, data analysis options and using EDA to derive deep and meaningful
insights for the business

# Data Description

● Part-I

● The ages of CEOs of 42 Top Fortune 500 Companies when they took over the post of CEO
was given and this data was enough for answering questions given in part –I

● Part-II

● The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807
transactions.

● It contains only numeric input variables. due to confidentiality issues, Features V1, V2, … V28 are the
principal components obtained with PCA, the only features which have not been transformed with PCA
are 'Time' and 'Amount’.

# Data Cleaning Steps

● In First part we have small number of values , we checked for outliers using boxplot
and found two outliers.

● In second part we Checked for the missing values and no values were missing

● Checked the datatype, number of non-null values and name of each variable in the
dataset using df.info() and all were numerical values

● We have Checked if there are any non-real characters in the dataset and we don’t have
any non-real characters.

● Performed data analysis to derive deep and meaningful insights for the business

● Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the
dataset.

● The feature 'Amount' is the transaction Amount,

● Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise
