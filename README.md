# Tesla Income Statement Sankey Chart


## Project Overview
This project visualizes Tesla's income statement using a **Sankey diagram**, which effectively demonstrates the flow of financial data from one state to another. The visualization provides insights into how revenue transitions through various expenses to net income.

## Understanding Sankey Diagrams

A Sankey diagram is a type of flow diagram used to visualize the distribution of resources or quantities through a system. Key characteristics of Sankey diagrams include:

-   **Nodes:** Represent different states or categories (e.g., Revenue, Cost of Revenue, Gross Profit).
-   **Links/Flows:** Connect the nodes and their width is proportional to the quantity of the flow (e.g., the amount of revenue flowing from "Total Revenue" to "Cost of Revenue").
-   **Conservation of Flow:** The total inflow into a node equals the total outflow from that node, ensuring that the quantity is conserved throughout the diagram.

### Mechanism of a Sankey Diagram

1.  **Data Input:** The diagram requires data in a structured format, typically a table with three columns:
    *   **Source:** The starting point of the flow.
    *   **Destination:** The ending point of the flow.
    *   **Value:** The magnitude of the flow from the source to the destination.

2.  **Node and Link Creation:**
    *   The unique values from the Source and Destination columns are identified and created as nodes in the diagram.
    *   Links are created between these nodes, with the width of each link determined by the corresponding Value.

3.  **Layout and Arrangement:**
    *   Nodes are arranged to minimize overlap and make the flow direction clear (typically from left to right).
    *   The height or vertical position of nodes and links is adjusted to prevent intersections and improve readability.

4.  **Rendering:**
    *   The diagram is rendered using a graphics library or visualization tool that supports drawing nodes and links.
    *   Labels and tooltips are added to provide additional information about each node and link.

### How it Visually Works

*   **Flow Representation**: The width of the arrows (or links) in a Sankey diagram is proportional to the quantity being transferred. Wider arrows indicate larger flows, making it easy to identify the most significant transitions.
*   **Color Coding**: Different colors can be used to represent different categories or types of flows, enhancing clarity and making it easier to follow specific paths through the diagram.
*   **Interactive Elements**: Many implementations of Sankey diagrams include interactive features such as tooltips, which display detailed information when hovering over a node or link, and the ability to highlight or filter specific flows.


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


