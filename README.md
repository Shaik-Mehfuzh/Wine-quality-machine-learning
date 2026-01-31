# Wine-quality-machine-learning
End-to-end ML project to predict wine quality using classification models.
# 🍷 Wine Quality Prediction – End-to-End Machine Learning Project

This project builds a complete end-to-end Machine Learning pipeline to predict **wine quality** based on chemical properties.  
It includes data exploration, feature engineering, model training, hyperparameter tuning, and evaluation.

---

## 🔥 Project Highlights

✔ Real-world dataset: *winequality.csv*  
✔ Full ML pipeline: EDA → Preprocessing → Training → Tuning  
✔ 5 ML models compared  
✔ SVM with GridSearchCV for best performance  
✔ Clean and reproducible Google Colab notebook

---

## 📂 Project Structure
wine-quality-machine-learning/
│
├── wine_quality_project.ipynb # Main Jupyter notebook
├── winequality.csv # Dataset
├── README.md # This documentation
└── images/ # Plots & screenshots 

---

## 📊 Dataset Information

The dataset contains **chemical properties of wine** along with a quality score (0–10).

Goal:  
**Predict if a wine is Good (1) or Bad (0).**

| Quality Score | Label |
|--------------|--------|
| ≥ 7          | Good (1) |
| < 7          | Bad (0)  |

---

## 🧪 Models Used

- Logistic Regression  
- K-Nearest Neighbors  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- GridSearchCV + Pipeline for optimization  

---

## 🏆 Best Model

| Model | Accuracy |
|-------|----------|
| ⭐ Support Vector Machine (SVM) | **≈ Best Accuracy** |

SVM performed best after hyperparameter tuning with **RBF kernel**.

---

## 📈 Exploratory Data Analysis (EDA)

- Distribution of wine quality
- Correlation heatmaps
- Feature relationships using pairplots
- Identification of class imbalance


---

## 🚀 How to Run the Project

### **Option 1 — Google Colab (Recommended)**

1. Open the notebook  
2. Upload `winequality.csv`  
3. Run all cells  

### **Option 2 — Local Machine**

pip install -r requirements.txt
python main.py

---

## 🧠 What I Learned

- Complete lifecycle of building ML projects
- Importance of EDA and scaling
- Hyperparameter tuning using GridSearchCV
- Choosing the best model based on performance

---

## ❤️ Author

Made by SHAIK MEHFUZH

If you like this project, please ⭐ star the repo!



