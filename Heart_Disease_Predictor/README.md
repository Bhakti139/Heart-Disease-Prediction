# Heart-Disease-Prediction


This project applies **machine learning techniques** to predict whether a person is at risk of heart disease based on their clinical attributes.  
The aim is to build an accurate and interpretable model that can assist in **early detection** and **decision support** for healthcare professionals.


## 📌 Overview
Heart disease remains one of the leading causes of death worldwide. Early prediction and diagnosis play a crucial role in prevention and treatment.  
In this project, we:
- Perform **exploratory data analysis (EDA)** to identify key risk factors.
- Preprocess the data by handling missing values, encoding categorical variables, and scaling features.
- Train multiple machine learning models for prediction.
- Compare model performance using accuracy, precision, recall, and F1-score.

---

## 📊 Dataset
The dataset includes patient medical records with the following attributes:

- **Age**
- **Sex**
- **Chest Pain Type (cp)**
- **Resting Blood Pressure (trestbps)**
- **Serum Cholesterol (chol)**
- **Fasting Blood Sugar (fbs)**
- **Resting Electrocardiographic Results (restecg)**
- **Maximum Heart Rate Achieved (thalach)**
- **Exercise-Induced Angina (exang)**
- **ST Depression (oldpeak)**
- **Slope of Peak Exercise ST Segment (slope)**
- **Number of Major Vessels (ca)**
- **Thalassemia (thal)**
- **Target (1 = heart disease, 0 = no heart disease)**

## Project Structure
Heart-Disease-Prediction/
│
├── Heart_Disease_Predictor/
│ ├── Disease_Predictor.ipynb # Main Jupyter Notebook (EDA + ML)
│ ├── Disease_Predictor_Bootcamp.ipynb # Alternate/bootcamp version
│ ├── README.md # Project documentation
│
└── data

## Installation & How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/Bhakti139/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction/Heart_Disease_Predictor
2. **Set up the environment**
Install required Python packages:
pip install -r requirements.txt

3. **Run the Jupyter Notebook**
jupyter notebook Disease_Predictor.ipynb

Models Used

We experimented with the following machine learning models:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

XGBoost / Gradient Boosting (if applicable)

Each model was evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

**Results**

The models were compared, and the best-performing model was selected based on recall and overall accuracy.
Random Forest achieved the highest accuracy of 88.5% with balanced recall.

**Future Work**

Hyperparameter tuning for better performance.

Deployment of the model using Flask / FastAPI / Streamlit.

Integration with a healthcare dashboard for real-world use.

Testing on larger and more diverse datasets.

**Acknowledgements**

Dataset source: Kaggle

Inspired by heart disease prediction research and ML tutorials