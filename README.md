
# Breast Cancer Classification using Logistic Regression

A beginner-friendly machine learning project that classifies breast tumors as **Benign** or **Malignant** using Logistic Regression and the Breast Cancer Wisconsin (Diagnostic) dataset.

> **Disclaimer:** This project is for educational purposes only. It is not a medical diagnostic tool and must not be used to make medical or healthcare decisions.

## Dataset

- **Dataset:** Breast Cancer Wisconsin (Diagnostic)
- **Target column:** `diagnosis`
- **Classes:** Benign (`B`) and Malignant (`M`)
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Load and explore the dataset.
2. Remove unnecessary columns.
3. Convert diagnosis labels into numeric values.
4. Separate features (`X`) and target (`y`).
5. Split the data into training and testing sets.
6. Scale numerical features using `StandardScaler`.
7. Train a Logistic Regression model.
8. Evaluate the model using classification metrics and a confusion matrix.

## Model

**Algorithm:** Logistic Regression

The model was trained on the training dataset and evaluated on the test dataset.

## Results

The model achieved **96.49% accuracy** on the test set.

| Class | Precision | Recall | F1-score |
|---|---:|---:|---:|
| Benign | 0.96 | 0.99 | 0.97 |
| Malignant | 0.97 | 0.93 | 0.95 |

The model identified 93% of the malignant cases in the test set. Some malignant cases were missed, so accuracy alone is not enough to evaluate this type of model.

## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

## Repository Structure

```text
breast-cancer-classification/
├── breast_cancer_classification.ipynb
├── confusion_matrix.png
├── requirements.txt
└── README.md
```

The dataset CSV is not included in this repository. Download it from the dataset source linked above.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `breast_cancer_classification.ipynb` in Jupyter Notebook or Google Colab.
4. Download the dataset and update the file path in the notebook.
5. Run the notebook cells in order.

## What I Learned

- Data cleaning and preprocessing
- Feature and target separation
- Training and testing data splitting
- Feature scaling
- Logistic Regression classification
- Model evaluation using precision, recall, F1-score, and a confusion matrix

## Author

**Mohammed Sajib**

- GitHub: [mohammedsajib](https://github.com/mohammedsajib)

---

Created as a machine learning practice project.
