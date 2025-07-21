 
Ahmed Raza Attari
Intern, DevelopersHub Corporation   
# Customer Churn Prediction – Bank Customers  
 Objective
To identify bank customers who are likely to leave (churn), so that the bank can take proactive measures to retain them.

---

Approach

1. Data Cleaning  
   - Removed unnecessary columns like `RowNumber`, `CustomerId`, and `Surname`.

2. Feature Encoding  
   - Gender was label encoded (Male=1, Female=0).  
   - Geography was one-hot encoded.

3. Model Training  
   - Used a Random Forest Classifier for classification.

4. Evaluation
   - Accuracy and classification report used for performance metrics.

5. Feature Importance Analysis  
   - Visualized the impact of each feature on churn.

---

Results & Insights

- **Accuracy Achieved:** ~86%  
- **Important Features:**  
  - Credit Score  
  - Age  
  - Balance  
  - Number of Products  
  - IsActiveMember

Older customers with higher balance and lower product engagement were more likely to churn.

---

 Skills Demonstrated

- Data preprocessing and cleaning  
- Label Encoding & One-Hot Encoding  
- Supervised Machine Learning (Random Forest)  
- Model evaluation and feature importance analysis  
- Matplotlib & Seaborn for visualization

---

 Dataset
Churn_Modelling.csv— standard public dataset for customer churn modeling.

---


Ahmed Raza Attari
Intern, DevelopersHub Corporation  
