# Breast Cancer Classification

This project uses machine learning to classify breast cancer tumors as malignant or benign. It uses logistic regression model. The dataset is sourced from sklearn's built-in breast cancer dataset, and the project follows a complete machine learning workflow, from data collection to building a predictive system.

1.  The main steps of the project include:

Data Collection: Imported the breast cancer dataset from sklearn.

Data Pre-processing: Cleaned the data and prepared it for modeling.

Feature and Target Separation: Separated the features (input variables) and target (output variable).

Data Splitting: Split the dataset into training and testing sets for model evaluation.

Model Training: Trained a logistic regression model using the training data.

Model Evaluation: Evaluated the model using accuracy score metrics.

Predictive System: Built a system to predict whether a tumor is benign or malignant based on new input data.


2.  PROJECT OVERVIEW
   The dataset used for this project is the Breast Cancer Wisconsin dataset available directly through sklearn. It contains features related to cell characteristics and a target variable indicating whether a tumor is benign (non-cancerous) or malignant (cancerous).


3. The following Python libraries are required to run this project:

numpy

pandas

scikit-learn (for the dataset and logistic regression model)


Model Performance

The logistic regression model was evaluated using an accuracy score to measure its performance in classifying breast cancer cases. The accuracy score indicates how well the model predicts benign vs. malignant tumors on the test data.


Results

The model effectively classifies breast cancer tumors, with a high accuracy in distinguishing between benign (non-cancerous) and malignant (cancerous) samples.

Contributing

Contributions are welcome! If you have ideas for improving the model or adding new features, feel free to fork the repository and submit a pull request.

