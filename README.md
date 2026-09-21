# 📊 Oasis Infobyte – Data Analyst Internship (Level 1 Tasks)

A collection of four data analytics tasks completed during my **Data Analyst Internship at Oasis Infobyte**, covering exploratory data analysis, customer segmentation, data cleaning, and sentiment analysis using Python in Jupyter Notebooks.

---

## 📑 Table of Contents
- [Repository Structure](#-repository-structure)
- [Tools & Technologies](#️-tools--technologies)
- [Task 1: Retail Sales EDA](#-task-1-retail-sales--exploratory-data-analysis-eda)
- [Task 2: Customer Segmentation](#-task-2-customer-segmentation)
- [Task 3: Data Cleaning](#-task-3-data-cleaning-titanic-dataset)
- [Task 4: Sentiment Analysis](#-task-4-sentiment-analysis-on-product-reviews)
- [Overall Learnings](#-overall-learnings)
- [How to Run](#️-how-to-run)

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
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn *(add NLTK / TextBlob / VADER if used)*
- **Environment:** Jupyter Notebook / Google Colab
- **Data formats:** Excel (.xls / .xlsx)

---

## ✅ Task 1: Retail Sales – Exploratory Data Analysis (EDA)

**🎯 Objective:** Understand sales patterns in retail data and identify the factors that drive revenue.

**📂 Dataset:** `task-1 retail_sales.xls`

### 🔧 What I Did
- Loaded the dataset with Pandas and inspected its shape, columns, data types, and summary statistics
- Checked for missing values and duplicate records, and cleaned them
- Converted the date column to datetime and created time-based features (month, day, year)
- Grouped and aggregated sales by category, product, and time period
- Created visualisations (bar charts, line charts, histograms, heatmaps) to explore trends

### 🔍 What I Analysed
- Which product categories generate the most revenue and units sold
- How sales change over time (monthly / seasonal trends)
- How customer attributes (age, gender, region) relate to spending
- Correlations between numerical variables such as quantity, price, and total sales

### 📈 Outcomes
- 🏆 Top-performing category: **[fill]**, contributing **[fill]%** of total sales
- 📅 Sales peaked in **[fill: month / season]** and dipped in **[fill]**
- 🛒 Average transaction value: **[fill]**
- 👥 Highest-spending customer group: **[fill]**
- 💡 **Recommendation:** [fill: e.g., increase stock before peak months, promote low-performing categories]

---

## ✅ Task 2: Customer Segmentation

**🎯 Objective:** Group customers by purchasing behaviour so a business can target each group effectively.

**📂 Dataset:** `online_retail.xlsx`

### 🔧 What I Did
- Loaded the transaction data and removed rows with missing customer IDs, cancelled orders, and negative quantities
- Calculated a total price per transaction (Quantity × Unit Price)
- Built customer-level features: **Recency, Frequency, and Monetary value (RFM)**
- Scaled the features and applied a clustering algorithm (e.g., K-Means)
- Chose the number of clusters (e.g., using the elbow method) and labelled each segment

### 🔍 What I Analysed
- How recently each customer purchased (Recency)
- How often each customer buys (Frequency)
- How much each customer spends (Monetary)
- The average behaviour of each segment and its share of total revenue

### 📈 Outcomes
- 🔢 Customers were grouped into **[fill]** segments
- 🌟 **High-value customers:** **[fill]%** of customers generate **[fill]%** of revenue
- 🔁 **Loyal customers:** [fill: short description]
- ⚠️ **At-risk / inactive customers:** [fill: short description]
- 💡 **Recommendation:** [fill: e.g., reward the top segment, run win-back campaigns for inactive customers]

---

## ✅ Task 3: Data Cleaning (Titanic Dataset)

**🎯 Objective:** Turn raw, messy data into a clean, analysis-ready dataset.

**📂 Output:** `task-3 titanic_cleaned.xls`

### 🔧 What I Did
- Inspected the dataset for missing values, wrong data types, and duplicates
- Handled missing values in **[fill: Age, Cabin, Embarked]** using **[fill: mean / median / mode / dropping]**
- Removed duplicate records and standardised inconsistent formats
- Corrected data types and, where needed, dropped columns that added little value
- Detected and treated outliers
- Exported the final cleaned dataset

### 🔍 What I Analysed
- The number and percentage of missing values in each column
- The distribution of key columns before and after cleaning
- Survival patterns by gender, passenger class, and age group

### 📈 Outcomes
- 🧹 Shape before cleaning: **[fill]** → after cleaning: **[fill]**
- ❓ Column with the most missing values: **[fill]** (**[fill]%**), handled by **[fill]**
- 🚢 Overall survival rate: **[fill]%**, higher among **[fill: females / first class / children]**
- 💡 **Takeaway:** Data cleaning decisions directly affect the reliability of any analysis built on top

---

## ✅ Task 4: Sentiment Analysis on Product Reviews

**🎯 Objective:** Understand how customers feel about products by classifying reviews as positive, negative, or neutral.

**📂 Dataset:** `task-4 product_reviews.xls`

### 🔧 What I Did
- Loaded the reviews and cleaned the text (lowercasing, removing punctuation, numbers, and stop words)
- Applied a sentiment analysis method (**[fill: TextBlob / VADER / other]**) to score each review
- Classified each review as Positive, Negative, or Neutral
- Visualised the sentiment distribution and generated word frequency views (e.g., word clouds)

### 🔍 What I Analysed
- The overall split of positive, negative, and neutral reviews
- The most frequent words and themes in positive vs. negative reviews
- How sentiment relates to ratings or products (if available in the data)

### 📈 Outcomes
- 😊 Positive: **[fill]%** | 😐 Neutral: **[fill]%** | 😞 Negative: **[fill]%**
- 🔑 Common words in positive reviews: **[fill]**
- 🔻 Common complaints in negative reviews: **[fill]**
- 💡 **Recommendation:** [fill: e.g., address the most-cited product issues to improve customer satisfaction]

---

## 📌 Overall Learnings

- Practised the complete data workflow: **load → clean → explore → analyse → interpret**
- Applied **EDA**, **clustering**, **data cleaning**, and **NLP** techniques on real-world datasets
- Learned to convert raw data into **actionable business insights**
- Strengthened skills in **Pandas, data visualisation, and data storytelling**

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
