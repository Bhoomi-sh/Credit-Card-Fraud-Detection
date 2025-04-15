# Project Name 
💳 Credit Card Fraud Detection using Logistic Regression
This project presents a machine learning-based solution to detect fraudulent credit card transactions using a Logistic Regression model built with Python. The goal is to classify transactions as either legitimate or fraudulent, based on patterns found in historical transaction data.

# Discription
📌 Project Objective
The objective of this project is to develop an efficient fraud detection model that:

Uses supervised machine learning to classify transactions.

Leverages the Logistic Regression algorithm for binary classification.

Achieves high accuracy, precision, recall, and F1 score.

Helps financial institutions mitigate online transaction fraud.

📊 Dataset
The dataset used is from Kaggle, containing anonymized credit card transactions over two days.

Includes 284,807 transactions, where only 492 are frauds (~0.172%).

Highly imbalanced, requiring preprocessing.

Features: Time, Amount, and 28 anonymized variables (V1 to V28).

Label column: Class (0 = Legitimate, 1 = Fraudulent)

🔍 Features of the Project
Data Cleaning and Preprocessing

Missing value handling

Feature encoding

Data scaling

Data Visualization

Class distribution

Correlation matrix

Heatmaps

Model Building

Logistic Regression implementation with scikit-learn

Train-test split

Model Evaluation

Confusion Matrix

Accuracy, Precision, Recall, F1-score

Visualization of performance metrics

🛠️ Technologies & Tools Used
Python (Jupyter Notebook)

Libraries:

NumPy, Pandas – Data manipulation

Matplotlib, Seaborn – Visualization

scikit-learn – ML modeling

Anaconda + Jupyter environment

📈 Model Performance

Dataset	Accuracy	Precision	Recall	F1-Score
Training	99%	99%	99%	0.90
Testing	99%	99%	99%	0.90
The model demonstrated consistent performance across training and testing datasets, indicating robustness in detecting fraudulent activity.

📂 Folder Structure
kotlin
Copy
Edit
📁 Credit-Card-Fraud-Detection/
├── 📄 README.md
├── 📄 fraud_detection_logistic_regression.ipynb
├── 📁 data/
│   └── creditcard.csv
├── 📁 visuals/
│   ├── heatmap.png
│   ├── correlation_matrix.png
│   └── fraud_vs_legit_plot.png
🧠 Key Takeaways
Logistic Regression is highly effective for binary classification problems like fraud detection.

Data preprocessing (scaling, encoding, balancing) is crucial to boost model accuracy.

Even simple models can yield high performance when data is well-prepared.

Machine learning can play a critical role in ethical, real-time financial fraud prevention.

📚 References
Kaggle Dataset: Credit Card Fraud Detection Dataset

Bhoomi Sharma, MSc Dissertation, University of the West of Scotland


