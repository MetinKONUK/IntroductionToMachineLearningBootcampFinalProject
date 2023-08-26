<br>
<h1 align="center">Medical Cost Analysis</h1>
Dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance
In this project, you will be trying to develop an end-to-end data science application using the
dataset given above. The aim of the project is to estimate the approximate cost of a person's
health insurance based on the given variables. While creating the project, try to follow the
instructions below and make sure that the project is unique.
<h2 align="center">1. Creating a Google Colaboratory File</h2>
● Make sure your project has .ipynb extension.
● Make sure that there are comment lines explaining the details in your project.
● When submitting the project, submit the cells of this .ipynb file so that the cells are
run and the results are visible.
<h2 align="center">2. Importing Required Libraries</h2>
● Import the required libraries for the project to the Colab environment.
● Import Pandas, NumPy, Seaborn, Matplotlib and Sklearn libraries for data analysis
<h2 align="center">3. Perform An Exploratory Data Analysis</h2>
● <b> Analyze the data and draw meaningful conclusions from the data.</b>
○ Examine the distribution of Bmi (Body Mass Index)
○ Examine the relationship between “smoker” and “charges”
○ Examine the relationship between “smoker” and “region”.
○ Examine the relationship between “bmi” and “sex”.
○ Find the "region" with the most "children".
○ Examine the relationship between “age” and “bmi”.
○ Examine the relationship between “bmi” and “children”.
○ Is there an outlier in the "bmi" variable? Please review.
○ Examine the relationship between “bmi” and “charges”.
○ Examine the relationship between “region”, “smoker” and “bmi” using bar plot.
● Try to use data visualization techniques as much as possible while examining the
data.
● Please add the meanings you deduced from the analyzes as a comment line.
<h2 align="center">4. Data Preprocessing</h2>
● In this section, prepare the data you have, for training the model.
● Use Label Encoding and One-Hot Encoding techniques to deal with categorical
variables.
● Split your dataset into X_train,X_test, y_train, y_test.
● Scale the dataset by normalizing it(Min-Max Scaling or Standard Scaling).
<h1 align="center">5. Model Selection</h1>
● Select several regression models and train them with the preprocessed data.
● Examine the performances of the selected models using cross validation.
● Choose the best performing model
<h2 align="center">6. Hyper-parameter Optimization</h2>
● Optimize the hyper-parameters of the model selected in the previous step.
● Optimize parameters with Grid Search. (Grid Search or Randomized Search)
<h2 align="center">7. Model Evaluation</h2>
● Evaluate the optimized model using regression model evaluation metrics. (Ex. Mean
Squared Error, Mean Absolute Error etc.)
<br>