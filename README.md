# Power BI Dashboard - Ryanair Product Performance Overview

This Power BI dashboard provides an overview of product performance metrics for Ryanair. It includes key indicators such as revenue, transactions, and a breakdown of revenue contribution by product category and country. The design uses Ryanair’s branding with its signature blue and yellow color scheme, making the dashboard visually aligned with the company's identity.

## Sections of the Dashboard

### Header and Branding
- The **Ryanair logo** is prominently displayed in the top-right corner to reinforce brand identity.
- The title, **"Product Performance Overview"**, highlights the main purpose of the dashboard: analyzing revenue, transactions, and product performance.

### Key Metrics
- **Revenue Metric (1.28M)**: Displays the total revenue in euros for the selected date range.
- **Transactions (3000)**: Shows the total number of transactions.
  
**Date Filters:**
- **Transaction Date Range**: A slicer for filtering data based on when transactions occurred.
- **Departure Date Range**: A slicer for filtering data based on the departure date.
  
**Dropdown Filter (name):** 
- Enables filtering by additional categories, such as product or customer.

### Product Contribution by Category Table
- This matrix provides a breakdown of revenue by product categories such as "Car Rental," "In-Flight Meals," and "Hotel Booking."
- Each product is analyzed across several dimensions:
  - Percentage contribution in different revenue streams (After Flight, In-Flight, Services, etc.).
  - Total revenue for each product category.
  
The table emphasizes Ryanair's major revenue contributors, allowing for detailed product performance analysis.

### Transactions by Date (Line Chart)
- A bar chart on the left visualizes the volume of transactions over time, highlighting fluctuations in customer activity.

### Top 5 Countries by Revenue (Stacked Bar Chart)
- A bar chart shows the top 5 countries generating revenue, with China, Indonesia, and the Philippines leading.

### Revenue by Country (Map Visualization)
- The map displays revenue distribution across various countries using bubble sizes. Larger bubbles represent higher revenue, making it easy to identify key markets.

#### Interactive Features for the Map:
- **Tooltips**: When hovering over any country on the map, a tooltip will display additional information about the revenue generated from that country.
- **Drill-Down Capability**: You can drill into the map to explore detailed user information from a specific country, such as:
  - Revenue
  - Email
  - Transaction Date

This allows you to see more granular data about transactions from that specific region, providing in-depth insights into country-specific performance.
