#  BDA Task 02 – Data Analysis & Visualization

## About the Project

This project is part of my **Big Data Analytics (BDA) – Task 02**.

In this task, the **Sample Superstore dataset** is analyzed using Python. The main focus is on **data preprocessing, exploratory data analysis, and data visualization**.

Different plots are used to understand sales, profit, discount, data distribution, and correlations between numerical variables.

---

## Objectives

* Explore the Sample Superstore dataset
* Perform basic data preprocessing
* Analyze sales and profit
* Compare different product categories
* Study profit distribution and variation
* Analyze the impact of discount on profit
* Find relationships between numerical variables using correlation

---

##  Tools & Technologies

*  Python
*  Pandas
*  NumPy
*  Matplotlib
*  Seaborn
*  Google Colab

---

##  Dataset

The **Sample Superstore dataset** contains information about orders, sales, profit, discounts, categories, and dates.

The dataset is loaded using Pandas and explored using basic functions such as `head()`, `info()`, and `describe()`.

---

##  Data Preprocessing

The following preprocessing steps were performed:

### Date Conversion

`Order Date` and `Ship Date` were converted into datetime format.

### Delivery Days

A new column called **Delivery Days** was created by calculating the difference between the shipping date and order date.

### Missing Values

The dataset was checked for missing values.

### Category Analysis

The unique product categories were identified and sales were grouped by category.

---

#  Visualizations

## 1. Bar Plot

Bar plots were created to compare:

* Sales across categories
* Profit across categories

This helps identify which categories perform better in terms of sales and profit.

---

## 2. Box Plot

Box plots were created to analyze:

* Profit distribution
* Profit variation across categories
* Median values
* Outliers
* Data variation

---

## 3. Discount vs Profit

A scatter plot was used to study the relationship between **Discount** and **Profit**.

This helps analyze whether increasing discounts have an effect on profitability.

**Question analyzed:**

> At what discount level does profit start decreasing?

---

## 4. Correlation Heatmap

A correlation heatmap was created using the numerical columns in the dataset.

It helps understand the relationships between different numerical variables and identify whether variables have positive or negative correlations.

---

## 5. Sales Distribution

A histogram was created to visualize the distribution of **Sales** values in the dataset.

---

#  Analysis Performed

| Analysis                | Visualization       |
| ----------------------- | ------------------- |
| Sales by Category       | Bar Plot            |
| Profit by Category      | Bar Plot            |
| Profit Distribution     | Box Plot            |
| Profit Variation        | Box Plot            |
| Discount vs Profit      | Scatter Plot        |
| Sales Distribution      | Histogram           |
| Numerical Relationships | Correlation Heatmap |

---

##  Key Learnings

From this task, I learned how to:

* Work with datasets using Pandas
* Perform basic data preprocessing
* Convert date columns
* Create calculated columns
* Group and analyze data
* Create different visualization techniques
* Analyze distributions and outliers
* Understand correlation between numerical variables

---

##  Files in this Repository

```text
BDA-Task-02/
│
├── BDA_Task_02.ipynb
├── bda_task_02.py
├── samplesuperstore - samplesuperstore.csv
└── README.md
```

---

##  How to Run

### Google Colab

1. Open `BDA_Task_02.ipynb`
2. Upload the Sample Superstore dataset
3. Run the notebook cells
4. View the generated analysis and visualizations

### Local Environment

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Then run the Python file:

```bash
python bda_task_02.py
```

---
