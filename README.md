# 🧠 Rock vs Mines Prediction Using Machine Learning

## 🌊 Project Overview

This project leverages machine learning techniques to accurately classify sonar signals as either **rock** or **mine**, based on the sonar returns. Such a system is highly beneficial for **submarines**, enabling them to predict the nature of underwater objects and navigate safely, especially in sensitive or dangerous waters.

## 🎯 Objective

The main goal is to train and evaluate a machine learning model capable of distinguishing between rocks and mines using the UCI Sonar dataset. The system supports:
- Early warning systems in submarine operations
- Safer navigation and automated decision-making
- Reduction in human error in underwater object detection

## 📦 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))
- **Instances**: 208
- **Features**: 60 continuous variables per instance, each representing energy in a particular frequency band.
- **Target classes**:
  - **R** → Rock
  - **M** → Mine

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## 🧪 Model Workflow

The notebook follows a complete ML pipeline:
1. **Data Loading & Exploration**
   - Understanding the shape, data types, and initial insights from the dataset.
2. **Data Preprocessing**
   - Encoding categorical variables
   - Feature scaling using StandardScaler
   - Train-test split
3. **Model Training**
   - Logistic Regression Classifier
4. **Evaluation Metrics**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

### ✅ Final Model Accuracy:
> **95.23%** on test data using Logistic Regression.

## 📈 Visualizations

- Countplot of label distribution (Rocks vs Mines)
- Accuracy and performance evaluation using classification metrics

## 🚀 Real-World Impact

By integrating this ML-based prediction model into submarine sonar systems:
- Operators can receive real-time alerts distinguishing rocks from mines.
- This improves operational safety and helps avoid catastrophic decisions in hostile or unfamiliar underwater environments.

## 🧠 Future Scope

- Experiment with ensemble models like Random Forests and XGBoost
- Use CNNs for advanced feature extraction on sonar spectrograms
- Real-time deployment using a REST API or embedded systems

## 📄 License

This project is open-source and available under the **MIT License**.
