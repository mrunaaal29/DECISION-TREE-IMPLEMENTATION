# DECISION-TREE-IMPLEMENTATION

*COMPANY *: CODTECH IT SOLUTIONS

*NAME *: MRUNAL TAYDE
I
*INTERN ID *: CTIS7006

*DOMAIN *: MACHINE LEARNING

*DURATION *: 4 WEEEKS

*MENTOR *: NEELA SANTOSH


DECISION-TREE-IMPLEMENTATION on Iris Dataset

1.OVERVIEW :

This project focuses on implementing a Decision Tree Classification model using the scikit-learn library to classify flower species in the Iris dataset. The Iris dataset is one of the most commonly used datasets for introductory machine learning tasks, especially classification. This project includes data loading, exploratory data analysis, preprocessing, model development, evaluation, and visualization. A complete Jupyter Notebook is provided, along with a prediction example demonstrating how to use the trained model for new inputs.

The goal of this project is to understand how Decision Trees work, how to train them using scikit-learn, and how to visualize the structure of the tree. The project also covers how to evaluate model performance using accuracy, a confusion matrix, and classification reports.

2.DATASET DESCRIPTION :

The dataset used in this project contains 150 entries with the following attributes:

sepal_length
sepal_width
petal_length
petal_width
species

There are three species classes in the dataset:

Iris-setosa
Iris-versicolor
Iris-virginica

This dataset is known for being simple, clean, and well-structured, which makes it suitable for beginners working on machine learning classification models.

3.PROJECT STRUCTURE :

DecisionTree_Iris/
│── Iris.csv
│── DecisionTree.ipynb
│── README.md

4.OBJECTIVES :

The main objectives of this project are:

To load and explore the Iris dataset.
To visualize the relationships between its features.
To prepare the dataset for machine learning tasks.
To train a Decision Tree Classifier using scikit-learn.
To evaluate the performance of the model.
To visualize the decision-making structure of the model.
To demonstrate an example prediction using custom input values.

5.STEPS PERFORMED :

1. Importing Libraries

All required Python libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn were imported.

2. Loading the Dataset

The dataset was loaded using pandas. Columns were inspected to ensure there were no unwanted attributes such as index columns. Missing values were also checked.

3. Exploratory Data Analysis (EDA)

Exploratory analysis included viewing dataset statistics, plotting pairplots to observe feature relationships, and species count plots. This step helps in better understanding the dataset patterns before modeling.

4. Data Preprocessing

The dataset was divided into features (X) and labels (y). Unwanted columns, if present, were dropped. A train-test split was performed using an 80-20 ratio to separate data for training and evaluation.

5. Model Training

A DecisionTreeClassifier from scikit-learn was initialized and trained on the training dataset. The model was fitted using entropy criterion or default parameters depending on implementation.

6. Model Evaluation

Evaluation included calculating accuracy, generating a classification report, and plotting a confusion matrix. The Iris dataset is relatively simple, so the accuracy may range from 0.95 to 1.00 depending on training splits.

7. Decision Tree Visualization

The structure of the tree was visualized using sklearn.tree.plot_tree(). This gives insight into how the model makes decisions based on thresholds and conditions applied to feature values.

8. Prediction Example

The notebook includes an example where a new flower measurement is given to the model to predict the corresponding species. A DataFrame with column names was used to match the trained model’s feature structure.

Results

The Decision Tree model performed well on the Iris dataset, achieving high accuracy due to the dataset’s simplicity and clear class separability. The visualization of the tree structure shows how different feature thresholds influence the classification.

6.How to Run the Project :

Clone the repository.
Install the required Python libraries.
Open the Jupyter Notebook.
Run the cells one by one to reproduce the model and results.

7.FUTURE ENHANCEMENTS :
Hyperparameter tuning using GridSearchCV.
Comparison with other models such as Random Forest.
Deployment of the model using Flask or Streamlit.
Adding interactive widgets for prediction.

8.OUTPUT :

1.Dataset - first 5 rows
<img width="1052" height="414" alt="Image" src="https://github.com/user-attachments/assets/5ffbeefa-063a-4e6a-bb39-7384c63de117" />

2.Evaluation
<img width="774" height="398" alt="Image" src="https://github.com/user-attachments/assets/ad9031a7-f3fc-4610-b5c1-cde51445b749" />

3.Confusion Matrix
<img width="910" height="768" alt="Image" src="https://github.com/user-attachments/assets/109e1024-3384-4ee1-96fb-8ce0b58756f7" />

4.Decision tree visualization
<img width="1744" height="964" alt="Image" src="https://github.com/user-attachments/assets/3d7d8373-7be0-4a05-aac9-9624adb59b36" />

5.Example of prediction
<img width="550" height="248" alt="Image" src="https://github.com/user-attachments/assets/5bd42076-4561-4806-a38d-a714688f8ec0" />


