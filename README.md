# ❤️ Heart Rate Dataset - Physical Activity Classification

## 📌 Project Overview

This project focuses on classifying physical activities using health-related data and Machine Learning techniques.

The project uses a **Random Forest Classifier** to predict the type of physical activity based on different health parameters such as Heart Rate, SpO2, Body Temperature, Stress Level, Age, and Gender.

The model learns patterns from the dataset and classifies the corresponding physical activity.

## 🎯 Project Objectives

- Analyze heart rate and health-related data.
- Understand the relationship between health parameters and physical activities.
- Perform data preprocessing and feature encoding.
- Build a Machine Learning classification model.
- Predict physical activities using Random Forest.
- Evaluate model performance using classification metrics.
- Visualize feature correlations using a heatmap.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📊 Dataset Description

The project uses a dataset named `heart_rate_dataset.csv`.

### Features Used

| Feature | Description |
|---|---|
| Age | Age of the individual |
| SpO2 | Blood oxygen saturation level |
| BodyTemp | Body temperature |
| StressLevel | Stress level |
| HeartRate | Heart rate measurement |
| Gender | Gender of the individual |
| Activity | Physical activity category (Target Variable) |

## ⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the heart rate dataset.
3. Explore the dataset using Pandas.
4. Check missing values.
5. Encode categorical variables using LabelEncoder.
6. Select input features and target variable.
7. Split the dataset into 80% training and 20% testing.
8. Build a Random Forest Classifier.
9. Train the classification model.
10. Predict physical activities.
11. Evaluate model performance.
12. Visualize feature correlations using a heatmap.

## 🤖 Machine Learning Algorithm

**Random Forest Classifier**

Random Forest is a supervised Machine Learning algorithm that combines multiple decision trees to perform classification.

### Model Configuration

- Algorithm: Random Forest Classifier
- Number of Estimators: 100
- Random State: 42
- Train-Test Split: 80:20

### Input Features

- Age
- SpO2
- BodyTemp
- StressLevel
- HeartRate
- Gender

### Target Variable

- Activity

## 📈 Model Evaluation

The model performance is evaluated using:

- **Accuracy Score:** Measures the percentage of correctly classified predictions.
- **Confusion Matrix:** Shows correct and incorrect classification results.
- **Classification Report:** Provides Precision, Recall, and F1-Score for each activity class.

## 📉 Data Visualization

The project includes a feature correlation heatmap using Seaborn.

The heatmap helps understand relationships between numerical health-related features.

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Heart-Rate-Activity-Classification.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the Notebook

Open `HEART_RATE_DATASET.ipynb` and execute all cells.

### 5. Load the Dataset

Make sure `heart_rate_dataset.csv` is available in the correct location expected by the notebook.

## 📁 Project Structure

```text
Heart-Rate-Activity-Classification/
│
├── HEART_RATE_DATASET.ipynb
├── heart_rate_dataset.csv
└── README.md
```

## 🔮 Future Enhancements

- Compare Random Forest with other classification algorithms.
- Implement Decision Tree, KNN, and XGBoost classifiers.
- Improve model performance through hyperparameter tuning.
- Build an interactive health activity classification dashboard.
- Add more health-related features for better analysis.

## ⚠️ Disclaimer

This project is developed for educational and academic purposes only. The predictions are based on dataset patterns and should not be used for medical diagnosis or health-related decisions.

## 👨‍💻 Author

**Mohamed Aziz**

Machine Learning Project – Heart Rate Based Physical Activity Classification.

---

⭐ If you find this project useful, don't forget to star the repository!
