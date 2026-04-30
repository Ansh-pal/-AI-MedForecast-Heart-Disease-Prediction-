# 🩺 AI MedForecast – Heart Disease Prediction

A Machine Learning project that predicts the **10-year risk of Coronary Heart Disease (CHD)** using the **Framingham Heart Study dataset**.
The project leverages **Random Forest Classifier**, **SHAP explainability**, and an **interactive Gradio app** for real-time predictions.

---

## 🚀 Features

- ✅ Trained **Random Forest ML model** with **85%+ accuracy**
- ✅ **Cross-validation** for performance robustness
- ✅ **Feature importance analysis** and **SHAP-based explainability** for model transparency
- ✅ **Interactive Gradio Web App** to predict heart disease risk based on patient inputs
- ✅ Model persistence using **Joblib** for deployment readiness
- ✅ All preprocessing and prediction modules covered by **pytest unit tests**

---

## 📂 Project Structure

```
AI-MedForecast/
│-- framingham_heart_study.csv   # Dataset (download separately from Kaggle)
│-- heart_disease_model.pkl      # Saved trained model
│-- app.py                       # Main project code
│-- test_pipeline.py             # pytest unit tests
│-- requirements.txt             # Dependencies
│-- README.md                    # Project documentation
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Ansh-pal/AI-MedForecast.git
cd AI-MedForecast
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Project
```bash
python app.py
```

### 4. Launch Gradio Web App
Uncomment `demo.launch()` in `app.py` then run:
```bash
python app.py
```
Access the app at: **http://127.0.0.1:7860/**

---

## 📊 Results

| Metric | Score |
|---|---|
| Accuracy | 85%+ |
| F1-Score | 0.82 |
| Baseline (Logistic Regression) | ~73% |
| Improvement over baseline | +12% |
| pytest coverage | 90%+ |

---

## 🧠 Explainability

- **Feature Importance:** Identifies the top 10 clinical factors influencing predictions
- **SHAP Values:** Provides transparent, patient-level explanations — critical for physician trust in clinical decision support

---

## 🖥️ Example Usage

### Input:
- Age: 50
- Male: 0 (Female)
- Smoker: No
- Cholesterol: 245
- Systolic BP: 120
- BMI: 26

### Output:
```
Low Risk of CHD
```

---

## 📌 Future Improvements

- 🔹 Integrate with Electronic Health Records (EHRs)
- 🔹 Add XGBoost and Neural Network models for comparison
- 🔹 Deploy on Flask/FastAPI with cloud hosting (AWS/Azure)
- 🔹 Expand to multi-dataset scalability

---

## 🙌 Acknowledgements

- Dataset: [Framingham Heart Study — Kaggle](https://www.kaggle.com/datasets/aasheesh200/framingham-heart-study-dataset)
- Libraries: Scikit-learn, SHAP, Gradio, Pandas, NumPy, Matplotlib, pytest

---

## 📬 Contact

👤 **Ansh Pal**  
🔗 [LinkedIn](https://www.linkedin.com/in/anshpal-ap)  
💻 [GitHub](https://github.com/Ansh-pal)  
📧 pansh2004@gmail.com

---

⭐ If you found this useful, give it a star!
```
