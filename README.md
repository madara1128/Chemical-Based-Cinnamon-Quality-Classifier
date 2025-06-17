## 👤 Author

**Madara Weerasingha**  
📍 GitHub: [madara1128](https://github.com/madara1128)  
📍 Kaggle: [@madaraweerasingha](https://www.kaggle.com/madaraweerasingha)
# 🧪 Chemical-Based Cinnamon Quality Classifier

A machine learning project to classify the **quality of Ceylon cinnamon** (High, Medium, Low) based on its **chemical composition** using a Random Forest Classifier.

---

## 📂 Dataset

This project uses a **balanced synthetic dataset** created based on chemical properties mentioned in scientific research.

📌 Dataset link:  
➡️ [Cinnamon Quality Classification - Kaggle](https://www.kaggle.com/datasets/madaraweerasingha/cinnamon-quality-classification)

📁 Filename:  
`balanced_cinnamon_quality_dataset.csv`

### 🔬 Features included:
- `Moisture (%)`  
- `Ash (%)`  
- `Volatile Oil (%)`  
- `Acid Insoluble Ash (%)`  
- `Chromium (mg/kg)`  
- `Coumarin (mg/kg)`

### 🏷 Labels:
- `High`
- `Medium`
- `Low`

Each class has **20 samples** (Total = 60 records).

---

## 🧠 Model Details

- **Algorithm**: Random Forest Classifier  
- **Library**: scikit-learn  
- **Development Environment**: Google Colab  
- **Evaluation Metrics**: Accuracy, Classification Report, Confusion Matrix

---

## 📈 Sample Predictions

```python
# 🟨 Medium quality sample
{
  'Moisture (%)': 12.0,
  'Ash (%)': 6.5,
  'Volatile_Oil (%)': 1.1,
  'Acid_Insoluble_Ash (%)': 0.4,
  'Chromium (mg/kg)': 0.0025,
  'Coumarin (mg/kg)': 0.007
}
# → Prediction: Medium
```

```python
# 🔴 Low quality sample
{
  'Moisture (%)': 13.2,
  'Ash (%)': 7.3,
  'Volatile_Oil (%)': 0.7,
  'Acid_Insoluble_Ash (%)': 0.7,
  'Chromium (mg/kg)': 0.0035,
  'Coumarin (mg/kg)': 0.016
}
# → Prediction: Low
```

---

## 🗂️ Project Structure

```
Chemical-Based-Cinnamon-Quality-Classifier/
├── data/
│   └── balanced_cinnamon_quality_dataset.csv
├── notebooks/
│   └── cinnamon_classifier_colab.ipynb
├── README.md
└── requirements.txt
```

---

## 📌 How to Use

1. Clone the repository:

```bash
git clone git@github.com:madara1128/Chemical-Based-Cinnamon-Quality-Classifier.git
```

2. Open the Colab notebook from the `notebooks/` folder.
3. Run all cells to train and test the model.
4. Modify the sample input at the bottom to predict new quality.

---

## 🚀 Future Enhancements

- Train with real-world chemical lab data
- Add Streamlit web interface
- Use XGBoost for higher accuracy
- Export model as `.pkl` and create API

---

## 📚 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/madaraweerasingha/cinnamon-quality-classification)  
- Peradeniya University Research Paper: *Quality and Safety Aspects of Ceylon Cinnamon*

---


