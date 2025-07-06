# From Exploration to Optimization: A Two-Phase Data Science Study on Heart Disease Data.
PHASE 1: Exploratory Data Analysis & Dimensionality Reduction.
Phase 1 Includes data cleaning, visualization, and unsupervised learning through dimensionality reduction using PCA.
Tasks of Phase-1 ->Task-1:Data Handling using Pandas, Task-2:Data Visualization with Matplotlib and Seaborn, Task-3:Principal Component Analysis(PCA).

PHASE 2: Supervised Learning and Model Optimization.
Phase 2 Focuses on supervised learning with classification models, boosting algorithms, and hyperparameter tuning to evaluate and improve model performance.
Tasks of Phase-2 ->Task-4:Classification Model Comparison, Task-5:Boosting and Hyperparameter Tuning.

TASK-1:Data Handling using Pandas.
OBJECTIVE:To explore and manipulate datasets using the Pandas library.
WORK DONE:I have taken a datasets that refers to the presence of heart disease in the patient where I have:
a)Loaded dataset (heart.csv) using pd.read_csv.
b)Saved dataset into Excel format using df.to_excel().
c)Extracted a single column (chol) and computed:Mean,Maximum,Minimum,Standard Deviation.

TASK-2:Data Visualization with Matplotlib & Seaborn.
OBJECTIVE:To Visualize Numerical Data for better understanding of distribution and patterns.
VISUALIZATIONS PERFORMED:a)Line Graph b)Bar Graph c)Scatter Plot d)Density Plot e)Violin Plot f)Box Plot

TASK-3:Dimensionality Reduction using PCA
OBJECTIVE:To Reduce Dimensions and Identify Principal Components.
WORK DONE:
a)Applied Principal Component Analysis(PCA) to the dataset.
b)Extracted and plotted PC1 and PC2.
Key Output:
a)Visualized the data in a 2D space using the first two principal components.
b)Used color to differentiate target classes.

TASK-4:Model Evaluation & Comparison.
OBJECTIVE:To apply and compare various supervised learning models.
Models Used:a)Logistic Regression b)Support Vector Machine(SVM) c)K-Nearest Neighbors(K-NN) d)Naive Bayes e)Decision Tree f)Random Forest
Evaluation Metric: Accuracy Score.
Result Summary:
MODEL	           ACCURACY
Logistic Regression	90.74%
Naive Bayes	90.74%
SVM	           88.88%
Random Forest	88.88%
KNN                   81.48%
Decision Tree         68.51%

TASK-5:Boosting & Hyperparameter Tuning.
OBJECTIVE:To compare boosting models and apply hyperparameter tuning.
Models Used:
a)XGBoost
b)CatBoost
Techniques for Tuning:Used GridSearchCV for-> a)Logistic Regression(tuning C) b)SVM(tuning C, kernel) c)Random Forest(tuning n_estimators, max_depth, min_samples_split)
Important Concepts:
a)Boosting: Improves performance by combining weak learners.
b)XGBoost & CatBoost: Advanced boosting algorithms for tabular data.
c)Hyperparameter Tuning: Used cross-validation(cv=5) to find optimal values.

           
