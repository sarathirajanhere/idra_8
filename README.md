# E-commerce Sales Analysis — Day 8 🛍️

A complete end-to-end data analysis project using **Pandas** on a synthetic e-commerce dataset (100 orders, 13 columns). Covers the full analysis pipeline: loading, inspection, filtering, grouping, aggregation, and business insights.

## Dataset

- **File**: `Day8_Ecommerce_Sales_Dataset.csv`
- **Rows**: 100 orders
- **Columns**: Order_ID, Order_Date, Customer, City, Region, Category, Product, Quantity, Unit_Price, Discount_Percent, Total_Sales, Rating, Payment_Method
- **Categories**: Electronics, Sports, Clothing, Home & Kitchen, Books
- **Regions**: North, South, East, West
- **Payment Methods**: Cash on Delivery, UPI, Debit Card, Credit Card, Net Banking

## Analysis Performed

1. **Data Loading & Inspection** — Shape, dtypes, missing values
2. **Column Selection & Record Filtering** — Specific columns, conditional rows
3. **Sorting** — By Total_Sales (ascending/descending)
4. **GroupBy Aggregations**:
   - Sales by Category, City, Product, Region, Payment Method
   - Total sales, average sales, max/min sales
   - Total quantity sold, order count
5. **Top Performers** — Best-selling products & categories
6. **Business Observations** — Written insights from findings

## Tech Stack

- **Language**: Python 3.x
- **Environment**: Jupyter Notebook / Google Colab
- **Libraries**: `pandas`, `numpy`

## Installation

```bash
git clone https://github.com/sarathirajanhere/idra_8.git
cd idra_8
```

## Usage

### Google Colab (Recommended)
1. Open [colab.research.google.com](https://colab.research.google.com)
2. Upload both files:
   - `Day8_Ecommerce_Sales_Analysis.ipynb`
   - `Day8_Ecommerce_Sales_Dataset.csv`
3. Run all cells

### Local Jupyter
```bash
pip install pandas numpy jupyter
jupyter notebook Day8_Ecommerce_Sales_Analysis.ipynb
```

## File Structure

```
idra_8/
├── Day8_Ecommerce_Sales_Analysis.ipynb      # Analysis notebook
├── Day8_Ecommerce_Sales_Dataset.csv         # Source dataset (100 rows)
└── README.md                                # This file
```

## Key Insights Extracted

- Top-selling category by revenue
- Regional performance comparison
- Payment method preferences
- Discount impact on sales
- Customer rating distributions

## Notebook Structure

The notebook contains comprehensive markdown documentation explaining each step, with executed code cells showing outputs for:
- Data loading and verification
- Exploratory analysis
- Aggregation results in formatted tables
- Business interpretations

---

*Part of the IDRA learning series — progressive data science curriculum (Day 8 of 11).*