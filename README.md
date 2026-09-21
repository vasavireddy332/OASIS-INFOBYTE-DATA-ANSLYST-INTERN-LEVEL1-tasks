
# 📊 Oasis Infobyte – Data Analyst Internship (Level 1 Tasks)

A collection of four data analytics tasks completed during my **Data Analyst Internship at Oasis Infobyte**. The tasks cover exploratory data analysis, customer segmentation, data cleaning, and sentiment analysis, using Python in Jupyter Notebooks.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `Task_1_Retail_Sales_EDA (1).ipynb` | Exploratory Data Analysis on retail sales data |
| `Task_2_Customer_Segmentation.ipynb` | Customer segmentation on online retail transactions |
| `Task_3_Data_Cleaning.ipynb` | Cleaning and preparing the Titanic dataset |
| `Task_4_Sentiment_Analysis (1).ipynb` | Sentiment analysis on product reviews |
| `task-1 retail_sales.xls` | Dataset for Task 1 |
| `online_retail.xlsx` | Dataset for Task 2 |
| `task-3 titanic_cleaned.xls` | Cleaned output dataset for Task 3 |
| `task-4 product_reviews.xls` | Dataset for Task 4 |

---

## 🛠️ Tools & Technologies

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn *(add NLTK / TextBlob / VADER if used in Task 4)*
- **Environment:** Jupyter Notebook / Google Colab
- **Data formats:** Excel (.xls / .xlsx)

---

## ✅ Task 1: Retail Sales – Exploratory Data Analysis (EDA)

**Objective:** Understand sales patterns in retail data and find the factors that drive revenue.

**Dataset:** `task-1 retail_sales.xls`

**Approach:**
1. Loaded the dataset and inspected its structure, data types, and summary statistics
2. Checked for missing values and duplicates
3. Analysed sales by category, product, and time period
4. Visualised distributions and trends using charts
5. Examined relationships between key variables

**Key Insights:**
- 📈 Top-performing product category: **[fill]**, contributing **[fill]%** of total sales
- 📅 Sales peak in **[fill: month / season]** and dip in **[fill]**
- 🛒 Average transaction value: **[fill]**
- 👥 Customer group with the highest spending: **[fill: age group / gender / region]**
- 💡 Recommendation: **[fill: e.g., stock up before the peak period, promote low-performing categories]**

---

## ✅ Task 2: Customer Segmentation

**Objective:** Group customers by purchasing behaviour so businesses can target them better.

**Dataset:** `online_retail.xlsx`

**Approach:**
1. Cleaned the data (removed missing customer IDs, cancelled orders, and negative quantities)
2. Created customer-level features such as **Recency, Frequency, Monetary (RFM)**
3. Scaled the features
4. Applied a clustering method (e.g., K-Means) and chose the number of clusters
5. Profiled and interpreted each segment

**Key Insights:**
- 🔢 Customers were grouped into **[fill]** segments
- 🌟 **High-value segment:** **[fill]%** of customers generate **[fill]%** of revenue
- 🔁 **Loyal / frequent buyers:** **[fill: short description]**
- ⚠️ **At-risk / inactive customers:** **[fill: short description]**
- 💡 Recommendation: **[fill: e.g., reward the top segment, run win-back offers for inactive customers]**

---

## ✅ Task 3: Data Cleaning (Titanic Dataset)

**Objective:** Turn raw, messy data into a clean, analysis-ready dataset.

**Output:** `task-3 titanic_cleaned.xls`

**Approach:**
1. Inspected missing values, data types, and duplicates
2. Handled missing values in columns such as **[fill: Age, Cabin, Embarked]** (imputation or removal)
3. Removed duplicate records
4. Corrected data types and standardised formats
5. Checked for outliers and treated them where needed
6. Exported the cleaned dataset

**Key Insights:**
- 🧹 Original shape: **[fill]** → Cleaned shape: **[fill]**
- ❓ Column with the most missing values: **[fill]** (**[fill]%**), handled by **[fill: method]**
- 🚢 Survival rate: **[fill]%** overall; higher among **[fill: females / first-class / children]**
- 💡 Takeaway: Clean data leads to more reliable analysis, and the way missing values are handled directly affects the results

---

## ✅ Task 4: Sentiment Analysis on Product Reviews

**Objective:** Find out whether customer reviews are positive, negative, or neutral.

**Dataset:** `task-4 product_reviews.xls`

**Approach:**
1. Loaded and cleaned the review text (lowercasing, removing punctuation, stop words, etc.)
2. Applied a sentiment analysis method to score each review
3. Classified reviews as Positive, Negative, or Neutral
4. Visualised the sentiment distribution
5. Explored common words in positive vs. negative reviews

**Key Insights:**
- 😊 Positive: **[fill]%** | 😐 Neutral: **[fill]%** | 😞 Negative: **[fill]%**
- 🔑 Most common words in positive reviews: **[fill]**
- 🔻 Most common complaints in negative reviews: **[fill]**
- 💡 Recommendation: **[fill: e.g., fix the most-cited product issues to improve ratings]**

---

## 📌 Overall Learnings

- Practised the full data workflow: **load → clean → explore → analyse → interpret**
- Applied **EDA**, **clustering**, **data cleaning**, and **NLP** techniques on real datasets
- Learned to turn raw data into **actionable business insights**
- Strengthened skills in **Pandas, data visualisation, and storytelling with data**

---

## ▶️ How to Run

1. Clone the repository:
   `git clone https://github.com/vasavireddy332/OASIS-INFOBYTE-DATA-ANSLYST-INTERN-LEVEL1-tasks.git`
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn scikit-learn openpyxl xlrd`
3. Open any notebook in Jupyter Notebook or Google Colab
4. Keep the dataset files in the same folder as the notebooks and run all cells

---

## 👩‍💻 Author

**Vasavi Kadari**
🔗 [LinkedIn](https://linkedin.com/in/vasavi-kadari) | 💻 [GitHub](https://github.com/vasavireddy332)

⭐ If you found this useful, feel free to star the repository!
