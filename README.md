Purpose:
The program aims to build a Random Forest Classifier model to classify breast tumors as either malignant (1) or benign (0) using features extracted from the Breast Cancer Wisconsin (Diagnostic) dataset.

Explanation:

Data Loading and Preparation:
The Breast Cancer Wisconsin (Diagnostic) dataset is fetched using the fetch_ucirepo function from the ucimlrepo library.
Features (X) and target labels (y) are extracted from the dataset.
Target labels ('M': malignant, 'B': benign) are encoded to numerical values for model training.

Data Splitting:
The dataset is split into training and testing sets using the train_test_split function with a test size of 20%.

Model Initialization and Training:
A Random Forest Classifier model is initialized with default parameters.
The model is trained on the training data using the fit method.

Model Evaluation:
Predictions are made on the test set using the trained model.
The accuracy of the model is calculated using the accuracy_score function.
A classification report is generated to provide precision, recall, F1-score, and support metrics for each class.
The confusion matrix is computed to evaluate the model's performance in terms of true positive, false positive, true negative, and false negative predictions.

Result:
The Random Forest Classifier achieves an accuracy of approximately 96.49% on the test set.
The classification report and confusion matrix provide detailed insights into the model's performance, including precision, recall, and F1-score for each class.

Conclusion:
The program successfully trains a Random Forest Classifier model to classify breast tumors based on provided features. The model demonstrates high accuracy and provides valuable metrics for evaluating its performance, making it a potentially useful tool for medical diagnosis and decision-making.
