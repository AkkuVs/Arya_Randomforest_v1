Purpose:
The program aims to build a Support Vector Classifier (SVC) model to classify breast tumors as either malignant (1) or benign (0) using features extracted from the Breast Cancer Wisconsin (Diagnostic) dataset.

Explanation:

Installation and Importing Libraries:
The program begins by installing the ucimlrepo library using pip and importing necessary libraries such as pandas, numpy, train_test_split, accuracy_score, classification_report, confusion_matrix, and SVC from scikit-learn.

Fetching Dataset:
The fetch_ucirepo function from the ucimlrepo library is used to fetch the Breast Cancer Wisconsin (Diagnostic) dataset with id=17. The dataset contains features and target labels for breast tumors.

Data Preparation:
The features (X) and target labels (y) are extracted from the fetched dataset.
Target labels ('M': 1, 'B': 0) are encoded to numerical values for model training.

Splitting Data:
The dataset is split into training and testing sets using the train_test_split function. 80% of the data is used for training (X_train, y_train), and 20% is used for testing (X_test, y_test).

Model Training:
An SVC model with a linear kernel is initialized and trained on the training data (X_train, y_train) using the fit method.

Model Evaluation:
Predictions are made on the test set (X_test) using the trained model.
The accuracy of the model is calculated using the accuracy_score function.
A detailed classification report containing precision, recall, F1-score, and support is generated using the classification_report function.
The confusion matrix is computed using the confusion_matrix function to evaluate the model's performance in terms of true positive, false positive, true negative, and false negative predictions.

Result:
The accuracy of the SVC model on the test set is approximately 94.74%.
The classification report provides detailed metrics for each class (benign and malignant), including precision, recall, and F1-score.
The confusion matrix illustrates the distribution of correct and incorrect predictions made by the model.

Conclusion:
The program successfully trains an SVC model to classify breast tumors as benign or malignant based on the provided features. The model achieves high accuracy and provides detailed insights into its performance, which can be useful for medical diagnosis and decision-making.






