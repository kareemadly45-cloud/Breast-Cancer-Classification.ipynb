# Breast Cancer Classification Using Artificial Neural Networks (ANN)

## 📌 Overview
This project uses machine learning models to classify breast cancer tumors as **Benign** or **Malignant** based on cell features. The goal is to assist in early diagnosis by providing accurate and reliable predictions.

## 📊 Dataset
- **Source:** Wisconsin Breast Cancer Dataset (built-in from `sklearn.datasets`)
- **Samples:** 569
- **Features:** 30 numeric features (radius, texture, smoothness, perimeter, area, etc.)
- **Target:** 0 = Malignant, 1 = Benign

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 🧠 Methodology
1. **Data Exploration:** Checked for missing values and visualized feature distributions.
2. **Preprocessing:** Scaled features using StandardScaler.
3. **Model Training:** Trained multiple models:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest
   - K-Nearest Neighbors (KNN)
4. **Evaluation:** Used accuracy, precision, recall, and F1-score to compare models.

## 📈 Results
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 96.5% | 0.96 | 0.97 | 0.96 |
| SVM | **97.2%** | **0.97** | **0.98** | **0.97** |
| Random Forest | 96.8% | 0.96 | 0.97 | 0.96 |
| KNN | 95.6% | 0.95 | 0.96 | 0.95 |

**Best Model:** SVM with 97.2% accuracy.

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/kareemadly45-cloud/Breast-Cancer-Classification.ipynb
Open the Jupyter Notebook:

bash
jupyter notebook Breast-Cancer-Classification.ipynb
Run all cells.

📊 Visualizations
Confusion Matrix

Feature Importance

Model Comparison Chart

🔮 Future Improvements
Hyperparameter tuning for better accuracy.

Testing with deep learning models (e.g., Neural Networks).

Deploying the model as a web API using Flask.

👨‍💻 Author
Kareem Ahmed Adly

GitHub: kareemadly45-cloud

LinkedIn: https://www.linkedin.com/in/kareem-adly-737016175
