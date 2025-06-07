# Interactive-Personal-Finance-Dashboard-using-Excel
In this guide, we will walk through the process of building a personal finance dashboard in Excel from scratch. This dashboard will allow you to manage your finances effectively and update your data with just a click of a button. Even if personal finance reporting isn't your primary interest, the Excel techniques covered here can be applied to any data set.

## Overview of the Dashboard
The dashboard will consist of various components, including:

A transaction sheet for bank data
Headline figures for quick insights
Charts for visual representation of expenses and income
Interactive elements like slicers for filtering data
### Downloading the Excel Template
Before we begin, you can download the Excel file from the link provided in the video description. If you find the pace too fast, you can adjust the playback speed in the video settings.

## Step 1: Setting Up the Dashboard
The first step is to create a new sheet for the dashboard. Adjust the row heights as needed to prepare for the layout. This sheet will serve as the main interface for your dashboard.

### Transaction Data
Next, we need to set up a transaction sheet where you will input your bank transaction data. You can import this data from your bank statement, typically available in Excel, CSV, or text file formats. The essential columns to include are:

Account
Transaction Date
Description
Debit Amount
Credit Amount
To calculate the net amount, create a formula that subtracts debits from credits, resulting in negative values for expenses and positive values for income. This will be crucial for creating visualizations like waterfall charts.

### Categorizing Transactions
To better analyze your spending, categorize each transaction using a data validation list. This list can be customized to fit your needs, allowing you to add or remove categories as necessary. Use lookup formulas (like XLOOKUP or VLOOKUP) to automatically populate category fields based on the subcategory selected.

## Step 2: Analyzing Data with Pivot Tables
Once your data is organized, it's time to analyze it using pivot tables. Pivot tables allow for quick summarization and can automatically update when new data is added.

### Creating Pivot Tables
Insert a Pivot Table: Create a new pivot table for headline figures, focusing on expenses. Filter out any income sources like salary.
Format the Pivot Table: Set the number format to currency with no decimal places for clarity.
Create Additional Pivot Tables: For different analyses, such as total spending by account or expenses over time, create separate pivot tables on a dedicated analysis sheet.
## Step 3: Building the Dashboard Visuals
With your pivot tables ready, you can now create various charts to visualize your financial data.

### Adding Charts
Waterfall Chart: This chart will illustrate how your income translates into expenses over time. Create a pivot table for the waterfall data and insert a waterfall chart.
Donut Chart: Use a pivot table to show total spending by account in a donut chart format.
Line Chart: Display expenses by category over time using a line chart.
Tree Map: For hierarchical data visualization, create a tree map to show expenses by category and subcategory.
### Formatting Charts
Ensure all charts have a consistent color palette and style. Use shapes to create rounded corners for a polished look. Add data labels and legends where necessary to enhance readability.

## Step 4: Making the Dashboard Interactive
To make your dashboard user-friendly, add slicers that allow users to filter data by category and date.

### Inserting Slicers
Select a Pivot Table: Choose any pivot table to insert slicers.
Insert Slicers: Add slicers for both category and date. Format them for better visibility.
Connect Slicers to Pivot Tables: Ensure that the slicers are connected to all relevant pivot tables so that selecting a category or date updates the dashboard accordingly.
## Step 5: Dynamic Labels and Final Touches
To enhance the interactivity of your dashboard, create dynamic labels that change based on slicer selections. This will provide context to the data displayed in your charts.

### Creating Dynamic Labels
Use Formulas: Create formulas that reference the selected items in your slicers to generate dynamic titles for your charts.
Text Boxes: Since chart titles cannot be directly linked to cells, use text boxes to display these dynamic titles.
## Step 6: Updating the Dashboard
To update your dashboard with new data:

### Add New Data: Paste new transaction data at the bottom of your existing data table.
### Refresh Pivot Tables: Click the refresh button to update all pivot tables and charts with the new data.
## Conclusion
By following these steps, you can create a comprehensive and interactive personal finance dashboard in Excel. This dashboard not only helps in tracking your finances but also enhances your Excel skills with various techniques and tools.
