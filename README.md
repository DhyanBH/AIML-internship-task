# AIML-internship-task
DATASET ANALYSIS REPORT
Task 1: Data Understanding and Preliminary Analysis
Dataset: Titanic Passenger List (CSV)

1. Data Profile

The dataset consists of a total of 891 records with 12 features capturing passenger demographics and survival status.

Data attributes include a combination of Continuous/Discrete Numerical data and Nominal/Ordinal Categorical data.

2. Core Variable Definitions

Dependent (Target) Variable: Survived (The objective is to classify whether a passenger survived).

Independent Variables (Features): * Numerical: Age, Fare, SibSp (Count of siblings/spouses), Parch (Count of parents/children).

Categorical: Sex, Embarked (Port of boarding), Pclass (Socio-economic class).
3. Data Integrity & Missing Values Initial inspection via df.info() reveals data gaps that require attention:

Age: 177 missing entries (Requires imputation strategy).

Cabin: 687 missing entries (Significant data loss; may require dropping this feature).

Embarked: 2 missing entries.

4. Summary Statistics
Average Fare: Approximately 32.20, though there is high variance in the data.

Survival Distribution: Roughly 38.4% of passengers survived, indicating a slight class imbalance.

Demographic Insight: Survival counts were significantly higher among female passengers, suggesting 'Sex' is a high-importance feature for prediction.
