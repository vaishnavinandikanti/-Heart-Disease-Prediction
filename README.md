# -Heart-Disease-Prediction

##  Project Overview
Heart disease remains one of the leading causes of mortality worldwide. This project leverages **machine learning** to predict heart disease based on various health parameters. Using advanced data analysis and predictive modeling, we aim to provide insights that could aid in early diagnosis.

##  Dataset
The dataset consists of multiple health indicators, including:
- **Demographics**: Age, Sex
- **Clinical Features**: Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar
- **Electrocardiographic Measures**: Resting ECG Results, Maximum Heart Rate Achieved
- **Exercise-Induced Stress**: Exercise-Induced Angina, ST Depression (Oldpeak), Slope of ST Segment
- **Other Factors**: Number of Major Vessels, Thalassemia

##  Technologies & Methods
###  Machine Learning Models Used:
- **Logistic Regression**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **Decision Tree**

###  Model Evaluation Metrics:
- **Accuracy**
- **Precision, Recall, and F1-Score**
- **Confusion Matrix & ROC Curve**

###  Data Visualization:
Utilized **Matplotlib** and **Seaborn** for exploratory data analysis and feature correlation insights.

##  Installation & Setup
Ensure you have the required dependencies installed:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### 💻 Running the Project
1. Clone this repository:
```bash
git clone https://github.com/vaishnavinandikanti/heart-disease-prediction.git
```
2. Navigate to the project directory:
```bash
cd heart-disease-prediction
```
3. Run the Python script:
```bash
python heart_disease_prediction.py
```

## 📊 Results & Insights
- The best-performing model achieved **88.52% accuracy** on the test set.
- A **confusion matrix** and **ROC curve** were plotted to assess performance.
