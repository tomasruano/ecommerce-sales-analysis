# 📊 E-commerce Sales Analysis

End-to-end **data analysis project** focused on analyzing e-commerce sales, customers, products and geographic performance using Python and Pandas.

The project uses transaction data from **2018** and combines order-level information with product-level sales details to generate business KPIs, visualizations and actionable insights.

## 🎯 Business Questions

The analysis explores:

* How much revenue was generated?
* Which categories and products generate the most revenue?
* How do sales change throughout the year?
* Which cities generate the most revenue?
* Which customers contribute the most revenue?
* How many orders and customers are represented in the dataset?

## 📁 Dataset

The analysis uses two related datasets:

### `Orders.csv`

Contains **500 orders** with information about:

* Order ID
* Order date
* Customer
* State
* City

### `Details.csv`

Contains **1,500 sales-detail records** with information about:

* Order ID
* Amount
* Profit
* Quantity
* Category
* Sub-category
* Payment method

The datasets were merged using **Order ID** to create the final analytical DataFrame.

## 🧹 Data Preparation

The project includes:

* Dataset inspection using `info()` and `describe()`
* Column and data-type inspection
* Null-value validation
* Merging of the two datasets using `Order ID`
* Conversion of `Order Date` to datetime
* Extraction of year, month and month name
* Creation of a `Revenue` analytical variable
* Aggregation using Pandas `groupby()`

The final analytical dataset contains **1,500 records and 15 columns**.

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

## 📈 Business KPIs

| KPI                 |  Result |
| ------------------- | ------: |
| Total Revenue       | 437,771 |
| Total Orders        |     500 |
| Total Customers     |     336 |
| Average Order Value |  875.54 |

## 📊 Analysis Performed

### Revenue by Category

Revenue by category:

| Category    | Revenue |
| ----------- | ------: |
| Electronics | 166,267 |
| Clothing    | 144,323 |
| Furniture   | 127,181 |

**Electronics** generated the highest revenue among the three categories.

### Revenue Over Time

Monthly revenue was analyzed throughout 2018:

| Month     | Revenue |
| --------- | ------: |
| January   |  61,632 |
| February  |  38,962 |
| March     |  60,694 |
| April     |  34,330 |
| May       |  29,093 |
| June      |  23,658 |
| July      |  12,966 |
| August    |  31,492 |
| September |  27,283 |
| October   |  31,613 |
| November  |  48,469 |
| December  |  37,579 |

The analysis allows periods of higher and lower sales activity to be identified throughout the year.

### Top Cities by Revenue

The highest-revenue cities in the dataset were:

| City    | Revenue |
| ------- | ------: |
| Indore  |  63,680 |
| Mumbai  |  58,886 |
| Pune    |  43,612 |
| Mathura |  28,747 |
| Bhopal  |  23,783 |

### Top Products by Revenue

The highest-revenue sub-categories were:

| Sub-Category     | Revenue |
| ---------------- | ------: |
| Printers         |  59,252 |
| Saree            |  59,094 |
| Bookcases        |  56,861 |
| Phones           |  46,119 |
| Electronic Games |  39,168 |

### Customer Analysis

Customer revenue was aggregated to identify the customers with the highest contribution to total revenue.

The project also visualizes the **top 10 customers by revenue**.

## 📉 Visualizations

The notebook includes visualizations for:

* Revenue by category
* Monthly revenue
* Revenue over time
* Top states by revenue
* Top cities by revenue
* Top products by revenue
* Top customers by revenue

These visualizations are used to identify patterns and communicate the main findings.

## 💡 Key Findings

The analysis shows that:

1. **Electronics is the highest-revenue category**, generating 166,267 in revenue.
2. **Revenue varies substantially throughout 2018**, with January and March among the strongest months and July showing the lowest monthly revenue.
3. **Revenue is geographically concentrated**, with Indore, Mumbai and Pune generating the highest revenue among the analyzed cities.
4. **Revenue is concentrated among specific sub-categories**, with Printers, Saree and Bookcases being the top three.
5. **Customer revenue is unevenly distributed**, allowing high-value customers to be identified through customer-level aggregation.

## 🧠 Skills Demonstrated

This project demonstrates practical experience with:

* Data loading and inspection
* Data cleaning and validation
* Pandas DataFrames
* Dataset merging
* Datetime transformation
* Feature engineering
* `groupby()` aggregations
* KPI calculation
* Exploratory Data Analysis (EDA)
* Data visualization
* Business-oriented analysis
* Translating data into business insights

## 📂 Project Structure

```text
ecommerce-sales-analysis/
├── notebook.ipynb
├── Orders.csv
├── Details.csv
└── README.md
```

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/tomasruano/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis
```

Install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `notebook.ipynb` and run the cells.

## 👨‍💻 Author

**Tomás Ruano**

Data Science & Artificial Intelligence student at UADE.
