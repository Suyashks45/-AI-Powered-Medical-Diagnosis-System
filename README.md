# AI-Powered-Medical-Diagnosis-System

## 📌 **Project Overview**
This AI-Powered Medical Diagnosis System predicts the likelihood of various diseases using machine learning algorithms. Users can input their medical data to receive predictions for diseases like:
- Diabetes
- Heart Disease
- Lung Cancer
- Parkinson's Disease
- Thyroid Disease

The system utilizes a user-friendly interface built with **Streamlit** and leverages pre-trained machine learning models to provide accurate predictions.

---

## 🚀 **Features**
- Disease Prediction using Machine Learning
- Multiple Disease Support
- Data Visualization
- Explainability using SHAP for Model Interpretation
- User Data Upload for Custom Predictions
- Evaluation Metrics Dashboard

---

## 🧑‍💻 **Technologies Used**
- **Python**
- **Streamlit** for the web interface
- **scikit-learn** for machine learning models
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **SHAP** for model explainability
- **Pickle** for model serialization

---

## 📂 **Folder Structure**
```
AI medical/
│
├── app.py                   # Streamlit Application
├── Models/                  # Pretrained Models
├── Data/                    # Datasets for Predictions
├── Heart_Disease_Prediction.ipynb
├── Lung_Cancer.ipynb
├── Parkinson's_Disease_Detection.ipynb
├── Thyroid.ipynb
└── README.md
```

---

## ⚙️ **Installation Guide**

1. **Clone the Repository:**
```bash
git clone https://github.com/your_username/AI-Medical-Diagnosis.git
cd AI-Medical-Diagnosis
```

2. **Create Virtual Environment:**
```bash
python -m venv .venv
source .venv/bin/activate  # For Linux/Mac
.venv\Scripts\activate    # For Windows
```

3. **Install Dependencies:**
```bash
pip install -r requirements.txt
```

4. **Run the Application:**
```bash
streamlit run app.py
```

---

## 📊 **Usage Instructions**
1. Select a disease from the dropdown menu.
2. Enter the relevant medical data.
3. Click on the **Predict** button.
4. View the prediction result and explanation.
5. For data visualization or uploading your data, follow the prompts on the interface.

---

## 🛠 **Model Training and Evaluation**
- Datasets are preprocessed using **Pandas**.
- Models are trained using **scikit-learn**.
- Evaluation metrics like **Accuracy, Precision, Recall, and F1-Score** are displayed.
- Model explainability is provided using **SHAP**.

---

## 📧 **Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to your branch: `git push origin feature-name`
5. Submit a Pull Request.

---

## 📞 **Contact**
- **GitHub:** [Suyashks45](https://github.com/Suyashks45)
