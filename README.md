# 🛍️ Festival Sales Analysis (EDA Project using Python)

This project involves a detailed **Exploratory Data Analysis (EDA)** of a retail dataset capturing customer purchases during the Indian festival season. The goal is to uncover key trends in consumer behavior, segment customers based on demographics, and extract actionable insights for marketing and inventory planning.

## 📌 Objective

To analyze sales transactions generated during Indian festivals and understand:

* Who the top-spending customers are (by age, gender, city, etc.)
* What products and categories sell the most
* How customer demographics impact purchasing patterns
* Which business decisions can be guided using these insights

---

## 🛠️ Tools and Technologies Used

| Tool                     | Purpose                                |
| ------------------------ | -------------------------------------- |
| **Python**               | Programming language used for analysis |
| **Jupyter Notebook**     | Development environment                |
| **Pandas**               | Data manipulation                      |
| **NumPy**                | Numerical operations                   |
| **Matplotlib & Seaborn** | Data visualization                     |

---

## 📂 Project Structure

```
festival-sales-eda/
│
├── EDA.ipynb                  # Jupyter Notebook with all analysis
├── Festival Sales Data.csv    # Sales dataset
├── README.md                  # Project documentation (this file)
└── assets/                    # (Optional) Folder for saved plots
```

---

## 📈 Exploratory Data Analysis

### 🧹 Data Cleaning

* Handled missing values in product category fields.
* Removed irrelevant columns (e.g., unnamed index).
* Converted data types and renamed columns for clarity.

### 🔢 Demographic Analysis

* **Gender**: Males outnumber females in transaction count (\~70% male).
* **Age**: The 26–35 age group shows the highest engagement.
* **City**: City Category B dominates in number of transactions.
* **Occupation**: Category 4 and 0 spend the most.
* **Marital Status**: Slight skew towards purchases from married individuals.

### 🛍️ Product-Level Analysis

* **Top Categories**:

  * Product Category 1: Most frequently purchased.
  * Product Categories 2 and 3: Less frequent, more sparse.
* **Top Products**:

  * Identified most frequently occurring Product\_IDs.
  * Potential for bundling popular products during promotions.

### 📉 Purchase Trends

* **Average spend per demographic group**
* **Gender vs Purchase**: Males spend slightly more on average.
* **City vs Spend**: Customers from Category A cities tend to have higher per-transaction spend.

---

## 🔍 Key Insights

| Insight                                            | Recommendation                                           |
| -------------------------------------------------- | -------------------------------------------------------- |
| Majority of purchases made by **Males aged 26–35** | Focus marketing on this segment                          |
| City B has the **highest customer base**           | Allocate more inventory and run location-based campaigns |
| **Product Category 1 dominates sales**             | Prioritize stocking and promotions                       |
| **Married individuals spend more**                 | Explore couple/family-centric offers                     |

---

## 📌 Conclusion

The EDA reveals clear patterns in customer behavior during festivals:

* Certain age groups and city categories drive more sales.
* Product category performance can guide inventory management.
* Marketing teams should align promotions with demographic trends.

These insights can be used by retail managers and marketers to tailor strategies for future festive seasons, driving higher revenue and customer satisfaction.

---

## 👨‍💼 Author

**Name**: *Manvanth G*  
**Contact**: *manvanth1087@gmail.com*  
**Linkedin**: *https://www.linkedin.com/in/manvanth-g-8b2a60244/*
