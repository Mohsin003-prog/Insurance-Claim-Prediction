# Insurance-Claim-Prediction
# Predicting Insurance Claim Amounts

## 📌 Objective

Estimate **medical insurance charges** using **Linear Regression** based on personal data such as age, BMI, sex, smoking status, etc.

---

## 🗂️ Dataset

**Source:** [Medical Cost Personal Dataset (Kaggle)](https://www.kaggle.com/datasets/mirichoi0218/insurance)

**File:** `insurance.csv`

**Features:**

- `age`: Age of the primary beneficiary
- `sex`: Gender of the beneficiary
- `bmi`: Body Mass Index
- `children`: Number of children covered by health insurance
- `smoker`: Whether the person smokes or not
- `region`: Residential area in the US
- `charges`: Medical insurance cost (target variable)

---

## 🔧 Tasks

1. **Train** a Linear Regression model to predict `charges`.
2. **Visualize** the effect of `age`, `bmi`, and `smoker` on `charges`.
3. **Evaluate** the model using:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)

---

## 🛠️ Tools Used

- Python
- Pandas
- Seaborn & Matplotlib
- Scikit-learn

---

## 📊 Visualizations

- Scatter plot: `Charges vs Age`
- Scatter plot: `Charges vs BMI`
- Boxplot: `Charges by Smoking Status`
- Correlation heatmap of all features

---

## 📈 Model Evaluation

After training a Linear Regression model, we evaluated the performance using:

- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)

---

## 🚀 How to Run

1. Download the dataset from Kaggle.
2. Place `insurance.csv` in your project directory.
3. Run the Jupyter/Colab notebook or Python script.

```bash
pip install pandas seaborn matplotlib scikit-learn
