
Breast cancer is one of the most common cancers among women worldwide. Early diagnosis is crucial for effective treatment and improved survival rates. This project uses a Support Vector Machine (SVM), a powerful machine learning algorithm, to classify breast cancer as either benign or malignant based on features extracted from cell images.

Dataset:
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which is available from the UCI Machine Learning Repository. It consists of features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
Features: 30 numeric features
Classes: 2 (benign and malignant)
Samples: 569

Dependencies:
The project requires the following Python libraries:
numpy
pandas
scikit-learn
matplotlib
seaborn

Data Preparation:
Before training the model, the data needs to be prepared. This includes loading the data, handling missing values, and splitting it into training and testing sets.

Hyperparameter Tuning:
To find the best parameters for the SVM, we use GridSearchCV. This involves trying out different combinations of parameters and selecting the one that gives the best performance.

Results
The results of the model training and evaluation, including the accuracy, precision, recall, and F1-score, will be displayed in the console or notebook output. Visualizations such as the confusion matrix and ROC curve can also be generated.
