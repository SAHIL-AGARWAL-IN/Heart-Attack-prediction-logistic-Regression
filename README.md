# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the presence of **heart disease** in patients using machine learning techniques. The model is trained on a structured medical dataset containing various health indicators such as age, cholesterol level, blood pressure, and heart rate.

The goal of this project is to demonstrate the **end-to-end machine learning workflow**, including data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## 📂 Project Structure

```
📁 Heart-Disease-Prediction
│── 📄 Untitled.ipynb        # Jupyter Notebook containing full implementation
│── 📄 1-heart.csv           # Dataset used for training and testing
│── 📄 README.md             # Project documentation
```

---

## 📊 Dataset Information

**File:** `1-heart.csv`

The dataset contains medical attributes commonly used to diagnose heart disease.

### 🔑 Common Features (may vary slightly depending on dataset version):

* `age` – Age of the patient
* `sex` – Gender (1 = male, 0 = female)
* `cp` – Chest pain type
* `trestbps` – Resting blood pressure
* `chol` – Serum cholesterol (mg/dl)
* `fbs` – Fasting blood sugar
* `restecg` – Resting ECG results
* `thalach` – Maximum heart rate achieved
* `exang` – Exercise-induced angina
* `oldpeak` – ST depression induced by exercise
* `slope` – Slope of the peak exercise ST segment
* `ca` – Number of major vessels colored by fluoroscopy
* `thal` – Thalassemia
* `target` – **Target variable** (1 = heart disease present, 0 = not present)

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **Pandas**
* **Matplotlib / Seaborn**
* **Scikit-learn**

---

## ⚙️ Workflow

1. **Data Loading** – Import dataset using Pandas
2. **Exploratory Data Analysis (EDA)** – Understand distributions and relationships
3. **Data Preprocessing**

   * Handling missing values
   * Feature scaling
   * Encoding categorical variables
4. **Model Training**

   * Train-test split
   * Apply machine learning algorithm(s)
5. **Model Evaluation**

   * Accuracy score
   * Confusion matrix
   * Classification report

---

## 🚀 How to Run the Project

1. Clone this repository or download the files
2. Open a terminal in the project directory
3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Open `Untitled.ipynb`
5. Run all cells sequentially

---

## 📈 Results

The model predicts whether a patient is likely to have heart disease based on clinical features. Performance metrics such as **accuracy** and **confusion matrix** are used to evaluate the model.

---

## 📌 Future Improvements

* Try advanced models (Random Forest, XGBoost, SVM)
* Hyperparameter tuning
* Cross-validation
* Deploy as a web app using Flask or Streamlit


---

⭐ If you like this project, consider giving it a star on GitHub!
