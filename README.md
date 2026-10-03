# Zepto Product Catalog & Pricing Analysis

## 📌 Project Overview

This project performs an exploratory data analysis (EDA) of a Zepto-style e-commerce product catalog dataset using Python.

The objective is to understand product categories, pricing, discounts, customer savings, product availability, quantity, and inventory-related patterns.

The project follows a complete data analysis workflow, from loading and cleaning raw data to exploratory analysis, visualization, and extracting business-oriented insights.

---

## 🎯 Objectives

The main objectives of this project are to:

* Understand the structure and quality of the dataset
* Identify and remove duplicate records
* Check for missing and invalid values
* Validate product pricing calculations
* Analyze product categories
* Examine MRP and discounted selling prices
* Analyze discount percentages
* Calculate customer savings
* Analyze product availability and out-of-stock rates
* Explore product quantity and weight
* Compare category-level pricing and availability
* Create visualizations to communicate findings

---

## 📊 Dataset

The dataset contains product-level information from a Zepto-style e-commerce catalog.

### Main Columns

| Column                   | Description                            |
| ------------------------ | -------------------------------------- |
| `Category`               | Product category                       |
| `name`                   | Product name                           |
| `mrp`                    | Maximum Retail Price                   |
| `discountPercent`        | Discount percentage                    |
| `availableQuantity`      | Recorded available quantity            |
| `discountedSellingPrice` | Selling price after discount           |
| `weightInGms`            | Product weight in grams                |
| `outOfStock`             | Whether the product is out of stock    |
| `quantity`               | Quantity value recorded in the dataset |

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

1. Loaded the CSV dataset using Pandas.
2. Handled the file encoding required by the dataset.
3. Inspected dataset dimensions, columns, and data types.
4. Identified duplicate records.
5. Removed duplicate records.
6. Identified a product with an MRP of zero.
7. Excluded the zero-MRP record from the analysis dataset.
8. Validated discounted selling prices against calculated prices.
9. Investigated pricing differences.
10. Checked for missing values.

---

## 🔎 Exploratory Data Analysis

The project analyzes:

### Product Categories

* Number of unique categories
* Product count by category
* Largest product categories
* Average discount by category
* Average MRP by category
* Average selling price by category

### Pricing

* MRP distribution
* Discount distribution
* Discounted selling prices
* MRP vs selling price
* Highest-priced products
* Highest-discount products
* Customer savings

### Product Availability

* Available products
* Out-of-stock products
* Overall out-of-stock percentage
* Out-of-stock rate by category

### Quantity & Weight

* Quantity distribution
* Highest and lowest quantity values
* Product weight distribution
* Available quantity by category

---

## 📈 Visualizations

The project includes visualizations such as:

* Top product categories
* MRP distribution
* Discount distribution
* Average discount by category
* Product availability
* Quantity distribution
* MRP vs discounted selling price

These visualizations help communicate patterns in the dataset more clearly.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Git
* GitHub

---

## 📁 Project Structure

```text
beginner-friendly-data-analysis/
│
├── data/
│   └── sales_data.csv
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── outputs/
│   └── zepto_analysis_clean.csv
│
├── .gitignore
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/ZOR0-tech/beginner-friendly-data-analysis.git
```

### 2. Navigate to the project

```bash
cd beginner-friendly-data-analysis
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the environment

macOS/Linux:

```bash
source venv/bin/activate
```

### 5. Install the required libraries

```bash
pip install -r requirements.txt
```

### 6. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/ecommerce_analysis.ipynb
```

and run the notebook cells in order.

---

## ⚠️ Dataset Limitation

This is a product-level catalog dataset. The `quantity` field has not been assumed to represent sales volume because the available data does not provide enough business context to confirm that interpretation.

The analysis therefore focuses on catalog, pricing, discount, availability, quantity, and product-level patterns.

---

## 📚 Skills Demonstrated

This project demonstrates practical skills in:

* Data loading
* Data cleaning
* Data validation
* Pandas
* Exploratory Data Analysis
* Data aggregation
* GroupBy analysis
* Statistical analysis
* Data visualization
* Business-oriented interpretation
* Jupyter Notebook documentation
* Git and GitHub workflow

---

## 👤 Author

**Sooraj Krishna**

GitHub: `ZOR0-tech`

---

## 🚀 Future Improvements

Potential future improvements include:

* Interactive dashboards using Power BI or Tableau
* More advanced statistical analysis
* Automated data-quality checks
* Price and discount segmentation
* Machine learning applications using additional datasets
* Integration with a database such as MySQL
