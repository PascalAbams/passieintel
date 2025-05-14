# Python for Data Analysis

This is my repo for all my python work

## Projects

### Project 1: Analyzing Amazon Sales Data

This project analyzes a large Amazon sales dataset (128,975 records) to extract meaningful business insights through data cleaning, exploration, and aggregation.

#### Tasks Completed:
* **Data Cleaning**
  * Handled missing values (particularly in Amount, currency fields)
  * Verified data types for analysis
  * Created cleaned subsets for different analysis purposes
* **Data Exploration**
  * Examined basic statistics and distributions
  * Identified key dataset characteristics
  * Analyzed sales patterns across categories
* **Data Aggregation & Analysis**
  * Answered key business questions:
    * Identified 13,332 sales with amounts exceeding ₹1,000
    * Found 3 sales in the "Top" category with a quantity of 3
    * Calculated total sales by product category - highest in "Set" category (₹39,204,124)
    * Analyzed average sales amount by category and status
    * Summarized total sales by fulfillment and shipment type

#### Key Insights:
* "Set" category generates the highest revenue (₹39,204,124), followed by "Blouse" (₹21,757,954)
* Amazon-fulfilled orders generally have higher average order values than Merchant-fulfilled ones
* Products in the "Dress" category with "Shipped - Damaged" status have the highest average amount
* Most sales volume comes from "Shipped" items fulfilled by Amazon (₹50,331,934)

#### Files:
* `Amazon Project.ipynb` - Main analysis script
* Generated Excel reports:
  * `average_sales_by_category_and_status.xlsx`
  * `total_sales_by_ship_and_fulfil.xlsx`

## Technologies Used
* Pandas for data manipulation
* NumPy for numerical operations
* Excel integration for data import/export

### Project 2: Analyzing Olist Ecommerce Orders Data

This project explores customer payment behavior using Olist’s ecommerce datasets from Brazil, focusing on how customers pay and whether credit card usage is disproportionately high.

#### Tasks Completed
* **Data Cleaning**
  * Merged orders.xlsx, order_payment.xlsx, and customers.xlsx
  * Handled missing values and dropped duplicates
  * Filtered data by payment type and state for targeted insights

* **Data Exploration & Aggregration**
  * Created time-based features (year, month, week) for trend analysis
  * Analyzed total monthly payment values
  * Grouped and aggregated data by payment type and time

 * **Data Visualization**
   * Line chart showing total payment value by month
   * Stacked bar chart showing payment method breakdown over time
   * Scatter plot showing relationship between payment value and number of installments
   * Box plot comparing payment value ranges across methods
   
#### Key Insights
 * Credit cards are the most dominant payment method across months.
 * Users paying with credit cards tend to have higher transaction values and more installments.
 * A few customers spread payments over 60+ installments, indicating possible credit overuse.
 * Payment value peaked around late 2017, followed by a dip in mid-2018.

#### Files
 * `Olist Analytics.ipynb` – Main notebook for data cleaning, merging, and visualization
 * my_plot.png – Final multi-plot image showing all four key charts
 * `orders.xlsx`,  `order_payment.xlsx`, `customers.xlsx` – Raw datasets used

#### Technologies Used
 * Pandas for data manipulation
 * Seaborn/Matplotlib for visualization
 * Jupyter Notebook for interactive analysis





