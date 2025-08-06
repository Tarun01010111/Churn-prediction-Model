# Churn-prediction-Model
# 🔮 Churn Prediction Using Random Forest (Google Colab)

This repository hosts a machine learning project built in **Google Colab** to predict customer churn using a **Random Forest Classifier**. Churn prediction helps businesses identify customers likely to leave, so they can take proactive retention steps.

## 📌 Objectives

- Load and clean customer data
- Perform exploratory data analysis (EDA)
- Build a Random Forest model to classify churn
- Evaluate model performance using metrics and visualizations

## 🛠️ Tech Stack

- Google Colab (Python)
- Pandas, NumPy
- Matplotlib & Seaborn
- Scikit-learn

## 📁 Folder Structure
📁 churn-prediction/
├── churn_prediction.ipynb       
├── data/
│   └── customer_data.csv        
├── models/
│   └── random_forest_model.pkl  
├── images/
│   └── roc_curve.png            
├── requirements.txt             
└── README.md                  


## 🚀 Getting Started

To run this project in Google Colab:

1. Click on the notebook file `churn_prediction.py`
2. Open it in Google Colab by clicking “Open in Colab”
3. Make sure your dataset is loaded correctly (modify the path if needed)
4. Run all cells and inspect outputs

## 🧪 Model Details

- **Algorithm:** Random Forest Classifier
- **Preprocessing:**
  - Categorical encoding using LabelEncoder / OneHotEncoding
  - Imputation of missing values
  - Feature scaling if needed
- **Evaluation:**
  - Confusion Matrix
  - ROC Curve
  - Accuracy, Precision, Recall, F1 Score

## 📊 Results

The model achieved an accuracy of **XX.X%** and showed strong performance in identifying churn-prone customers. Graphs and evaluation metrics are included in the notebook.

## 📎 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Tarun**  
Connect with me or contribute to the project—let's make it better together!
