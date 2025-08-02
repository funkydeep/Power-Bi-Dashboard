# Power-Bi-Dashboard
Superstore Sales Power BI Dashboard

 Why I Built This
I've always enjoyed making sense of messy real-world data, so I wanted to practice with a small “Superstore” retail dataset. My specific goal was to build an interactive Power BI dashboard for quick sales insights—something an actual manager would use.

 What This Dashboard Shows
- Total Sales, # of Orders, Average Order Value, and Profit
- Sales trends by month
- Sales breakdown by category (Furniture, Tech, etc.)
- Region-wise sales on a map

 How I Did It
1. Loaded `power_bi_superstore_sales_sample.csv` into Power BI.
2. Cleaned up the data and fixed date formats—ran into some issues with date parsing but sorted it by double-checking column types.
3. Calculated new measures—Average Order Value, Year-on-Year growth using DAX.
4. Built visuals: Line chart (monthly sales), bar chart (sales by category), map (regional breakdown).
5. Added simple filters—users can slice by year or category in real time.

 What Was Hard
Getting DAX to work for YoY metrics took a few attempts—errors mostly due to column references. Also, designing a simple but useful layout that didn’t look like a template took some fiddling.

What I’d Like to Improve
With more time, I’d add:
- Drill-through to see data by customer or product
- Dynamic tooltips
- Q&A (natural language) for managers



