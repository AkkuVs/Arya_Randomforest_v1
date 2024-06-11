Random Forest Classifier
The Random Forest classifier program (Arya_Randomforest_v1.ipynb) is a Jupyter Notebook that demonstrates the process of building and evaluating a Random Forest model using the Breast Cancer Wisconsin (Diagnostic) dataset. The dataset is used to classify tumors as either benign or malignant based on various features computed from digitized images of fine needle aspirates (FNAs) of breast masses.

Steps Included in the Program:

Importing Necessary Libraries:
The program begins by importing libraries such as pandas, numpy, sklearn, seaborn, and matplotlib.

Loading the Dataset:
The dataset is loaded from the UCI Machine Learning Repository.

Exploratory Data Analysis (EDA):
The structure and summary statistics of the dataset are examined to understand the data.

Data Preprocessing:
The 'ID' column is dropped as it is not useful for the model.
The 'Diagnosis' column is encoded to numerical values (0 for benign and 1 for malignant).

Splitting the Dataset:
The dataset is split into training and testing sets using an 80-20 split.

Building the Random Forest Model:
A Random Forest classifier is instantiated and trained on the training data.

Evaluating the Model:
Predictions are made on the test set, and the model's performance is evaluated using metrics such as accuracy, confusion matrix, and classification report.
A confusion matrix is plotted for visual representation of the model's performance.
