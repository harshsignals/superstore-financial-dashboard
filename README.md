# 📊 Superstore Financial & Operational Dashboard

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-F2C811?style=for-the-badge&logo=powerquery&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=dax&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-000000?style=for-the-badge&logo=visualbasic&logoColor=white)

## Executive Summary
This interactive reporting suite was developed to provide executive leadership with a holistic view of company performance. By bridging the gap between raw operational data and high-level financial strategy, this tool tracks revenue generation, profit efficiency, and supply chain logistics, enabling data-driven decision-making across all levels of the organization.

<img width="800" height="359" alt="ezgif-1f05ccdd01fbfda5" src="https://github.com/user-attachments/assets/ab1062dc-7493-4bfe-b70e-f3162a927bc9" />
<!-- ![Dashboard Demo](Dashboard_Demo.gif) -->

---

## 🛠️ The Engine Room (Tech Stack)

This project moves beyond standard spreadsheet design, utilizing advanced data engineering techniques to build a standalone, interactive application.

*   **Architecture:** Built on a Relational **Star Schema** Data Model integrating thousands of rows across Sales, Customer, Product, and Returns databases.
*   **Calculations:** Powered by a custom **DAX** (Data Analysis Expressions) measure library, utilizing advanced Time Intelligence functions (e.g., `SAMEPERIODLASTYEAR`) for dynamic Year-over-Year variance reporting.
*   **Automation:** Data shaping and automated table formatting handled via **VBA macros** to ensure data integrity before entering the model.
*   **Visualization:** Designed with a focus on color psychology, spatial consistency, and UI/UX best practices to eliminate visual clutter and highlight actionable insights.

---

## 📸 Application Previews

### 1. Sales Overview
Tracks top-line revenue, monthly targets, and geographic performance with dynamic Year-over-Year KPIs.

<img width="1855" height="817" alt="sales dashboard" src="https://github.com/user-attachments/assets/5dfd265e-9338-4124-ba76-b82a8a77745c" />


### 2. Profit Efficiency
Analyzes margin compression, discount impacts, and identifies bottom-performing sub-categories draining profitability.

<img width="1856" height="814" alt="profit dashboard" src="https://github.com/user-attachments/assets/9b166fe5-c840-44e6-82c2-c97fdf6b4eb9" />


### 3. Supply Chain & Orders
Monitors total volume, average order value, and isolates high-frequency return rates to optimize supply chain logistics.

<img width="1857" height="817" alt="orders dashboard" src="https://github.com/user-attachments/assets/1cd09291-7c15-4165-beef-4b26f85dd74a" />


### 4. Project Documentation (About Page)
A built-in navigation and documentation tab outlining the architecture and usage guide for end-users.

<img width="1877" height="842" alt="about tab" src="https://github.com/user-attachments/assets/2f55fafd-49e3-4167-b21d-415cd495fc5a" />


---

## ⚙️ Under The Hood

To ensure peak performance and scalability, the raw dataset was modeled using Power Pivot rather than standard Excel tables. 

**Relational Star Schema Data Model:**
Fact and Dimension tables are connected via one-to-many relationships, eliminating data redundancy and enabling seamless cross-filtering across all dashboard tabs.

<img width="512" height="409" alt="model" src="https://github.com/user-attachments/assets/e36db06d-f339-4d9d-9be7-a2650f848d06" />


**Custom DAX Measure Library:**
Over 20 explicitly defined DAX measures calculate core KPIs, Year-over-Year growth, and handle blank-value logical formatting.

<img width="512" height="355" alt="measures" src="https://github.com/user-attachments/assets/d3e8e5b9-882c-4e9e-9c65-eee18dc671bf" />


---

## 📥 How to Run This Project Locally

This dashboard utilizes a **Dynamic Power Query Pathing** system. It will automatically detect its own file location, meaning the data connections will not break when downloaded to a new computer.

1. Click the green **"<> Code"** button at the top of this repository.
2. Select **"Download ZIP"**.
3. Extract the ZIP file to your local computer. *(Critical: The dashboard `.xlsm` file and the `datasets` folder must remain in the exact same directory).*
4. Open the Excel file and click **Enable Macros** at the top prompt.
5. Go to the Data tab and click **Refresh All** to trigger the dynamic query engine.
6. Navigate using the side-panel buttons and slicers!

---

**Developer:** Harshvardhan Singh Shekhawat  
**Contact:** hsshekhawat2006@gmail.com  
