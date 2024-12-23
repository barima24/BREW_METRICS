# BREW_METRICS

Coffee store sales Analysis

Transaction records for Maven Roasters, a coffee shop operating out of three NYC locations. Dataset is of 6 months with more than 1 lakh data includes the transaction date, timestamp and location, along with product-level details.

In this project, I used **Excel** for **initial data preprocessing and transformation**. The raw dataset included **only the unit price** for various products across three locations. I calculated the **sales** by multiplying the unit price with the quantity sold and then used **a nested XLOOKUP function** to determine the **profit percentage** per product category and location for 2024. This allowed me to calculate the **profit** for each transaction.

To ensure the data was ready for analysis, I applied date transformations in Power BI and used DAX queries to convert the transaction time, which included hours, minutes, and seconds, into a clean hour format for better time-based analysis.

The dashboard I created includes several key graphs, including:

**Category Performance**
**Profit Breakdown by Category**
**Trending Products**
**Peak Hours**
**Busiest Days**
**Sales Trend Over the Month**
For KPIs, I integrated metrics like **revenue, sales gains, orders sold, and quantity tracker**. These visualizations are **controlled through a location slicer**, allowing for easy filtering of data by store location.

Additionally, I incorporated a **15-day sales forecast** in a separate page, with a **view forecast button** on the main dashboard that **links users to the forecasted data**. The dashboard also includes a graph displaying profit by location to visualize performance across different store locations.

**This interactive and dynamic dashboard offers insights into various key metrics, enabling better decision-making for store management and strategy optimization.**
