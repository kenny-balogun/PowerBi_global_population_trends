# A World in Transition: Glimpse into Growth  

## Overview  

Population growth, urbanization, and health metrics play a crucial role in shaping economies and societies.  
This project presents an **interactive Power BI dashboard** that visualizes **global population trends, urbanization rates, and health indicators** across different **regions and income groups** from **1960 to 2050**.  

The dashboard provides **data-driven insights** to help policymakers, NGOs, and researchers understand and forecast demographic shifts for better decision-making.  

## Objectives  

- **Analyze global population growth** trends over time.  
- **Explore urbanization patterns** across different regions and income groups.  
- **Examine key health metrics**, including birth rates, death rates, and life expectancy.  
- **Provide interactive visualizations** for intuitive exploration and analysis.  

## Dataset  

This project uses two datasets:  

1. **Population Figures and Projections Dataset**  
   - Covers global population data from **1960 to 2050**.  
   - Contains **19,748 observations** across **12 columns**.  
   
2. **Country Groupings Dataset**  
   - Provides **218 observations** with income classifications and regional groupings.  

| Dataset | Description |
|---------|------------|
| **Population Figures & Projections** | Yearly population data, birth/death rates, urbanization levels. |
| **Country Groupings** | Classification of countries by region and income level. |

## Data Preparation  

The datasets underwent **data cleaning and transformation** using **Power Query** to ensure accuracy and usability:  

- **Data Formatting:** Ensured consistent data types.  
- **Handling Missing Values:** Removed blank rows and avoided imputation to prevent bias.  
- **Column Renaming:** Used meaningful names for better interpretability.  
- **Removing Duplicates:** Eliminated redundant data for cleaner relationships.  
- **Establishing Relationships:** Linked datasets using country codes to enable dynamic filtering.  

## Key Features of the Dashboard  

### **1. Dynamic Title**  
The title **automatically updates** based on selected filters to provide contextual insights.  

### **2. Slicer Panel**  
Users can **filter data** by:  
- **Year** (1960–2050)  
- **Year Category** (Historical vs. Projected)  
- **Region**  
- **Country**  
- **Income Group**  

### **3. Key Performance Indicators (KPIs)**  
The top section of the dashboard provides **high-level summary metrics** for quick insights:  
- **Total Population Growth**  
- **Average Annual Population Growth Rate**  
- **Average Life Expectancy**  
- **Average Birth Rate & Death Rate**  

KPIs are **color-coded** to indicate comparison with global averages.  

### **4. Population Growth by Income Group (Waterfall Chart)**  
- Shows **how each income group contributes** to global population growth.  
- Highlights differences between **high-income and low-income countries**.  

**Example Insight:**  
Low-income countries contribute significantly to population growth, while high-income countries show stagnation or decline.  

### **5. Urbanization Trends by Region (Bar Chart)**  
- Compares the **average urban population percentage** across different regions.  
- Uses **shading intensity** to indicate the urbanization growth rate.  

### **6. Population Growth vs. Urbanization (Dual Y-Axis Line Chart)**  
- Tracks **population growth rates** alongside **urbanization rates** over time.  
- Helps analyze the correlation between **economic development and urbanization**.  

### **7. Annual Population Growth Breakdown (Stacked Bar Chart)**  
- Shows **population growth across income groups per region**.  
- Provides detailed insights into **which regions drive global population increases**.  

## Critical Evaluation  

### **Strengths**  
✅ **Interactive Design:** Filters allow users to explore data from multiple perspectives.  
✅ **Data-Driven Insights:** Provides **historical trends and future projections**.  
✅ **User-Friendly Layout:** Visuals are arranged to guide users from **high-level summaries to in-depth analysis**.  
✅ **Conditional Formatting:** Highlights deviations from **global averages** for quick comparison.  

### **Limitations**  
⚠ **Dual Y-Axis Chart Complexity:** Some users may misinterpret the relationship between population growth and urbanization.  
⚠ **Space Utilization:** The slicer panel takes up dashboard space and could be optimized with a collapsible design.  

## Business & Policy Implications  

This dashboard provides **valuable insights** for governments, NGOs, and businesses by:  

- **Urban Planning:** Identifying high-growth regions to improve infrastructure and housing.  
- **Healthcare Resource Allocation:** Understanding health trends to **allocate medical services efficiently**.  
- **Investment Decisions:** Businesses can use these trends to **identify market opportunities**.  

## Future Enhancements  

- **Integrate Real-Time Data Feeds** for continuous updates.  
- **Expand to Additional Metrics** such as GDP growth and migration patterns.  
- **Develop Predictive Models** to forecast urbanization and economic growth.  

## Installation & Usage  

To explore the dashboard:  

1. Download the **Power BI file** from this repository.  
2. Open it using **Microsoft Power BI Desktop**.  
3. Use the interactive filters to explore insights.  


