# 🌸 Iris Flower Classification using Machine Learning

This project is a beginner-friendly introduction to machine learning using the classic Iris flower dataset. We build a supervised classification model that predicts the species of an iris flower based on its petal and sepal dimensions.

---

## 📌 Project Overview

- **Problem Type**: Multi-class Classification
- **Algorithm Used**: Logistic Regression
- **Dataset**: [Iris Dataset from Kaggle](https://www.kaggle.com/datasets/uciml/iris)
- **Goal**: Classify iris flowers into Setosa, Versicolor, or Virginica

---

## 📂 Dataset Information

The dataset consists of **150 records** with 5 columns:
- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species` (Target variable)

Each species has 50 examples.

---

## 🔧 Tools and Libraries

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

---

## 🧪 Project Workflow

1. **Data Loading**  
   Load the CSV dataset using pandas.

2. **Data Cleaning**  
   Remove unnecessary columns (e.g., `Id`) and check for null values.

3. **Exploratory Data Analysis (EDA)**  
   Use visualizations like pair plots, histograms, and heatmaps to explore relationships.

4. **Label Encoding**  
   Convert string labels to numerical values for model training.

5. **Train-Test Split**  
   Split dataset into 80% training and 20% testing sets.

6. **Feature Scaling**  
   Standardize features using `StandardScaler`.

7. **Model Training**  
   Train a Logistic Regression classifier on the scaled data.

8. **Evaluation**  
   Evaluate model performance using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

---

## 📊 Results

- **Accuracy Achieved**: ~96.67%
- **Model**: Logistic Regression
- The model performs well across all 3 classes.

---

## 🖼️ Visuals

- 📌 Pairplot for feature separation
- 📌 Heatmap of feature correlations
- 📌 Confusion matrix for prediction results

---

## 💡 Future Improvements

- Try other classifiers: KNN, SVM, Random Forest, etc.
- Hyperparameter tuning with GridSearchCV
- Deploy using Streamlit or Flask as a simple web app

---

## 🚀 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/iris-flower-classification.git
   cd iris-flower-classification

##📁 Folder Structure
iris-flower-classification/
├── Iris.csv
├── iris_classifier.ipynb
├── README.md
├── requirements.txt






