# 🧑‍💼 Capgemini O-Zone Employee Attrition Analysis

This project explores the key drivers of **employee attrition** at O-ZONE Telecom, a Capgemini client expanding operations in Africa. By combining clustering, PCA, and predictive modeling, the analysis offers actionable insights to improve workforce retention and guide strategic HR planning.

📘 Final report: [`Capgemini_O-Zone Employee Attrition Data Project.pdf`](./Capgemini_O-Zone%20Employee%20Attrition%20Data%20Project.pdf)  
💻 Notebook: [`Capgemini | O-Zone Employee Attrition Data Project`](https://github.com/xuefeiwang001/Capgemini_O-Zone_Employee_Attrition/blob/6e85ee1d4d2102b389d811140750758ec883e6fe/Capgemini%20%7C%20O-Zone%20Employee%20Attrition%20Data%20Project))

---

## 📌 Project Objectives

- Understand employee profiles and attrition behavior
- Identify patterns and segments among employees
- Predict attrition using supervised machine learning
- Deliver strategic recommendations for retention

---

## 🔍 Methodology

1. **Data Preprocessing**  
   - Missing value handling  
   - Categorical encoding  
   - Outlier filtering

2. **Exploratory Data Analysis (EDA)**  
   - Attrition trends by gender, age, salary, department  
   - Correlation heatmaps and boxplots

3. **K-Means Clustering**  
   - Segment employees by behavioral and demographic profiles  
   - Help target retention strategies by group

4. **Principal Component Analysis (PCA)**  
   - Dimensionality reduction  
   - Visual clustering insight

5. **Predictive Modeling**  
   - Random Forest & Decision Tree classifiers  
   - Confusion matrix & accuracy evaluation

6. **Feature Importance Analysis**  
   - Identify top attrition drivers such as salary, years at company, and promotions

---

## 📈 Key Insights

- **Age, income, promotions, and satisfaction levels** strongly influence attrition
- **Employees aged 26–32 with low salary and no promotion in 2 years** are most likely to leave
- 3 employee clusters were identified:
  - Stable & Satisfied
  - At Risk
  - High Performers

---

## 💡 Strategic Recommendations

- Launch **retention campaigns** for Cluster 2 ("At Risk" group)
- Increase **promotion transparency** and **career development visibility**
- Tailor **incentives and salaries** for employees with high attrition risk
- Apply **targeted engagement surveys** per cluster

---

## 🧪 Tech Stack

- Python 3.8+  
- Pandas / NumPy  
- Matplotlib / Seaborn  
- Scikit-learn (KMeans, PCA, RandomForest)  
- Jupyter Notebook

---

## 🚀 How to Run

# Clone the repo
git clone https://github.com/xuefeiwang001/Capgemini_O-Zone_Employee_Attrition.git
cd o-zone-attrition-analysis

# Install necessary libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# Run the notebook
jupyter notebook  <br>
Open Guest lecture Capgemini_Xuefei.ipynb and execute all cells.

---

## 📁 Project Structure
- Guest lecture Capgemini_Xuefei.ipynb
- Capgemini_O-Zone Employee Attrition Data Project.pdf
- README.md

---

## 📄 License
This project is shared under the MIT License.

---

## 👩‍💻 Author
Xuefei Wang <br>
📘 MSc in Data Analytics and AI <br>
🔍 Driven to transform raw data into strategic insights that lead to real impact. <br>
📧 [xuefei.wang001@qq.com]
