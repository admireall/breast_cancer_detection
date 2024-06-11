# breast_cancer_detection


It is a data science project
We use fine needle test report to get whether the sample is malgnin or not
We use Support Vector Machine algorithm for classification.

Project Description
This project focuses on developing a machine learning model to detect breast cancer using fine needle aspiration (FNA) test data. The goal is to accurately classify tumors as benign or malignant based on various cellular features derived from FNA samples. The model is built using a Support Vector Machine (SVM), which is known for its effectiveness in classification tasks.

Dataset
The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe characteristics of the cell nuclei present in the image.

Features
The dataset includes the following features:

ID number
Diagnosis (M = malignant, B = benign)
30 real-valued features:
Radius (mean of distances from center to points on the perimeter)
Texture (standard deviation of gray-scale values)
Perimeter
Area
Smoothness (local variation in radius lengths)
Compactness (perimeter^2 / area - 1.0)
Concavity (severity of concave portions of the contour)
Concave points (number of concave portions of the contour)
Symmetry
Fractal dimension ("coastline approximation" - 1)
Each feature is computed for each cell nucleus and averaged for each image, resulting in 10 mean features, 10 standard error features, and 10 worst (largest) features.

Methodology
Data Preprocessing:

Handling missing values
Scaling features
Splitting the data into training and test sets
Model Selection:

Using Support Vector Machine (SVM) with a radial basis function (RBF) kernel
Hyperparameter tuning using Grid Search with cross-validation to find the best parameters for the SVM
Model Training:

Training the SVM model on the training set
Evaluation:

Evaluating the model on the test set using metrics such as accuracy, precision, recall, and F1-score
