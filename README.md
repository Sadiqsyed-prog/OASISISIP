
#  🌸Iris Flower Classification

Classifies Iris flowers into one of three species (Iris-setosa, Iris-versicolor, Iris-virginica) based on sepal and petal length/width.


## Goal

## workflow
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

## how to run
clone this repo :
```bash
git clone
https://github.com/Sadiqsyed-prog/OASISISIP.git
## PROJECT2: