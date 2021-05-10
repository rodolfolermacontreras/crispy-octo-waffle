# crispy-octo-waffle
Feature Engineering (Project Part 1/3)

# Problem

Explore the data from the "diaper" manufacturer, clean it, handle the class imbalance problem and apply feature selection techniques to reduce dimensionality.

# Abstract:

The capstone project focuses on diaper manufacturing quality. Generally, to ensure or predict quality, a diaper manufacturer need s to monitor every step of the manufacturing process with sensors such as heat sensors, glue sensors, glue level, etc.
For this capstone project, we will use the SECOM manufacturing Data Set from the UCI Machine Learning Repository.

The analysis is is divided the following way:

### Data exploration.
- **Merging Data**
- **Cleaning Data**
    - Missing Values
    - Repeated Values (Columns with the same value)
- **Preliminary Visual Exploration**
     - `target` Time Distribution
     - Exploration of `target` variable
     - Exploration of the first 5 features

### Feature Selection.
- **Correlation**
- **Mutual Information**
    - Visual exploration of features with higher mi value
- **Stepwise Model Selection**
- **LASSO**

### Evaluation of the Features for Future Models.
- **Train & Test Model**
- **Split Data and Class Imbalance**
- **Evaluate Model Performance**
    - Model using using Filter Methods
    - Model using using Wrapper Methods
    - Model using using Embedded Methods
- **Comparison**

### Summary/Conclusions.
