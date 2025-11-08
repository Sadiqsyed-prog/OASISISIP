# OASISINFOBYTESIP
📊 OASIS INFOBYTE Internship – Data Science Projects
This repo consists of projects that I developed using open source software(collab) during my data science internship at oasis infobyte(OIBSIP).
It includes  projects that can be used to train machine learning models that can be deployed in their respective fields.

PROJECT1: 🌸Iris Flower Classification
Classifies Iris flowers into one of three species (Iris-setosa, Iris-versicolor, Iris-virginica) based on sepal and petal length/width.

Workflow
Data Loading & Inspection:

Loaded the Iris.csv dataset and performed initial analysis (head, describe, info, value_counts).

Exploratory Data Analysis (EDA):

Visualized the data using histograms, scatter plots (colored by species), a pair plot, and a correlation heatmap.

Data Preprocessing:

Dropped the unnecessary Id column.

Used LabelEncoder to convert the categorical Species target variable into numerical values (0, 1, 2).

Baseline Model Training:

Split the data (70/30) and trained five baseline classification models.

Data Cleaning:

Identified and removed four outliers from the SepalWidthCm feature using the Interquartile Range (IQR) method.

Final Model Training:

Re-split the cleaned data and re-trained the top-performing models (SVC, Logistic Regression, KNN).

Final Model & Results
After cleaning the data, both the Support Vector Classifier (SVC) and Logistic Regression models achieved 100% accuracy on the test set.

PROJECT2: 🚗Car Price Prediction
Builds a regression model to predict used car prices using key features such as age, kilometers driven, fuel type, transmission, owner, and more.

Workflow
Data Loading & Inspection:

Imported the car data.csv dataset and previewed structure (head, info, shape).

EDA & Visualization:

Analyzed price distributions, correlations, and visual patterns using histograms and scatter plots.

Data Preprocessing:

Created new feature for car age.

Used OneHotEncoder for categorical features.

Handled missing or anomalous values.

Outlier Removal:

Identified and removed outliers based on Selling_Price using IQR method.

Model Training:

Built a Pipeline using RandomForestRegressor, split data (80/20), and trained/predicted.

Feature Importance:

Visualized feature importance scores to interpret model.

Final Model & Results
Achieved high accuracy (R² ≈ 0.95) in predicting car prices on the test set.

PROJECT3: Advertising Sales Prediction
Implements a regression approach to forecast sales based on advertising budget data (TV, radio, newspaper).

Workflow
Data Loading & Analysis:

Loaded the advertising dataset and reviewed initial statistics.

EDA:

Generated scatter plots comparing each ad channel to sales, and visualized correlations.

Preprocessing:

Checked for missing data or anomalies, scaled features as needed.

Regression Modeling:

Trained linear and multiple regression models, split data for train/test, and evaluated performance.

Model Evaluation:

Compared metrics (R², RMSE, MAE) for all models.

Final Model & Results
Linear regression model delivered strong sales predictions with clear relationships identified between ad spend and sales outcome.

