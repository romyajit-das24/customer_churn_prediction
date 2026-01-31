#  Machine Learning Classification Model 

##  Overview
This repository contains a **machine learning classification model** built as part of my **AI/ML practice**.  
The goal of this project is to understand the **end-to-end ML pipeline**, including data preprocessing, model training, evaluation, and saving the trained model.


##  Problem Type
- **Binary Classification**
- Predicts a target class based on structured (tabular) input data


##  Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn


##  Model Used
- **Random Forest Classifier**

### Why Random Forest?
- Works well on tabular datasets
- Handles non-linear relationships
- Less sensitive to feature scaling
- Provides feature importance for interpretability


##  Data Preprocessing
- Removed duplicate rows
- Handled missing values
- Dropped non-informative ID columns
- Encoded categorical features into numerical form


##  Model Training
- Dataset split into training and testing sets
- Stratified splitting used to preserve class distribution
- Model trained using default and tuned parameters


##  Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help in understanding both overall performance and class-wise behavior.


##  Model Saving
The trained model is serialized using `pickle` and saved for later use or deployment.


##  How to Run
1. Install dependencies:
```bash
pip install -r requirements.txt
