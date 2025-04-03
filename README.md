 ☕ Coffee Sales Dashboard
 
Welcome to the Coffee Sales Data Analytics Dashboard, a project built in Microsoft Excel to visualize and analyze customer orders for a coffee business. This dashboard leverages relational data spread across multiple sheets to provide actionable insights into sales trends, customer behavior, and product performance.

This project showcases how Excel tools such as Pivot Tables, VLOOKUP, Charts, Slicers, and Dashboard linking can be used to create an interactive and insightful analytical report, even from basic tabular data.

 📊 Project Overview

The dataset consists of three interrelated tables:

- `Orders Table`: Contains Customer ID, Coffee ID, Order Date, and Quantity Ordered.
- `Customer Table`: Includes customer details like Name, Region, Loyalty Card Status, etc.
- `Product Table`: Holds information about coffee such as Type, Roast Type, Size, and Price.

🔄 Data Preparation

1. Used VLOOKUP in the main Orders table to fetch:
   - Customer details from the `Customer Table` using `Customer ID`.
   - Product details from the `Product Table` using `Coffee ID`.
   
   > 🔧 This enriches the Orders table into a master data table ready for analysis.

 📈 Dashboard Visuals & Analysis Steps

1. 📅 Sales Over Time (Line Chart)
- Created a Pivot Table using `Date` and calculated `Sales`.
- Inserted a Line Chart to visualize sales trends over time.
- Added Slicers for dynamic filtering based on:
  - Roast Type
  - Loyalty Card
  - Size
  - 
 2. 📍 Sales by Region (Bar Chart)
- Built a Pivot Table with `Region` as rows and `Sales` as values.
- Plotted a Bar Chart to compare performance across different regions.

 3. 🧑‍💼 Top 5 Customers by Sales
- Created a Pivot Table with `Customer Name` and `Sales`.
- Sorted and filtered to show the Top 5 Customers.
- Visualized using a Bar Chart.

🔗 Interactive Slicers
- All charts and tables are connected using Slicers, enabling dynamic filtering across all visuals.
- A checkbox toggle allows the user to choose whether slicers apply to a single table or all visuals in the dashboard.

🧪 Features Demonstrated

- ✅ Relational joins via VLOOKUP
- ✅ Multiple Pivot Tables
- ✅ Interactive Slicers
- ✅ Dynamic Top N Filtering
- ✅ Fully formatted and styled dashboard
- ✅ Centralized filtering control across visuals
  
 📷 Dashboard Screenshots
   ![image](https://github.com/user-attachments/assets/f48cfb62-a0b8-4d06-b8ba-0de758899aa4)


 🚀 How to Use

1. Open the Excel file.
2. Use the slicers to filter insights by roast type, loyalty card, size, or region.
3. Watch the charts and tables update instantly based on your selection.

🛠️ Tools Used

- Microsoft Excel  
- Pivot Tables  
- VLOOKUP  
- Charts (Line, Bar)  
- Slicers  

