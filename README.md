# Lung Cancer Prediction using Naive Bayes

A machine learning project that predicts the likelihood of lung cancer based on lifestyle and demographic factors, using the Gaussian Naive Bayes algorithm.

## 📌 Overview
This project uses a small clinical/lifestyle dataset to predict whether a person has lung cancer (**Result**) based on age, smoking habits, air quality exposure, and alcohol consumption.

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (GaussianNB, StandardScaler, train_test_split)

## 🔍 Workflow
1. Loaded the dataset (59 rows, 7 columns)
2. Dropped non-predictive identifier columns (Name, Surname)
3. Checked for missing values and duplicates (none found)
4. Split data into training and testing sets (70/30)
5. Scaled features using StandardScaler
6. Trained a Gaussian Naive Bayes classifier
7. Evaluated performance using accuracy score

## 📊 Results
- **Accuracy: 94.44%**

## 📁 Dataset
Lifestyle and demographic dataset with features: Age, Smokes (frequency score), AreaQ (air quality score), Alkhol (alcohol consumption score), and Result (0 = no cancer, 1 = cancer).

## 🚀 How to Run
1. Clone this repository
2. Install dependencies: `pip install numpy pandas scikit-learn`
3. Open the notebook and run all cells

