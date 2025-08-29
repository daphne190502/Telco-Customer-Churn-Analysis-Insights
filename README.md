# Telco Customer Churn Analysis & Insights 

An **end-to-end data analytics and machine learning project** that predicts customer churn, analyzes churn drivers, and provides **actionable retention strategies** using **Python**, **Machine Learning**, and **Power BI**.

---

##  Project Overview  
Customer churn directly impacts a company's revenue and growth.  
This project focuses on:
- Predicting customers likely to churn.
- Identifying key factors influencing churn.
- Building an **interactive Power BI dashboard** for insights.
- Providing **data-driven retention recommendations**.

---

## 🛠 Tech Stack
- **Programming Language** → Python 
- **Libraries** → Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning Models** → Logistic Regression, Random Forest, XGBoost  
- **Visualization Tool** → Power BI  
- **Dataset** → [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)


---

##  Project Workflow

### **1. Data Preprocessing**
- Handled missing values (`TotalCharges`).
- Converted categorical features to numerical using One-Hot Encoding.
- Ensured `customerID` uniqueness.
- Scaled continuous features like `MonthlyCharges` and `TotalCharges`.

### **2. Exploratory Data Analysis (EDA)**
- Churn distribution analysis.
- Impact of **contract type**, **tenure**, **monthly charges**, and **payment method**.
- Visualized churn patterns using **Matplotlib** and **Seaborn**.

### **3. Machine Learning Modeling**
- Trained multiple models:
    - Logistic Regression
    - Random Forest  *(best-performing)*
    - XGBoost
- **Best Model → Random Forest**:
    - Accuracy: **80%**
    - Precision: **65%**
    - Recall: **55%**
    - F1-Score: **60%**

### **4. Churn Risk Segmentation**
- Predicted churn probabilities.
- Classified customers into:
    - **High Risk** → Probability ≥ 70%
    - **Medium Risk** → 40% ≤ Probability < 70%
    - **Low Risk** → Probability < 40%

### **5. Power BI Dashboard**
Built an **interactive dashboard** with:
- **KPIs** → Total Customers, Churn Rate, High-Risk Customers.
- **Churn Risk Segmentation**.
- **Churn by Contract Type**.
- **Monthly Charges vs Churn Probability**.
- **Top Churn Drivers**.
- **Retention Recommendations**.

---

##  Key Insights
- **Month-to-Month** customers are **3x more likely** to churn.
- High **Monthly Charges** → higher churn probability.
- Customers **without Tech Support** churn more.
- **Electronic Check** payments correlate with higher churn.

---

##  Results & Impact
- Achieved **80% prediction accuracy**.
- Built a **business-friendly dashboard** for strategic decision-making.
- Enables management to **target high-risk customers** and **reduce churn**.

---

##  Live Dashboard *(Optional)*
🔗 [View Interactive Power BI Dashboard](#)  
*(Add link here once published)*

---

##  How to Use This Project
```bash
# Clone the repository
git clone https://github.com/yourusername/telco-customer-churn.git

# Navigate to the folder
cd telco-customer-churn

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook telco_churn_analysis.ipynb
