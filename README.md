# BasicSalesSummary
📊 Sales Data Summary with SQLite and Python
This project demonstrates how to use Python, SQLite, Pandas, and Matplotlib to perform basic sales data analysis. It connects to a small SQLite database (sales_data.db), runs SQL queries to summarize the data, and visualizes the results with a simple bar chart.

🗂️ Project Structure

.
├── sales_data.db         # SQLite database with sample sales records
├── analyze_sales.py      # Python script for analysis and visualization
├── sales_chart.png       # Generated bar chart (after running the script)
└── README.md             # Project documentation


✅ Features
Connects to a local SQLite database

Executes SQL queries to summarize sales

Displays results using print() and matplotlib

Saves a revenue bar chart as an image


🛠️ Tools & Libraries Used
Python 3.x

SQLite (via sqlite3)

Pandas

Matplotlib



📦 Requirements
Install dependencies with:


pip install pandas matplotlib


🚀 How to Run
Make sure sales_data.db is in your project directory.

Run the analysis script:
python analyze_sales.py


Output:

Terminal will display a summary of sales.

A bar chart (sales_chart.png) will be saved and shown.



📈 Sample Output

   product  total_qty  revenue
0   Apples         15     37.5
1  Bananas         25     37.5
2  Oranges         15     45.0


A chart visualizing the revenue by product is also generated.
