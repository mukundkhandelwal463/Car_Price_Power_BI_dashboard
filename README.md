# 🚗 Multi-Brand Used Car Sales Dashboard (Power BI)

## 📌 Project Overview
This project is an interactive **Power BI dashboard** built to analyze **used car sales data across multiple automobile brands**.  
The dataset consists of **10 CSV files**, each representing a different car brand. These files were cleaned, standardized, and combined into a single analytical model to generate meaningful insights.

The dashboard is designed with a **summary-first approach**, followed by **brand-level analysis** and **cross-brand comparison**, making it suitable for both business users and decision-makers.

---

## 🎯 Project Objectives
- Analyze used car prices, mileage, and fuel efficiency across brands  
- Compare different brands to identify premium and economical options  
- Understand depreciation trends over manufacturing years  
- Study fuel type and transmission preferences in the used-car market  
- Provide an interactive and business-ready analytical dashboard  

---

## 📂 Dataset Description
- Source: Public used-car datasets  
- Format: CSV  
- Number of files: **10 (one per brand)**  
- Common columns:
  - model
  - year
  - price
  - transmission
  - mileage
  - fuelType
  - tax
  - mpg
  - engineSize

Each CSV represents a single brand (e.g., Audi, BMW, Mercedes-Benz, Volkswagen, Vauxhall, etc.).

---

## 🧱 Data Modeling
- All 10 CSV files were **appended into a single Fact table**
- A **Star Schema** was implemented for efficient analysis

### Fact Table
- `FactCars`

### Dimension Tables
- `DimBrand`
- `DimModel`
- `DimFuel`
- `DimTransmission`
- `DimYear`

**Benefits of Star Schema:**
- Improved performance  
- Simplified DAX calculations  
- Clean and effective slicers  

---

## 📊 Dashboard Structure

### 🔹 Page 1: Executive Summary
- High-level overview of the entire dataset  
- KPIs and overall market trends  

**KPIs:**
- Total Cars  
- Average Price  
- Average Mileage  
- Average MPG  

**Visuals:**
- Average Price by Brand  
- Price Trend by Year  
- Fuel Type Distribution  
- Transmission Distribution  

---

### 🔹 Page 2: Brand-Level Analysis
- Detailed analysis of a selected brand  
- Model-wise insights within the brand  

**Visuals:**
- Average Price by Model  
- Average Price by Year  
- Average Mileage by Model  
- Fuel Type Distribution  
- Transmission Type Count  

---

### 🔹 Page 3: All-Brand Comparison
- Side-by-side comparison of all brands  

**Visuals:**
- Average Price by Brand  
- Total Cars by Brand  
- Average Mileage by Brand  
- Average MPG by Brand  
- Brand Performance Matrix  

---

## 📈 Key Measures (DAX)
- Total Cars  
- Average Price  
- Average Mileage  
- Average MPG  
- Min & Max Price  

---

## 🛠️ Tools & Technologies Used
- **Power BI Desktop**
- **Power Query (ETL & Data Cleaning)**
- **DAX (Measures & Calculations)**
- **Star Schema Data Modeling**
- Interactive Slicers & Drill-through
- Dashboard Navigation using Buttons & Images

---

## 🎓 Key Learnings
- Handling and combining multiple real-world datasets  
- Designing a scalable star schema model  
- Creating executive-level and analytical dashboards  
- Applying best practices in Power BI visualization and performance  

---

## 📎 Files in This Repository
- `/data/` → Raw CSV datasets  
- `/dashboard/` → Power BI (.pbix) file *(if included)*  
- `README.md` → Project documentation  

---

## 👤 Author
**Mukund Khandelwal**  
Aspiring Data Analyst | Power BI | Data Visualization  

---

## 🙏 Acknowledgements
Special thanks to **my instructor/mentor** for guidance and support throughout this project.

---

## 📬 Feedback
Suggestions and feedback are always welcome.  
Feel free to connect with me on LinkedIn!
https://www.linkedin.com/posts/mukund-khandelwal-6a8663283_powerbi-dataanalytics-businessintelligence-activity-7407361794379280384-cuyj?utm_source=share&utm_medium=member_desktop&rcm=ACoAAET5diABs7bbZlDnVTGZ4DnPgeKxnEmHsgA
