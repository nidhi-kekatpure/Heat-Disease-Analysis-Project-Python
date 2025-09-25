# Heart Disease Dataset Analysis

---

## Business Problem
Heart disease is one of the leading causes of death worldwide.  
Healthcare providers, researchers, and policymakers need data-driven insights to better understand **risk factors** and **patterns** of heart disease to improve early detection and prevention.

**Challenge:**
- Work with a **medical dataset** containing patient health attributes  
- Identify patterns between health indicators (age, sex, chest pain, cholesterol, etc.) and heart disease  
- Clean and preprocess the dataset to ensure reliability  
- Perform **Exploratory Data Analysis (EDA)** to extract actionable insights  

---

## My Solution
I solved this problem using **Python and data analysis libraries** to perform an end-to-end EDA pipeline:

1. **Import libraries & dataset**  
   - `pandas`, `matplotlib`, `seaborn`  

2. **Data Cleaning**  
   - Checked dataset size: **1025 rows × 14 columns**  
   - Removed duplicates → Final dataset: **302 rows × 14 columns**  
   - Verified no missing values  

3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics (`describe()`)  
   - Correlation matrix & heatmap  
   - Distribution of target (Heart disease: Yes/No)  
   - Gender distribution overall & by target variable  
   - Age distribution  
   - Chest pain type distribution (and by target variable)  
   - Fasting blood sugar distribution by target  
   - Resting blood pressure distribution & comparison by gender  
   - Serum cholesterol levels  
   - Histograms for continuous variables  

---

