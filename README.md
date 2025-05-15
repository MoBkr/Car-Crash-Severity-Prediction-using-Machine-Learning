# 🚗 Car Crash Severity Prediction using Machine Learning

> A complete machine learning project to predict crash severity (Minor Injury, Severe Injury, Fatal) based on crash, vehicle, driver, and environmental factors.

---

## 📌 Overview

Car crashes are a significant public safety issue, often resulting in injuries, fatalities, and financial loss. This project uses a synthetic dataset inspired by real-world scenarios to **predict the severity of a car crash** using machine learning models.

The goal is to demonstrate **end-to-end data science skills** including data analysis, feature engineering, model building, evaluation, and actionable insights. This project can support stakeholders such as:

- **Government agencies** — improving road safety and infrastructure
- **Insurance companies** — assessing accident risks more accurately
- **Automobile manufacturers** — enhancing vehicle safety designs
- **Emergency services** — optimizing response strategies

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| `notebook.ipynb` | Complete Jupyter Notebook with data cleaning, EDA, modeling, and evaluation |
| `car_crash_train.csv` | Dataset used to train the models |
| `Car Crash Severity Prediction Dataset Explanation.pdf` | Full explanation of each feature and business context |
| `README.md` | Project documentation (you’re here!) |

---

## 📊 Dataset Summary

The dataset includes features grouped into:

- **Crash-Specific**: Speed, Impact Angle, Crash Type, Seatbelt Usage, Airbags
- **Vehicle-Specific**: Vehicle Type, Age, Brake/Tire Condition
- **Driver-Specific**: Age, Experience, Alcohol Level, Distraction
- **Environmental**: Weather, Time of Day, Traffic Density, Visibility Distance

**Target variable**: `Severity` — {`Minor Injury`, `Severe Injury`, `Fatal`}

> 🔍 Full details available in the PDF file: `Car Crash Severity Prediction Dataset Explanation.pdf`

---

## ⚙️ Technologies Used

- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **Scikit-learn** (Machine Learning & Evaluation)
- **Jupyter Notebook** (Development environment)

---

## 🧪 Workflow Summary

### 🔹 Step 1: Data Cleaning & Preprocessing
- Handled missing values and inconsistent entries
- Encoded categorical variables
- Normalized numerical features

### 🔹 Step 2: Exploratory Data Analysis (EDA)
- Identified correlations between features and crash severity
- Visualized feature distributions
- Detected class imbalance

### 🔹 Step 3: Modeling & Evaluation
- Trained multiple models (e.g., Random Forest, Logistic Regression)
- Used **accuracy**, **F1-score**, **precision**, and **recall** to evaluate performance
- Analyzed feature importance to interpret the model

---

## 📈 Results

- The **Random Forest model** achieved the best performance in balancing accuracy and generalization.
- Key contributing factors to severe crashes included: **crash speed**, **seatbelt usage**, **alcohol level**, and **time of day**.
- Model insights could help optimize traffic policy and emergency responses.

---

## 🌟 Key Highlights

✅ End-to-end data science pipeline  
✅ Strong focus on real-world relevance and interpretation  
✅ Business-context-aware feature analysis  
✅ Clean, professional code with explanations and visualizations  

---

## 🚀 Future Enhancements

- Implement **SMOTE** to handle class imbalance  
- Explore **XGBoost or LightGBM** for improved performance  
- Deploy as an **interactive app** using **Streamlit** or **Dash**  
- Incorporate **real-time weather or traffic APIs** for live predictions

---



## 🛠️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/car-crash-severity-prediction.git
cd car-crash-severity-prediction

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install required libraries
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebook.ipynb
