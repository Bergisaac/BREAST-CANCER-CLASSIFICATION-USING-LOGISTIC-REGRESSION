# Breast Cancer Classification

This project uses machine learning to classify breast cancer tumors as malignant or benign.

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [repository URL]
    cd breast-cancer-classification
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas scikit-learn joblib
    ```
3.  **Download Dataset:** Place `breast_cancer.csv` in the project root. (e.g. from UCI Machine Learning Repository or Kaggle)
4.  **Run the script:**
    ```bash
    python breast_cancer_classification.py
    ```

## Files

* `breast_cancer_classification.py`: Main Python script for data processing, model training, and evaluation.
* `breast_cancer.csv`: Dataset (download separately).
* `breast_cancer_model.joblib`: Saved trained model.
* `scaler.joblib`: Saved scaler.
* `deployment_config.json`: Sample input for deployment simulation.

## Usage

The script will:

* Load and preprocess the dataset.
* Train a Logistic Regression model.
* Evaluate the model.
* Save the model and scaler.
* Simulate a deployment prediction.

## Contributing

Feel free to submit pull requests for improvements.
