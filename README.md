 Breast Cancer Classification Using K-Nearest Neighbors (KNN)

 Project Overview

This project applies Machine Learning techniques to classify breast cancer tumors as benign or malignant using the K-Nearest Neighbors (KNN) algorithm.

The project demonstrates a basic Machine Learning workflow, including data exploration, preprocessing, feature scaling, hyperparameter tuning, model training, and evaluation.

It was developed as a learning project to build practical experience in Machine Learning and supervised classification.

 Objectives

- Explore and understand a real-world medical dataset.
- Apply data preprocessing and feature scaling.
- Implement a KNN classification model.
- Select the optimal number of neighbors using GridSearchCV.
- Evaluate model performance on unseen test data.

 Dataset

The project uses the Breast Cancer Wisconsin dataset available through "scikit-learn".

Dataset characteristics:

- Number of samples: 569
- Number of input features: 30
- Task: Binary classification
- Classes: Benign and malignant

The dataset contains numerical features computed from digitized images of fine needle aspirates of breast masses.

 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

 Methodology

1. Data Exploration

The dataset was examined to understand its structure, features, target distribution, and data quality.

2. Data Preprocessing

The dataset was prepared for Machine Learning. Missing values were checked, and the features were scaled before applying KNN.

3. Train-Test Split

The data was divided into training and testing sets to evaluate how well the trained model performs on unseen samples.

4. Feature Scaling

"StandardScaler" was used to standardize feature values because KNN relies on distances between samples.

5. Model Training and Hyperparameter Tuning

The K-Nearest Neighbors classifier was trained using a Scikit-learn Pipeline.

"GridSearchCV" with 5-fold cross-validation was used to evaluate different values of "n_neighbors" from 1 to 20 and select the best-performing value.

6. Model Evaluation

The final model was evaluated using the test set. Classification performance was examined using accuracy and a confusion matrix.

 Results

Metric| Result
Best number of neighbors (K)| 7
Best cross-validation accuracy| 97.14%
Final test accuracy| 97.37%

The results indicate that the KNN model achieved high classification accuracy on this dataset.

These results describe performance on the selected dataset and test split; they do not establish clinical validity or suitability for medical diagnosis.

 Project Structure

Breast-Cancer-Model/
│
├── Machine_Learning(Breast_Cancer_Model)KNN.ipynb
└── README.md

 How to Run

This project was developed using Google Colab.

1. Open the notebook file in this repository.
2. Click Open in Colab if the option is available, or download the notebook and upload it to "Google Colab" (https://colab.research.google.com/).
3. Run the notebook cells in order.
4. Install any required libraries if they are not already available in the environment.

Most of the required libraries, including Pandas and Scikit-learn, are generally pre-installed in Google Colab.

 Key Learning Outcomes

Through this project, I practiced:

- Exploratory Data Analysis (EDA).
- Data preprocessing and feature scaling.
- Supervised Machine Learning.
- KNN classification.
- Hyperparameter tuning using GridSearchCV.
- Model evaluation using a test set and confusion matrix.

Future Improvements

Potential extensions include:

- Comparing KNN with other classification algorithms.
- Evaluating precision, recall, and F1-score.
- Investigating feature selection and its effect on performance.
- Analyzing misclassified samples.
- Improving experiment reproducibility and documentation.

Disclaimeris
This project for educational purposes only. 
It is not intended for clinical use or as a substitute for professional medical diagnosis.

Author 
Rokaya Mohamed 
Aspiring researcher interested in Computing, Bioinformatics, and Machine Learning. 
