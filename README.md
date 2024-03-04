# Hotel Booking Prediction - KNN | SMOTE | DECISION TREE

## Objective
This case study aims to equip you with practical skills in data science, focusing on predicting customer behaviors and booking cancellations in the hotel industry. I've applied EDA, KNN, Decision Tree algorithms, and learn to handle class imbalances using SMOTE.

## Notebook Content
In this notebook, the following topics have been covered:
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Predictive Modeling with KNN and Decision Tree
- Handling Class Imbalance with SMOTE
- Model Evaluation and Comparison

## Dataset Overview
Provided is the dataset of 'INN Hotels,' containing various features related to hotel bookings. The task is to analyze this data to uncover insights and predict booking cancellations.

## Preprocessing Steps
1. **Data Cleaning**: Inspect the dataset for anomalies and missing values and handle them appropriately.
2. **Data Preparation**: Apply appropriate preprocessing techniques to prepare the data for analysis, including encoding categorical variables and normalizing/scaling numerical variables.

## Exploratory Data Analysis (EDA)
- Conduct a comprehensive analysis using statistical summaries and visualizations.
- Explore relationships between different features to understand booking trends.

## Predictive Modeling
- **KNN**: Implement the K-nearest neighbors model to predict booking cancellations.
- **Decision Tree**: Use the Decision Tree algorithm for the same prediction task.
- **SMOTE**: Apply SMOTE to address class imbalance issues in the dataset.

## Model Evaluation
- Evaluate both models based on accuracy, precision, recall, and F1-score.
- Compare the performance before and after applying SMOTE to understand the impact of class balance on the model's performance.

## Handling Class Imbalance with SMOTE
- Implement SMOTE to create synthetic samples of the minority class.
- Retrain models using the balanced dataset to improve model fairness and performance.

## Results and Conclusions
The Decision Tree model outperforms the KNN model across all metrics. Applying SMOTE improved the performance of the models, indicating that class imbalance was a significant factor affecting initial model performance.

## How to Run the Notebook
To replicate this analysis:
1. Ensure that Jupyter Notebook and the following libraries are installed: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
2. Clone the repository containing the dataset and the Jupyter notebook.
3. Navigate to the project directory and launch Jupyter Notebook.
4. Open the `Hotel Assignment (Hussain) (1).ipynb` file and execute the cells in order.

## Dependencies
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Contact
For questions or feedback, please contact me at hussainmurtaza899@gmail.com.

