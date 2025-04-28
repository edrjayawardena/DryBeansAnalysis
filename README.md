🧠 Machine Learning Classification Project
🚀 Overview
This project applies machine learning techniques to classify data with an emphasis on proper data preprocessing, balancing classes, and evaluating multiple algorithms for the best performance.

The workflow involves:

Exploratory Data Analysis (EDA)

Handling class imbalance

Feature scaling

Model selection, training, and evaluation

📊 Data Exploration and Preprocessing
EDA: Performed Exploratory Data Analysis to understand data distribution, missing values, and class imbalance.

Label Encoding: Converted the target column (Class) into numerical values to prepare for model training.

Train-Test Split: Separated the dataset into training and testing subsets to evaluate model generalization.

⚖️ Handling Imbalanced Data
Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the classes in the training data.

Improved model performance by preventing bias towards majority classes.

📈 Feature Scaling
Used StandardScaler to normalize feature values.

Ensured features are on the same scale, helping algorithms converge faster and perform better.

🛠️ Machine Learning Models
Evaluated and compared the following algorithms:

Support Vector Machine (SVM)

Multi-layer Perceptron (MLP)

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

K-Nearest Neighbors (KNN)

Gradient Boosting Classifier

Each model was trained on the scaled training data and evaluated based on accuracy.
