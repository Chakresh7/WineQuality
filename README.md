# Wine Quality Prediction Project
# Project Description
This project aims to build a predictive model to determine the quality of wine based on various physiochemical properties. The analysis involves data loading, exploration, preprocessing (including outlier removal), feature selection, and training a classification model.

# Data Source
The dataset used in this project is the Wine Quality dataset, which contains measurements of various attributes of red wines and their corresponding quality ratings.

# Analysis Steps
<ol>
  <li>Data Loading and Initial Exploration: Loaded the dataset and performed initial checks for shape, null values, and data types.</li>
  <li>Outlier Detection and Removal: Identified and removed outliers from the dataset using the Interquartile Range (IQR) method to improve model performance and prevent overfitting.</li>
  <li>Exploratory Data Analysis (EDA): Visualized the data distribution using boxplots and explored relationships between features using a correlation heatmap.</li>
  <li>Feature Selection: Identified important features for predicting wine quality based on correlation analysis.</li>
  <li>Data Preparation: Split the data into training and testing sets and scaled the features.</li>
  <li>Model Building and Training: Built and trained a Decision Tree classification model on the prepared data.</li>
  <li>Model Evaluation: Evaluated the performance of the trained model using metrics such as accuracy, precision, recall, and F1 score.</li>
</ol>

# Results
Accuracy: 0.5689
Precision: 0.5617
Recall: 0.5689
F1 Score: 0.5609


How to Run the Notebook
Clone the repository to your local machine.
Open the notebook in Google Colab or a Jupyter environment.
Run the cells sequentially to reproduce the analysis and model building steps.
Dependencies
The following libraries are required to run this notebook:

pandas
numpy
matplotlib
seaborn
scikit-learn
These can be installed using pip:
