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
* `amazonsalesreport.py` - Main analysis script
* Generated Excel reports:
  * `average_sales_by_category_and_status.xlsx`
  * `total_sales_by_ship_and_fulfil.xlsx`



## Technologies Used
* Pandas for data manipulation
* NumPy for numerical operations
* Excel integration for data import/export
