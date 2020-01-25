# EDA

## Summary : 

  Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.
  
## Feature Cleaning, Engineering, and Imputation :

**Cleaning**: To clean our data, we'll need to work with:

- **Missing values**: Either omit elements from a dataset that contain missing values or impute them (fill them in).
- **Special values**: Numeric variables are endowed with several formalized special values including ±Inf, NA and NaN. Calculations involving special values often result in special values, and need to be handled/cleaned.
- **Outliers**: They should be detected, but not necessarily removed. Their inclusion in the analysis is a statistical decision.
- **Obvious inconsistencies**: A person's age cannot be negative, a man cannot be pregnant and an under-aged person cannot possess a drivers license. Find the inconsistencies and plan for them.

## Engineering: There are multiple techniques for feature engineering :

- **Decompose**: Converting 2014-09-20T20:45:40Z into categorical attributes like hour_of_the_day, part_of_day, etc.
- **Discretization**: We can choose to either discretize some of the continuous variables we have, as some algorithms will perform faster. We are going to do both, and compare the results of the ML algorithms on both discretized and non discretised datasets. We'll call these datasets:
          dataset_bin => where Continuous variables are Discretised
          dataset_con => where Continuous variables are Continuous
- **Reframe Numerical Quantities**: Changing from grams to kg, and losing detail might be both wanted and efficient for calculation.
- **Feature Crossing**: Creating new features as a combination of existing features. Could be multiplying numerical features, or combining categorical variables. This is a great way to add domain expertise knowledge to the dataset.

## Imputation: We can impute missing values in a number of different ways:

- **Hot-Deck**: The technique then finds the first missing value and uses the cell value immediately prior to the data that are missing to impute the missing value.
- **Mean-substitution**:  Another imputation technique involves replacing any missing value with the mean of that variable for all other cases, which has the benefit of not changing the sample mean for that variable.
