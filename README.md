# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview
Heart disease is one of the leading causes of death worldwide. Early identification of high-risk patients can significantly improve treatment outcomes.  

This project implements a complete machine learning pipeline to predict the presence of heart disease using clinical and demographic data. In addition to model development, a **basic interactive user interface (UI)** is created using **ipywidgets** to allow users to input patient data and obtain predictions easily.

---

## 🎯 Problem Statement
Build a binary classification model that predicts whether a patient is likely to have heart disease based on medical attributes such as age, cholesterol, resting blood pressure, heart rate, and chest pain type.

---

## 🧠 Solution Approach
A structured machine learning workflow was followed. Logistic Regression was selected due to its simplicity, interpretability, and suitability for medical prediction problems.  
To enhance usability, a **simple interactive UI** was developed within the notebook using `ipywidgets`.

---

## 🔄 Project Workflow

Data Collection  
↓  
Data Understanding  
↓  
Data Preprocessing  
↓  
Exploratory Data Analysis (EDA)  
↓  
Feature Engineering  
↓  
Train–Test Split  
↓  
Model Training  
↓  
Model Evaluation  
↓  
Threshold Optimization  
↓  
Model Interpretation  
↓  
Cross-Validation & Robustness  
↓  
Limitations & Risk Analysis  
↓  
Interactive UI Creation (ipywidgets)  
↓  
Final Conclusion & Future Scope  

---

## 📂 Dataset Description
The dataset contains structured clinical data including:
- Demographic attributes
- Clinical measurements
- Exercise-related indicators
- Target variable indicating presence or absence of heart disease

Data preprocessing included handling missing values, encoding categorical variables, and scaling numerical features.

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to:
- Understand feature distributions
- Identify correlations
- Detect anomalies
- Analyze class balance

Insights from EDA guided feature selection and modeling decisions.

---

## 🏗️ Model Building
- Algorithm: Logistic Regression
- Reason for selection:
  - Interpretable coefficients
  - Suitable for binary classification
  - Commonly used in healthcare analytics

---

## 📊 Model Evaluation
Performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

Custom probability thresholds were tested to balance recall and precision based on healthcare priorities.

---

## 🔎 Model Interpretation
Model coefficients were analyzed to understand feature influence:
- Positive coefficient → increased heart disease risk
- Negative coefficient → reduced risk
- Odds ratios were used for intuitive interpretation

---

## 🔁 Cross-Validation & Robustness
K-fold cross-validation ensured:
- Stable performance
- Reduced dependency on a single train–test split
- Better generalization

---

## ⚠️ Limitations & Risk Analysis
- Dataset may not represent all populations
- Logistic Regression assumes linear relationships
- False negatives may have serious medical consequences

The model should be used as a decision-support tool, not a replacement for clinical judgment.

---

## 🧩 Interactive User Interface (UI) Using ipywidgets
To improve accessibility and demonstrate practical usability, a **basic interactive UI** was built using the `ipywidgets` library.

### UI Features:
- Input fields for patient attributes (age, cholesterol, blood pressure, etc.)
- A prediction button to trigger model inference
- Real-time display of heart disease prediction result

This UI allows non-technical users to interact with the trained model directly within the Jupyter Notebook or Google Colab environment, simulating a simple decision-support system.

---

## 🚀 Results Summary
- Reliable and consistent performance
- Medically meaningful feature influence
- Complete and responsible ML workflow
- Added usability through an interactive UI

---

## 🔮 Future Enhancements
- Improve UI design using Streamlit or Flask
- Deploy the model as a web application
- Integrate advanced models (Random Forest, Gradient Boosting)
- Add explainability tools such as SHAP

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- ipywidgets
- Jupyter Notebook / Google Colab

---

## 📌 Conclusion
This project demonstrates a complete machine learning lifecycle for heart disease prediction with a strong focus on interpretability, robustness, ethical considerations, and usability. The inclusion of a simple UI showcases how machine learning models can be made accessible to end users.

---

## 📎 How to Run the Project
1. Clone the repository  
2. Open the notebook in Jupyter Notebook or Google Colab  
3. Run all cells sequentially  
4. Scroll to the UI section and interact with the prediction interface  

⭐ If you find this project useful, feel free to star the repository.
