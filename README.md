# Unlox_Minor_Project_4_Submission
# Random Forest Machine Learning Project – Car Evaluation

## Project Overview
This project uses the Random Forest Classification algorithm to predict car acceptability based on various features such as buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and safety.

## Dataset
- File: `car_evaluation.csv`
- Source: [Kaggle – Car Evaluation Dataset](https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set)
- Target variable: `class`
- Classes: unacc, acc, good, vgood

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

## Project Workflow
1. Import required libraries.
2. Load and explore the dataset.
3. Check and handle missing values.
4. Encode categorical variables using One-Hot Encoding.
5. Split the dataset into training and testing sets (80:20).
6. Build and train the Random Forest Classifier.
7. Make predictions.
8. Evaluate model performance.
9. Visualize feature importance.
10. Save the trained model using Joblib.

## Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Additional Features
- Cross Validation
- Hyperparameter Tuning (GridSearchCV)
- Feature Importance Visualization
- Model Saving using Joblib

## How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn joblib jupyter
   ```
3. Open the Jupyter Notebook.
4. Run all cells sequentially.

Make sure the dataset and notebook are in the same folder.

## Conclusion
This project demonstrates an end-to-end Machine Learning workflow using the Random Forest algorithm, covering data preprocessing, model training, evaluation, and feature importance analysis.
