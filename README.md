# Machine Learning Classification Project

## Overview
This project is a machine learning classification model that predicts binary labels based on high-dimensional input data. The model has been trained and evaluated using a dataset with **13,601 features** and achieves an accuracy of **78.28%** at a classification threshold of **0.2**.

## Dataset
- The dataset consists of **5,634** training samples and **1,409** testing samples.
- Each sample has **13,601** features.
- The dataset is split into training and testing sets, and additional data augmentation techniques have been applied.

## Model Details
- **Algorithm:** Supervised classification (model details can be expanded)
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score
- **Final Model Performance:**
  - **Accuracy:** 78.28%
  - **Precision (Class 1):** 62%
  - **Recall (Class 1):** 48%
  - **F1-Score (Class 1):** 54%
  
## How to Run
### Clone the Repository
```bash
git clone https://github.com/M26I/telco-customer-churn-dataset
cd telco-customer-churn-dataset
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Future Improvements
- Hyperparameter tuning to improve recall.
- Implementing different threshold tuning strategies.
- Deploying as a web app using **Flask/Streamlit** for easy user interaction.

## License
This project is open-source and free to use.

---


