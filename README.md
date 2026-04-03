Iris Flower Classification – Machine Learning Project

📌 Project Overview

This project builds and evaluates machine learning models to classify iris flowers into species based on morphological measurements. The analysis follows a full data science workflow including exploratory data analysis, model training, evaluation, and cross-validation.

The goal is to identify which classification algorithm performs best for predicting iris species using petal and sepal measurements.

🎯 Objectives

The main objectives of this project are:

• Explore and understand the dataset through visualization and statistical summaries.

• Train multiple machine learning classification models.

• Evaluate model performance using accuracy, confusion matrix, and cross-validation.

• Compare models to determine the best performing algorithm.

📊 Dataset

This project uses the classic Iris Flower Dataset.

Dataset characteristics:

Number of samples: 150

Number of features: 4

Number of classes: 3

Features:

• Sepal Length

• Sepal Width

• Petal Length

• Petal Width

Target variable:

• Iris Species

1. Setosa
3. Versicolor
4. Virginica

🛠 Tools and technologies

Programming language

• Python

Libraries

• Pandas

• NumPy

• Matplotlib

• Seaborn

• Scikit-learn

Development Environment

• JupyterLab

🔎 Project workflow

1️⃣ Data Loading and Inspection

Dataset was imported, and converted into a Pandas DataFrame for analysis, and inspected using Pandas functions such as info(), describe(), and head(). and converted into a Pandas DataFrame for analysis.

2️⃣ Exploratory Data Analysis

EDA was performed to understand feature distributions and relationships between variables. Visualizations were used to explore relationships between flower measurements and species categories.

Techniques used:

• Pair plots

• Feature distribution plots

• Correlation analysis

Key observation: Petal length and petal width strongly separate iris species.

3️⃣ Data Preparation

Steps performed:

• Feature matrix (X) and target variable (y) separation

• Train-test split for model evaluation

• Data scaling where necessary

 🤖 Machine Learning Models

The following classification models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

📈 Model Evaluation

Models were evaluated using:

• Accuracy Score

• Confusion Matrix

• Cross-Validation

• Standard Deviation of validation scores

📊 Results

| Model               | Mean Accuracy |
| ------------------- | ------------- |
| Logistic Regression | 0.91          |
| Decision Tree       | 0.93          |
| Random Forest       | 0.95          |

Cross-validation results for Random Forest:

Mean Accuracy ≈ 0.94–0.96
Standard Deviation ≈ 0.07

Random Forest performed best due to its ensemble learning mechanism which reduces overfitting and improves generalization.

📉 Confusion Matrix Insight

The confusion matrix showed strong diagonal values indicating correct classification for most samples.

Example:

| Predicted  | Setosa | Versicolor | Virginica |
| ---------- | ------ | ---------- | --------- |
| Setosa     | 10     | 0          | 0         |
| Versicolor | 0      | 9          | 1         |
| Virginica  | 0      | 0          | 11        |

This indicates very strong classification performance.

🔬 Cross-Validation Insight

Cross-validation was applied to measure model stability across multiple training splits.

Example scores:

Accuracy Scores
[0.86, 1.00, 1.00, 1.00, 0.86]

Mean Accuracy
0.946

Standard Deviation
0.073

The model performs consistently across different subsets of data.

🚀 Future improvements

Possible extensions of this project:

• Hyperparameter tuning using GridSearchCV

• Visualizing decision boundaries

• Deploying the model as a web application

• Testing additional algorithms such as Support Vector Machines

📚 Skills Demonstrated

This project demonstrates skills in:

• Exploratory Data Analysis

• Machine Learning Model Training

• Model Evaluation and Validation

• Python Data Science Libraries

• Data Visualization

👨‍💻 Author 

* GitHub: [@ezrakomen693](https://github.com/ezrakomen693)

