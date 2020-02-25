# Analysis and Modeling of US Census
This notebooks contains my approach to building an estimator to predict whether or not an individual in the US Census dataset is earning more then 50.000 $ per year. After doing an exploratory data analysis to understand the different variables in the dataset, I finetuned and compared a penalized Logistic Regression Classifier and a Random Forest Classifier, comparing also different preprocessing-pipelines for the data.

The model I favor is a Logistic Regression Classifier that uses only 8 input variables, and performs with accuracy 94.24% when applied to the test data set.

I ran this notebook in Google Collab where all plots are interactively available. I included screenshots for those who are opening the file with jupyter (and don't want to redo the calculations). 

## Information about the data
This US Census dataset contains detailed but anonymized information for approximately 300,000 people. (download: http://thomasdata.s3.amazonaws.com/ds/us_census_full.zip)

The archive contains 3 files:

1) A large training file (csv)

2) Another test file (csv)

3) A metadata file (txt) describing the columns of the two csv files (identical for both)

The structure of the files should be as follows to execute the notebook:
```
.
├── Census_Analysis.ipynb
├── eda_report.html
├── us-census-full
   ├── census_income_learn.csv
   └──census_income_test.csv

```
