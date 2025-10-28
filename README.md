# Heart Disease Prediction using Machine Learning

A comprehensive machine learning project for predicting heart disease using the UCI Heart Disease dataset. This project implements and compares multiple classification algorithms to assist in clinical decision support.

## 🎯 Project Overview

This project builds predictive models to classify heart disease presence using patient health metrics. It demonstrates the complete ML pipeline from data preprocessing to model evaluation, with a strong emphasis on ethical healthcare data handling.

## 📊 Dataset

The project uses the UCI Heart Disease dataset (`heart_disease_uci.csv`) which contains patient health information including:

- **Demographic features**: Age, sex
- **Clinical measurements**: Resting blood pressure, cholesterol levels, maximum heart rate
- **Diagnostic indicators**: Chest pain type, ECG results, exercise-induced angina
- **Target variable**: Heart disease presence (num)

## 🛠️ Technologies Used

- **Python 3.x**
- **Data Processing**: pandas, numpy
- **Machine Learning**: scikit-learn, XGBoost
- **Visualization**: matplotlib, seaborn

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction

# Install required packages
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

## 🚀 Usage

```bash
python heart_disease_prediction.py
```

Make sure the `heart_disease_uci.csv` file is in the same directory as the script.

## 🔍 Models Implemented

The project trains and evaluates three classification models:

1. **Logistic Regression** - Baseline linear model
2. **Random Forest** - Ensemble learning with 100 decision trees
3. **XGBoost** - Gradient boosting algorithm

Each model is evaluated using:
- Classification report (precision, recall, F1-score)
- Confusion matrix visualization
- Overall accuracy comparison

## 📈 Features

- **Data Preprocessing Pipeline**
  - Handles missing values
  - StandardScaler for numerical features
  - OneHotEncoder for categorical features
  
- **Model Training & Evaluation**
  - 80/20 train-test split
  - Comprehensive performance metrics
  - Visual confusion matrices
  
- **Model Comparison**
  - Side-by-side accuracy visualization
  - Detailed classification reports

## 🧠 Key Components

### Data Preprocessing
The preprocessing pipeline handles:
- **Numerical features**: Age, blood pressure, cholesterol, heart rate, etc.
- **Categorical features**: Sex, chest pain type, ECG results, slope, thal

### Model Pipeline
Each model uses scikit-learn's Pipeline to ensure:
- Consistent preprocessing across train/test sets
- Prevention of data leakage
- Streamlined prediction workflow

## 📊 Output

The script provides:
- Dataset overview and missing value analysis
- Classification reports for each model
- Confusion matrix heatmaps
- Model accuracy comparison bar chart
- Ethical guidelines for healthcare data handling

## ⚖️ Ethical Considerations

This project emphasizes responsible AI in healthcare:

1. **Privacy Protection**: De-identification of patient records
2. **Consent**: Data collection with proper authorization
3. **Compliance**: HIPAA/GDPR adherence for data privacy
4. **Fairness**: Bias mitigation across demographics
5. **Transparency**: Interpretable model outputs for clinicians
6. **Appropriate Use**: Clinical decision support, NOT standalone diagnosis

## ⚠️ Disclaimer

**This model is intended for research and educational purposes only.** It should be used as a clinical decision support tool and NOT as a replacement for professional medical diagnosis. Always consult qualified healthcare professionals for medical decisions.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Project Link: [https://github.com/yourusername/heart-disease-prediction](https://github.com/Jagtap-Atharva/Healthcare-Predictive-Analytics-Disease-Detection-)

## 🙏 Acknowledgments

- UCI Machine Learning Repository for the Heart Disease dataset
- scikit-learn and XGBoost communities
- Healthcare ML ethics guidelines from various medical institutions
