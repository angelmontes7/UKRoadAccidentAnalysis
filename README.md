# UK Road Accident Dashboard

### 📊 [View Dashboard](https://noctrl-my.sharepoint.com/:u:/g/personal/amontes_noctrl_edu/EVdOcbzrqYBCpdxvdM7cA-4BHzrBWQ9vxkp27-QRKjrStQ?e=oCwE4C)

## 🚧 Problem Statement

This dashboard provides valuable insights into road accidents in the UK for the years 2021 and 2022. It aims to help key stakeholders—including the Ministry of Transport, road transport departments, emergency services, police forces, and traffic management agencies—better understand accident trends, casualty distributions, and contributing factors. By comparing year-over-year (YoY) metrics, stakeholders can make informed decisions to improve road safety and optimize resource allocation.

The dashboard focuses on tracking total casualties and accidents, analyzing severity levels, evaluating vehicle types involved, and uncovering trends based on time, location, and road type. With real-time visualizations and location-based mapping, this tool serves as a foundation for actionable public safety strategies.

---
![Screenshot 2025-05-17 101021](https://github.com/user-attachments/assets/30afbbcb-a935-4e21-a87b-b62c8c00489b)

## 🧑‍💼 Stakeholders

This dashboard is intended for a wide range of users, including:

- Ministry of Transport  
- Road Transport Department  
- Police Force  
- Emergency Services Department  
- Road Safety Corps  
- Transport Operators  
- Traffic Management Agencies  
- Media and General Public  

---

## 🧠 Key Insights

### [1] Primary KPIs

- **Total Casualties (2022):** 195.7K
- **Total Accidents (2022):** 144.4K
- **YoY Growth in Casualties:** -11.9%
- **YoY Growth in Accidents:** -11.7%

### [2] Casualties by Severity (2022)

- **Slight Injuries:** 165.8K 
- **Serious Injuries:** 27K
- **Fatalities:** 2.9K

### [3] Casualties by Vehicle Type (2022)

- **Cars:** 155,804
- **Motorcycles:** 15,610
- **Agricultural:** 399
- **Other:** 1,446
- **Vans:** 15,905
- **Bus:** 6,573

### [4] Monthly Casualty Trends

A dual-line chart shows monthly casualties for both 2021 and 2022, highlighting peaks during specific months (e.g., winter vs summer trends).

### [5] Casualties by Road Type (2022)

- **Single Carriageway:** 145k
- **Dual Carriageway:** 32k
- **Roundabout:** 13k
- **One way street:** 3k
- **Slip road:** 3k

### [6] Casualties by Location and Time of Day

**Top 5 Regions by Casualty Count:**
- Rural: 38.05%
- Urban: 61.95%

**Day vs Night Accidents:**  
- Day: 73.84%
- Night: 26.16%  

### [7] Mapping Insights

An interactive map pinpoints accident-prone locations with overlays showing both accident volume and casualty severity. This geospatial view allows regional authorities to identify target areas for safety improvements.

---

## 🛠️ Steps Followed

- **Step 1:** Loaded the road accident dataset (2021–2022) into Power BI Desktop from CSV files.
- **Step 2:** Performed data cleaning using Power Query Editor. Enabled Column Distribution, Column Quality, and Column Profile to assess data completeness.
- **Step 3:** Applied full dataset profiling to ensure accuracy across all records.
- **Step 4:** Addressed null values in relevant columns (e.g., severity or location data) and excluded them from aggregate metrics when necessary.
- **Step 5:** Used card visuals to represent Total Casualties and Total Accidents for the current year, alongside YoY Growth KPIs.
- **Step 6:** Created segmented visuals for Casualties by Accident Severity to highlight the distribution of slight, serious, and fatal injuries.
- **Step 7:** Developed visuals comparing Casualties by Vehicle Type for the current year to understand vehicle-specific risks.
- **Step 8:** Added line charts to visualize Monthly Casualty Trends for 2021 and 2022 to observe seasonal or policy-driven impacts.
- **Step 9:** Designed a bar chart to illustrate Casualties by Road Type (e.g., single carriageway, dual carriageway, roundabout) for the current year.
- **Step 10:** Incorporated visuals comparing Day vs Night Casualties and mapped them across UK Areas/Regions to identify high-risk zones.
- **Step 11:** Used map visuals to display Casualties and Accidents by Location, enabling spatial analysis of accident hotspots.
- **Step 12:** Customized dashboard with branded elements for government presentation, including logos, color themes, and informative titles.
- **Step 13:**  
  Created DAX measures to compute metrics such as:  
  - Total Casualties  
  - YoY Growth Rate  
  - Percentage of Severe Accidents  
  - Monthly Comparison Values
- **Step 14:** Published the report to Power BI Service for stakeholder access and collaboration.

---

## 🧾 Conclusion

This UK Road Accident Dashboard provides comprehensive insights into the country's road safety data for 2021 and 2022. With dynamic filtering, year comparisons, and geographic context, it serves as an essential tool for policymakers, traffic authorities, and emergency services to enhance transportation safety and save lives.
