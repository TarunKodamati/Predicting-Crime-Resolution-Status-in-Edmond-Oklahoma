# Predicting-Crime-Resolution-Status-in-Edmond-Oklahoma
### Project on predicting crime resolution status in Edmond, Oklahoma using machine learning

This project focuses on predicting the resolution status (solved vs. unsolved) of crime cases in Edmond, Oklahoma, using machine learning techniques. By analyzing 13,560 historical crime records from the Edmond Police Department, the study aims to identify patterns and factors that influence whether a crime is successfully resolved.

The project not only demonstrates technical expertise in data analytics and predictive modeling but also provides actionable insights that can support law enforcement decision-making and public safety strategies.

---
## Dataset

Source: Edmond Police Department

Size: 13,560 records after cleaning

Predictors: 29 (crime type, demographics, location, socioeconomic factors, etc.)

Target Variable: Binary (Solved = 1, Unsolved = 0)

Enriched Data: ZIP-code level socioeconomic features (Median Household Income, Property Value, Employment Rate) using Census and reverse geocoding APIs

---
## Methodology

### Data Cleaning & Preparation

Removed duplicates, irrelevant identifiers, and incomplete records

Handled missing values using mode/median imputation

Engineered features such as OCC_Time, DistanceFromPoliceStation, and ZIP-code socioeconomic attributes

### Exploratory Data Analysis (EDA)

Frequency distributions, histograms, boxplots

Statistical tests (T-tests, ANOVA, correlation analysis)

Identified key factors such as crime type, location, and demographics impacting case resolution

---
## Modeling & Evaluation

Models: Decision Trees (Maximal, Misclassification, Pruned, Probability), Logistic Regression (Forward, Backward, Stepwise), and Ensemble methods

Tools: SAS Enterprise Miner (primary), Python (feature engineering, geocoding)

Evaluation Metrics: Accuracy, ROC, Precision, Recall, F1-score

---
## Results

Champion Model: Probability Tree

Performance:

Accuracy: 79%

ROC: 87%

Balanced precision, recall, and F1-score

Key Predictors: Crime Code, Crime Description, Crime Against (Person/Property/Society), Subtype, Age Range, Distance from Police Station, Socioeconomic indicators

---
## Insights

Property crimes had lower resolution rates compared to crimes against society or individuals

Socioeconomic factors such as median income and property value influenced solvability

Case resolution rates varied across districts and locations (e.g., higher solvability for crimes on streets and schools compared to residences)

Temporal patterns (time of occurrence) also showed significant impact on case outcomes

---
## Tools & Skills

### Technical Skills:

SAS Enterprise Miner (data preparation, modeling, evaluation)

Python (feature engineering, geocoding APIs)

Machine Learning (Decision Trees, Logistic Regression, Ensemble models)

Data Analysis & Visualization (EDA, statistical tests, charts)

Model Evaluation (confusion matrix, accuracy, ROC, F1-score)

### Transferable Skills:

Team collaboration (5-member graduate project)

Report writing & presentation

Public safety analytics and data-driven problem solving
