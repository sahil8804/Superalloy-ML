 # 🔥 Relaxation of Superalloy at High Temperature during Cyclic Loading – Machine Learning Predictions

This project applies machine learning techniques to model and predict the relaxation behavior of superalloy materials subjected to high temperature cyclic loading. Understanding relaxation behavior is crucial for aerospace, turbine, and high-temperature engineering applications, where superalloys must withstand extreme thermal and mechanical stress.

The goal of this project is to analyze material behavior under repeated thermal cycles and develop ML-based predictive models that estimate relaxation characteristics with high accuracy.

---

## ✅ Project Highlights

- Predicts relaxation response of superalloys at elevated temperatures
- Uses machine learning models to analyze cyclic loading behavior
- Data preprocessing and feature engineering for high temperature material datasets
- Model comparison and evaluation (regression models, tree based models, etc.)
- Notebook implementation for easy experimentation and visualization

---

## 📁 Repository Structure

```

Superalloy-Relaxation-ML/
├── ml1min.ipynb        # Main Jupyter Notebook (ML model training + results)
├── data/               # (Optional) Material dataset if included
├── models/             # Saved ML models (if exported)
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies (optional)

````

---

## 🧪 Problem Description

Superalloys experience **stress relaxation** when exposed to:
- High temperature
- Repeated mechanical loading
- Thermal cycling

This project predicts:
- Relaxation rate
- Stress drop values
- Material response trends during cyclic loading

Machine learning helps capture nonlinear patterns that traditional material models may struggle with, enabling better prediction and material design insights.

---

## 🧠 Machine Learning Approach

The notebook includes:

### ✔ Data Preparation
- Handling missing values  
- Normalization and scaling  
- Feature extraction from temperature, stress cycles, time series outputs  

### ✔ Models Used
Examples of models used (modify based on your notebook):
- Linear Regression  
- Random Forest Regressor  
- XGBoost  
- Neural Network models  
- Polynomial Regression  

### ✔ Evaluation Metrics
- MAE  
- MSE  
- R² Score  
- Error distribution plots  

### ✔ Visualizations
- Stress relaxation curves  
- Predicted vs actual plots  
- Feature importance charts  

---

## ▶️ How to Run

### 1. Clone this repository
```bash
git clone https://github.com/sahil8804/Relaxation-of-Superalloy-ML.git
cd Relaxation-of-Superalloy-ML
````

### 2. Install dependencies

If you have a `requirements.txt`:

```bash
pip install -r requirements.txt
```

Or install basic ML packages:

```bash
pip install numpy pandas matplotlib scikit-learn
```

### 3. Open the Jupyter Notebook

```bash
jupyter notebook ml1min.ipynb
```

Run all cells to reproduce training, testing, and predictions.

---

## 📊 Results Summary

This project demonstrates that ML models can effectively approximate relaxation behavior of superalloys under high temperature cyclic loading, showing promising accuracy in predicting stress relaxation curves.

(Add your specific accuracy scores or findings here.)

---

## 🚀 Future Improvements

* Add deep learning models (LSTM, GRU for time-dependent patterns)
* Expand dataset for more alloy compositions
* Implement real time prediction interface
* Compare ML predictions with physics based material models

---

## 📄 License

This project is open source and free to use for research and educational purposes.

---

## 🙌 Author

**Sahil**
GitHub: [https://github.com/sahil8804](https://github.com/sahil8804)

---

If you want, I can:

* Add formulas
* Add dataset explanation
* Write a polished academic abstract for the top of the README
* Write a short summary for LinkedIn

Just tell me what you want.
