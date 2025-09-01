# 🔊 Sonar Rock vs Mine Prediction  

This project implements a **machine learning model** to classify sonar signals as either **rock** or **mine** using the **UCI Sonar dataset**. Such classification has practical applications in **naval defense systems** and **autonomous underwater vehicles**, where distinguishing natural objects from potential threats is crucial.  

---

## 📌 Project Overview  

- **Goal**: Predict whether an object detected by sonar is a **rock** or a **mine**.  
- **Dataset**: UCI Sonar Dataset (208 samples, 60 features).  
- **Model**: Logistic Regression (with scikit-learn).  
- **Output**:  
  - Rock (R)  
  - Mine (M)  

---

## 🛠️ Tech Stack  

- **Language**: Python 3  
- **Libraries**:  
  - `numpy`, `pandas` → Data handling  
  - `scikit-learn` → Machine learning (Logistic Regression, train-test split, accuracy score)  

---

## ⚙️ Workflow  

1. **Data Loading** → Load the UCI sonar dataset into a pandas DataFrame.  
2. **Data Preprocessing** → Split features and labels, prepare training & testing sets.  
3. **Model Training** → Train Logistic Regression classifier on sonar data.  
4. **Model Evaluation** → Evaluate accuracy on training and testing sets.  
5. **Prediction** → Input custom sonar values to predict Rock or Mine.  

---

## 🚀 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/sonar-rock-vs-mine.git
   cd sonar-rock-vs-mine

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows

4. Install dependencies:
    ```bash
   pip install -r requirements.txt

6. Open the notebook:
    ```bash
   jupyter notebook Sonar_Rock_vs_Mine_Prediction.ipynb

8. Run all cells to train and test the model.

---

## 📊 Results

The model achieves around 80–85% accuracy (depending on train/test split).

Can correctly identify mine-like signals most of the time.


