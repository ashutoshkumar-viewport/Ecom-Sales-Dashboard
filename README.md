# Ecom-Sales-Dashboard
An end-to-end data pipeline using Python (Pandas/Matplotlib) to clean and structure 500k+ lines of e-commerce invoice data, integrated with an interactive Power BI dashboard tracking seasonal sales trends, matrix heatmaps, and product performance metrics.

# E-Commerce Sales Pipeline & Interactive Analytics Dashboard

An end-to-end data analytics pipeline that performs ETL (Extract, Transform, Load) operations on over 500,000 rows of raw retail invoice data using **Python**, and structures it into an interactive **Power BI** business intelligence dashboard to drive operational decisions.

---

## 🛠️ The Technical Stack
* **Data Processing & ETL:** Python, Pandas
* **Data Visualization (Backend):** Matplotlib, Seaborn
* **Business Intelligence & Data Modeling:** Power BI Desktop
* **Development Environment:** VS Code

---

## 📊 Core Business Problems Solved

### 1. Dynamic Metric Snapshotting
* Built high-level KPI cards tracking **Total Revenue (₹8.91M)**, **Total Unique Orders (~18.5k)**, and **Average Order Value (₹22.40)**.
* Integrated a global **Country Dropdown Filter** allowing seamless cross-filtering across distinct regional markets dynamically.

### 2. Time-Series Seasonality Optimization
* Identified critical surge intervals between August and November where monthly revenue spikes by nearly 100%. 
* **Actionable Insight:** Allows supply chain managers to scale inventory procurement 30 days prior to Q3/Q4 surges to eliminate stockouts.

### 3. Value vs. Volume Divergence Matrix
* Created side-by-side behavioral charts comparing revenue assets against transaction frequencies.
* Identifies "cash cows" (high-margin, lower frequency items) against "high-velocity traffic drivers" (low-cost, high-volume shipping units) to guide strategic warehouse product layout positioning and targeted marketing budget allocation.

---

## 📂 Project Structure & Deliverables
* 🐍 [View Python ETL & Analysis Code](Ecom%20Analysis.ipynb) — Opens your clean processing script directly on GitHub.
* 🛠️ [Download Power BI Layout File (.pbix)](E-Commerce%20Report.pbix) — For clients and developers who want to inspect the structural data model layout.
* 💾 [Access Raw Messy Data Source (External Link)](PASTE_YOUR_GOOGLE_DRIVE_EXCEL_LINK_HERE) — Link to the original 45MB transaction log spreadsheet.
