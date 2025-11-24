## Sales Summary

This analyzes product sales data stored in an SQLite database and generates insights using Python and Jupyter Notebook. The goal was to calculate total revenue per product, export the results, and visualize data using a bar chart.

## 📁 Project Files
File Name	Description
sales_summary.ipynb	Main Jupyter Notebook with code, SQL query, and analysis
sales_data.db	SQLite database containing raw sales data
sales_summary.csv	Final exported summary of product revenue
sales_chart.png (optional)	Bar chart generated from the analysis

## Tools & Technologies

Python (Pandas, SQLite3, Matplotlib)

SQLite Database

Jupyter Notebook

Git & GitHub

## 📝 Steps Performed

Loaded the sales data from an SQLite database.

Queried the database to calculate:

Total quantity sold per product

Total revenue generated per product

Converted the results into a Pandas DataFrame.

Exported the summary to a CSV file.

Created a bar chart visualization showing revenue by product.

Saved the chart as an image.

## 📈 Output Example
Product	Total Quantity	Revenue
Widget B	7	136.50
Widget A	13	129.87
Widget C	17	85.00

## 🏷️ Learning Outcomes

✔ Understanding SQL queries inside Python
✔ Working with SQLite databases
✔ Data analysis using Pandas
✔ Data export to CSV
✔ Data visualization using Matplotlib
✔ Version control and pushing project to GitHub

## How to Run This Project

Clone the repository:

    git clone <repo-link>


Open the project folder and launch Jupyter Notebook:

jupyter notebook


    Run all cells in sales_summary.ipynb.
