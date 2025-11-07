# 🛒 E-Commerce Data Analytics using Python, SQL, and Power BI  

### 📘 Overview  
This project demonstrates a **complete end-to-end data analytics workflow** for an e-commerce business.  
It involves **data cleaning, analysis, SQL querying, and dashboard creation**, just like a real-world analyst would do.  
The goal is to uncover **customer behavior patterns, top-performing products, and sales trends** to support business decisions.  

---

### 🧾 Dataset Description  
The dataset contains realistic, uncleaned data with missing values and outliers to simulate real-world conditions.  

| Feature | Description |
|----------|-------------|
| Customer_ID | Unique ID for each customer |
| Name | Customer name |
| Email | Customer’s email address |
| Phone | Customer’s contact number |
| Gender | Gender of customer |
| DOB | Date of birth |
| Signup_Date | Account creation date |
| Last_Purchase_Date | Last order date |
| Product_ID | Unique product identifier |
| Product_Name | Product name |
| Category | Product category |
| Quantity | Number of items purchased |
| Price | Price per item |
| Payment_Mode | Mode of payment (Credit, Debit, UPI, etc.) |
| City | Customer city |
| State | Customer state |
| Returned | Indicates whether the product was returned |

---

### ⚙️ Tech Stack  
- **Python** → Pandas, NumPy, Matplotlib, Seaborn  
- **SQL** → PostgreSQL for structured queries  
- **Power BI** → For creating interactive dashboards  
- **Excel** → For quick checks and validation  

---

### 🧹 Data Analytics Process  

#### 1️⃣ Data Understanding  
- Loaded dataset using Pandas  
- Explored structure using `head()`, `tail()`, `info()`, `describe()`, `shape`, etc.  
- Checked missing values and duplicates  

#### 2️⃣ Data Cleaning & Preprocessing  
- Handled missing and null values  
- Fixed data types for date and numeric columns  
- Removed duplicates and treated outliers  
- Standardized text formats  
- Created new derived columns such as **Total_Spend** and **Customer_Age**  

#### 3️⃣ Exploratory Data Analysis (EDA)  
- Univariate and bivariate analysis  
- Customer demographic analysis  
- Purchase frequency, payment preference, and return ratio  
- City- and category-wise sales performance  

#### 4️⃣ SQL Analysis  
Created and queried tables in PostgreSQL to answer business questions:  
- Total revenue by city/state  
- Most frequent customers  
- Category-wise revenue  
- Average order value per customer  
- Number of returns per category  

#### 5️⃣ Power BI Dashboard  
Developed an interactive dashboard to visualize:  
- Total Sales & Revenue Overview  
- Top Products & Customers  
- Sales by City and State  
- Return Analysis and Trends  
- Payment Mode Distribution  

---

### 📊 Key Insights  
- Majority of purchases are made by **female customers** aged 25–35.  
- **Top 3 cities** generate more than **50% of total sales**.  
- **Debit cards** are the most common payment mode.  
- A small number of products account for the majority of revenue (Pareto 80/20 rule).  
- Returns are higher in a specific **category**, suggesting potential product-quality issues.  

---

### 🧠 Learning Outcomes  
✅ Performed complete end-to-end data analysis workflow  
✅ Gained hands-on experience with data cleaning, EDA, and SQL  
✅ Learned to visualize business KPIs in Power BI  
✅ Understood how to derive actionable insights from raw, messy data  

---

### 🗂️ Project Structure  
