# Heart_disease_Prediction
# ❤️ Heart Disease Prediction App

This project is a Machine Learning-based application to predict whether a patient is likely to have heart disease based on various health parameters.

## 🧠 Built With
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Streamlit (for UI)

---

## 🚀 Features
- Train model using logistic regression, random forest, or other ML models.
- Predict heart disease risk using patient data.
- Interactive web interface for real-time prediction.
- Data visualization for better understanding.

---

## 📊 Dataset
The dataset used is the [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

### Features used:
- `age`
- `sex`
- `cp` (chest pain type)
- `trestbps` (resting blood pressure)
- `chol` (cholesterol)
- `fbs` (fasting blood sugar)
- `restecg` (resting ECG)
- `thalach` (max heart rate)
- `exang` (exercise-induced angina)
- `oldpeak` (ST depression)
- `slope`, `ca`, `thal`
- `target` (0 = no disease, 1 = disease)

---

## 🧪 Model Training

```bash
# Step 1: Install required packages
pip install -r requirements.txt

# Step 2: Run the training script
python train_model.py
