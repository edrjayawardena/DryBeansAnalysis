
1. **Data Exploration and Preprocessing**:
   - Conducted exploratory data analysis (EDA) to understand the dataset.
   - Applied label encoding to convert the target column (Class) into numerical values.
   - Separated features and the target variable.
   - Split the dataset into training and testing sets.

2. **Handling Imbalanced Data**:
   - Used SMOTE (Synthetic Minority Over-sampling Technique) to balance the classes in the training set.

3. **Data Scaling**:
   - Applied StandardScaler to normalize the feature values.

4. **Model Selection**:
   - Chose several machine learning algorithms to evaluate:
     - Multi-class SVM
     - Multi-layer Perceptron (MLP)
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - Gradient Boosting

5. **Model Training and Evaluation**:
   - Trained each model using the scaled training data and evaluated its performance on the testing data.
   - Collected train and test accuracy for each model.
