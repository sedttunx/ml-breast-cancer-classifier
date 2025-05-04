# Breast Cancer Tumor Classification 🧬

This project involves developing a machine learning model to classify breast cancer tumors as **benign** or **malignant** based on cell features from a well-known dataset.

📌 Project Goal

The main objective is to assist in early diagnosis of breast cancer by building an accurate classification model using machine learning algorithms. Early detection is critical in improving patient outcomes and treatment planning.

🧪 Dataset

- **Dataset Name**: Breast Cancer Wisconsin (Diagnostic) Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features**: 30 numerical features derived from digitized images of fine needle aspirate (FNA) of breast mass
- **Target**: 
  - `0` → Malignant  
  - `1` → Benign

## 🧠 Models Used

- ✅ **Support Vector Machine (SVM)** – Achieved best performance with **97.20% accuracy**
- ⚙️ **Random Forest (with Grid Search optimization)** – Final test accuracy: **96.50%**

## 🔧 Techniques & Tools

- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)
- Data Preprocessing: Cleaning, feature scaling, train-test split
- Hyperparameter Tuning: GridSearchCV
- Model Evaluation: Accuracy, Confusion Matrix, Classification Report

## 📊 Results

| Model            | Test Accuracy |
|------------------|---------------|
| SVM              | 97.20%        |
| Random Forest    | 96.50%        |

## 💡 Conclusion

This study shows that machine learning models, especially SVM and optimized Random Forest, can achieve high accuracy in classifying breast tumors. Such systems can support medical professionals in making early and reliable diagnoses, ultimately improving patient care.

## 🚀 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the main notebook or script
python main.py
