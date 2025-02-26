# Tesla Income Statement Sankey Chart


## Project Overview
This project visualizes Tesla's income statement using a **Sankey diagram**, which effectively demonstrates the flow of financial data from one state to another. The visualization provides insights into how revenue transitions through various expenses to net income.

## Data Source
The financial data was collected from **Yahoo Finance** in a **CSV file**.

## Process Workflow
### 1. Data Collection
- Retrieved Tesla's income statement data from **Yahoo Finance**.
- Saved the data in a structured **CSV format**.

### 2. Data Loading
- Loaded the **CSV file** into a **database** for efficient querying and transformation.

### 3. Data Transformation
- Extracted relevant financial data.
- Structured the data into a **Source, Destination, and Value** format required for the **Sankey diagram**.

### 4. Data Visualization
- Imported the transformed data into **Power BI**.
- Installed and configured the **Sankey Chart** visualization.
- Connected the nodes (financial elements) according to the structured dataset.

## Technologies Used
- **Data Source:** Yahoo Finance
- **Database:** SQL (or another database of choice)
- **Visualization Tool:** Microsoft Power BI
- **Chart Type:** Sankey Diagram

## Key Insights
- The **Total Revenue** splits into **Cost of Revenue** and **Gross Profit**.
- **Gross Profit** is distributed into **Operating Expenses** and **Operating Income**.
- The **final flow** shows how various income and expense components contribute to **Net Income**.


