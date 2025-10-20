# 🏥 Medical Insurance Cost Prediction

This project predicts **medical insurance costs** based on factors like age, gender, BMI, smoking habits, region, and number of children.  
It uses **Linear Regression** from Scikit-learn and includes data preprocessing, visualization, and model evaluation.

---

## 📊 Project Overview

The goal of this project is to build a machine learning model that can estimate a person’s medical insurance cost using available demographic and lifestyle data.

The workflow includes:
- Data loading and exploration  
- Data visualization using Seaborn and Matplotlib  
- Data preprocessing (encoding categorical features)  
- Model training using Linear Regression  
- Model evaluation using R² score  
- Prediction for new input data  

---

## 🧰 Tech Stack

- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 📂 Dataset

- **File used:** `insurance.csv`  
  The dataset includes:
  - `age`: Age of the individual  
  - `sex`: Male/Female  
  - `bmi`: Body Mass Index  
  - `children`: Number of children/dependents  
  - `smoker`: Whether the person is a smoker or not  
  - `region`: Region of residence  
  - `charges`: Insurance cost (target variable)

📊 You can get the dataset from [Medical Cost Personal Dataset on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).

---

## 🚀 Features

1. **Data Exploration & Visualization**  
   - Age and gender distribution  
   - Relationship between factors and charges  

2. **Data Preprocessing**  
   - Encoding categorical columns (`sex`, `smoker`, `region`)  

3. **Model Training**  
   - Linear Regression model fitted on training data  

4. **Model Evaluation**  
   - Performance measured using R² score on training and testing data  

5. **Prediction**  
   - Example prediction for a sample input tuple:
     ```python
     input_data = (31, 1, 25.74, 0, 1, 0)
     ```
     → Predicts estimated insurance cost.

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/SNEH-17PATEL/medical-insurance-cost-prediction.git
cd medical-insurance-cost-prediction

## 🪪 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.


