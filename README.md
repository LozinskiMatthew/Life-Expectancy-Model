# 🧬 Life-Expectancy-Model

A regression model that predicts an individual’s life expectancy based on demographic, economic, and health-related data.  
This project emphasizes proper preprocessing, careful model design, and strong predictive performance.

---

## Features Used for Prediction

- Country  
- Year  
- Status  
- Life expectancy  
- Adult Mortality  
- Infant deaths  
- Alcohol  
- Percentage expenditure  
- Hepatitis B  
- Measles  
- BMI  
- Under-five deaths  
- Polio  
- Total expenditure  
- Diphtheria  
- HIV/AIDS  
- GDP  
- Population  
- Thinness (1–19 years)  
- Thinness (5–9 years)  
- Income composition of resources  
- Schooling  

---

## Model Overview

- **Framework:** TensorFlow (Keras API)  
- **Type:** Regression Neural Network  
- **Evaluation:** Mean Absolute Error ≈ ±1.2 years  
- **Future Work:** Hyperparameter tuning using Optuna for further optimization

---

## Project Summary

- Dataset was **cleaned, imputed, and normalized** (no data leakage).
- Applied **One-Hot Encoding** and **MinMax scaling** to categorical and numerical features.
- Data was split into **train**, **validation**, and **test** sets.
- The final model is a **regression neural network**, built with TensorFlow/Keras.
- Achieved **±1.2 years average prediction error**, with tight confidence intervals.
- Future improvements may include **hyperparameter optimization using Optuna**.

---

## Getting Started

### Option 1: Google Colab (best option)

You can run the notebook directly in [Google Colab](https://colab.research.google.com/):

1. Upload `LifeExpectancyModel.ipynb`.
2. Upload the dataset `data.csv` into the same Colab runtime directory.
3. Run all cells – everything is pre-configured to work smoothly.

### Option 2: Local Environment

Run the notebook locally using **Conda + Jupyter Notebook**:

1. Install the required libraries (see below).
2. Place both `LifeExpectancyModel.ipynb` and `data.csv` in the **same folder**.
3. Launch Jupyter Notebook and open `LifeExpectancyModel.ipynb`.
4. If you move the CSV file elsewhere, update the dataset path in the appropriate cell.
5. Comment out the pinned lines as directed in the notebook (these are marked with comments).
6. Run the notebook to train and evaluate the model.

---

## Requirements lest you choose local environment

1. You need to install python most preferably 3.10
2. Then via pip install -r requirements.txt you must install the requirements (for your convenience the best choice would be miniconda).

```txt
numpy           == 1.26.4  
pandas          == 2.2.2  
matplotlib      == 3.10.0  
scikit-learn    == 1.6.1  
tensorflow      == 2.18.0  
```

> ⚠️ **Note:** The code was developed and tested specifically on the above versions. Compatibility with other versions is not guaranteed.

---

## ✅ That's It!

You're ready to explore, train, and evaluate the life expectancy prediction model.  
If you encounter issues or want to contribute, feel free to open an issue or fork the repo.