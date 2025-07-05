# ML-project-Credit-Risk-Modeling
# 🧠 Neuro Finance: Credit Risk Modelling

This is my second machine learning project – a credit risk classification model that predicts whether a loan applicant will default or not using **Logistic Regression**. The model is deployed using **Streamlit** for real-time prediction and user interaction.

---

## 🚀 Demo

🔗 **Live App**: https://ml-project2-credit-risk-modeling.streamlit.app/ 
📂 **GitHub Repository**: https://github.com/Shreyash-Tote/ML-project-Credit-Risk-Modeling.git
---

## 📌 Problem Statement

Credit risk prediction is a critical task in the financial industry. This project aims to automate that by classifying loan applications as **"default"** or **"non-default"** based on input features such as income, loan amount, and credit history.

---

## 🧰 Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn (Logistic Regression)
- Streamlit
- Joblib (model saving/loading)

---

## 📊 Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical features
   - Feature selection & scaling

2. **Model Building**
   - Logistic Regression classifier
   - Evaluation: Accuracy, Precision, Recall, F1-score, ROC-AUC

3. **Deployment**
   - Created interactive Streamlit app using `main.py`
   - Integrated input form and live predictions

---

## 📈 Model Evaluation

- ✅ Accuracy: *Add your accuracy score here (e.g., 81.2%)*
- ✅ Evaluation Metrics: Precision, Recall, F1-score
- ✅ Feature Importance: Visualized using coefficient plots

---

## 💻 How to Run Locally

Make sure Python 3.7+ is installed on your machine.

```bash
# 1. Clone the repository
git clone https://github.com/Shreyash-Tote/ML-project-Credit-Risk-Modeling.git
cd ML-project-Credit-Risk-Modeling

# 2. (Optional) Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows
# OR
source venv/bin/activate  # On Mac/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run main.py
