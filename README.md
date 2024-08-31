# AdventureWorks BI Dashboard Project

### **Objective:**
Develop an interactive Business Intelligence dashboard for AdventureWorks, a global manufacturing company specializing in cycling equipment and accessories, to provide insights into key performance indicators (KPIs), regional performance, product-level trends, and high-value customer identification.

---

### **Project Overview**

**Tools and Technologies:**
- **Data Source:** 12 raw CSV files (transactions, returns, products, customers, sales territories)
- **Platform:** Power BI Desktop
- **Data Transformation and Preparation:** Power Query Editor
- **Data Modeling:** Star schema and snowflake schema design
- **DAX (Data Analysis Expressions):** 40+ calculated columns and measures
- **Visualization:** Interactive dashboards with dynamic visuals and AI visuals (Q&A, Decomposition Tree, Key Influencers)

**Project Steps:**

1. **Imported and Transformed Data:**
   - **Imported** 12 different CSV files into Power BI using Power Query Editor.
   - **Executed** data cleaning steps: **removed duplicates**, **handled errors**, managed missing values (NaNs), **verified column data types**, and **promoted headers**.

2. **Built Data Model:**
   - **Created** relationships between dimension (lookup) tables and fact tables using primary and foreign keys.
   - **Designed** a star schema with supporting snowflake schema to enhance data efficiency and dashboard interactivity.

3. **Developed DAX Calculations:**
   - **Created** over **40 DAX measures and calculated columns** to enable dynamic insights, such as total revenue, total profit, order count, return rate, and more.

4. **Designed Dashboards:**

   - **Dashboard 1: KPI Overview**
     - **Displayed** key metrics with KPI Cards: **Total Revenue, Total Profit, Total Orders, Return Rate** to provide an instant overview of business performance.
     - **Visualized** Monthly Revenue Trend using a **Line Chart** to help the management team identify sales patterns and seasonality, enabling better inventory and marketing decisions.
     - **Added** detailed insights with cards for **Monthly Revenue, Monthly Orders, Monthly Returns** to monitor monthly performance.
     - **Highlighted** top performers in a **Table** showing **Top 10 Products** (Orders, Revenue, Return %) to prioritize best-selling products and manage inventory effectively.
     - **Included** cards for **Most Ordered** and **Most Returned Product Type**, Orders by Category to assist in understanding product demand and return rates.
     - **Integrated** interactive elements: Filters, Back, and Bookmark Buttons to enhance user experience and allow quick navigation.

   - **Dashboard 2: Geographic Performance**
     - **Mapped** total orders by region using **Bubble Size Variations** to visualize geographic performance, allowing the sales team to identify high-performing regions and areas needing attention.
     - **Created** geographic filter cards: **Select All, Europe, North America, Pacific** to quickly compare regional data and adjust marketing strategies accordingly.

   - **Dashboard 3: Product Detail**
     - **Showcased** detailed product insights: **Monthly Orders vs. Target, Monthly Revenue vs. Target, Monthly Profit vs. Target** using **Gauge Charts** to track performance against targets, assisting in goal alignment and product strategy.
     - **Implemented** slicers for Profit Adjustments and Product Selection to dynamically adjust and analyze data based on different scenarios.
     - **Displayed** total and adjusted profit through **Line Graphs** to help in evaluating the profitability of products and identifying opportunities for pricing adjustments.

   - **Dashboard 4: Customer Detail**
     - **Visualized** customer data with **Donut Charts** showing **Unique Customers, Revenue per Customer, Orders by Income Level** to segment customers by value and target high-value customers effectively.
     - **Identified** top customers with cards: **Top Customers by Orders and Revenue** to prioritize engagement strategies.
     - **Provided** customer details in a **Table**: **Customer Key, Full Name, Orders, Revenue** to give a comprehensive overview of customer behavior, aiding in personalized marketing campaigns.

   - **Dashboard 5: Custom Category Tooltip**
     - **Leveraged** AI Visuals: Q&A, Decomposition Tree, Key Influencers, and Narrative Summary to allow users to explore data interactively and identify key drivers behind metrics like sales and returns, leading to more informed decision-making.

---

### **Key Features and Insights:**

- **Enhanced Dashboard Interactivity:** **Filters, bookmarks, and dynamic visual elements** allow users to explore data effortlessly.
- **Comprehensive KPI Monitoring:** Real-time tracking of key metrics such as **Sales, Revenue, Profit, and Returns** enables quick decision-making.
- **Geographic Analysis:** In-depth regional performance visualization with **interactive maps** helps identify growth opportunities and areas needing attention.
- **Product and Customer Insights:** Detailed analysis to drive product optimization and customer segmentation strategies.
- **AI-powered Insights:** Advanced AI visuals provide deeper exploration and identification of key data trends, enhancing strategic planning.

### **Conclusion:**

This project showcases the powerful capabilities of Power BI to transform raw data into actionable insights. The comprehensive dashboards empower AdventureWorks to make data-driven decisions, optimize sales strategies, and enhance customer engagement.

