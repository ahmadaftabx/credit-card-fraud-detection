# Credit Card Fraud Detection

A machine-learning project that detects fraudulent credit-card transactions using a **Random Forest classifier**. The notebook covers the full workflow—from preparing data to evaluating model performance with clear visualizations.

## Highlights

- Cleans and explores transaction data
- Builds a reproducible train/test split
- Standardizes features with StandardScaler
- Trains a tuned RandomForestClassifier
- Validates performance with 5-fold cross-validation and F1 score
- Evaluates predictions using a classification report and confusion matrix
- Visualizes feature importance, feature correlations, and the ROC–AUC curve

## Project structure

| File | Description |
| --- | --- |
| main.ipynb | Complete analysis, model training, evaluation, and visualizations |

## Tech stack

- Python
- pandas & NumPy
- scikit-learn
- Matplotlib & Seaborn

## Workflow

1. Load the credit-card transaction dataset.
2. Separate the target column (Class) and remove the identifier column (id).
3. Split the data into training and test sets.
4. Scale input features.
5. Train and validate the Random Forest model.
6. Evaluate results using F1 score, confusion matrix, classification report, and ROC–AUC.
7. Inspect feature importance and correlations.

## Getting started

1. Clone this repository.
2. Install the required Python libraries:

~~~bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
~~~

3. Place the dataset file in your preferred local data directory and update the dataset path in main.ipynb if needed.
4. Open the notebook:

~~~bash
jupyter notebook main.ipynb
~~~

## Dataset note

The original CSV dataset is not included in this repository because it exceeds GitHub's file-size limit. Download it separately and update the path in the notebook before running the project.
