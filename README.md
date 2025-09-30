# Employee-Growth-Business-Impact-Analytics-A-Data-Driven-Approach-to-Workforce-Performance-Management 

## Introduction  
In modern organizations, employee growth and workforce stability are critical to achieving consistent business outcomes and long-term sustainability. Employers face the dual challenge of engaging employees while minimizing turnover and optimizing workforce costs.  

The **Employee Growth & Business Impact Analytics solution** is a comprehensive Power BI dashboard designed to track and analyze headcount, turnover, satisfaction, performance, and store-level business outcomes. It enables decision-makers at all levels—HR managers, business leaders, and store managers—to identify high-risk employee groups, evaluate performance effectiveness, and optimize workforce strategies to support both employee wellbeing and organizational goals.  

By integrating diverse datasets into a centralized **star schema data model** and leveraging advanced **DAX measures**, this solution offers an interactive view of workforce KPIs such as headcount, turnover rate, satisfaction, promotion %, salary increase %, sales performance, and store customer satisfaction.  

---

## Data Model  
At the heart of the model lies a consolidated fact table—**Monthly Performance**—capturing employee evaluations, engagement, satisfaction, and productivity. This is enriched by multiple dimension tables:  

- **DimEmployees** – demographics, job roles, education, department  
- **DimStores** – store location, type, age  
- **DimRoleKPIs** – role-based KPIs and productivity  
- **DimBusinessOutcomes** – sales, NPS, CSAT, waste %  
- **Calendar** – time intelligence and reporting periods  

The model uses surrogate keys, calculated columns (e.g., Age Group, Career Growth Category), and advanced DAX measures for KPIs.  
<img width="1527" height="776" alt="EmpModelling" src="https://github.com/user-attachments/assets/a858ba46-38c6-4f33-ba7a-ec9c7fce5a27" />

---

## Dashboard Pages  

### 📊 Page 1 – Workforce Demographics & Growth  
- KPIs: **Headcount (7,500), Active Employees (6,009), Average Salary ($27.25K), Turnover Rate (19.88%), Annual Workforce Cost ($204.40M)**  
- Visuals:  
  - Headcount by Gender & Status (Active/Inactive)  
  - Headcount by Job Level & Job Role  
  - Education Level vs Active/Inactive  
  - Headcount trend by Month  
<img width="1286" height="730" alt="Emp1" src="https://github.com/user-attachments/assets/c370fba9-c54b-4687-8127-a5502276fa18" />

### 📈 Page 2 – Engagement, Growth & Career Insights  
- KPIs: **Avg Employee Satisfaction (7.24), Engagement Index (7.22), Avg Manager Evaluation (3.70), % Promoted (4.19%), % Salary Increase (35.03%)**  
- Visuals:  
  - Employee Satisfaction & Performance Categories  
  - Career Growth Category  
  - Manager Evaluation & Engagement Index Categories  
  - Overall Performance Distribution  
<img width="1282" height="729" alt="Emp2" src="https://github.com/user-attachments/assets/23f461f0-af87-4545-b212-ba34762c8d78" />

### 🏬 Page 3 – Store Performance & Business Outcomes  
- KPIs: **Total Stores (150), Avg Store Age (10 years), Avg Store CSAT (7.5), Avg Store NPS (40.12), OTD % (93.98%)**  
- Visuals:  
  - Total Sales by Store Type & Department  
  - Headcount by Store Type  
  - Sales per Employee by Education Level & Employment Type  
  - Store rankings by Sales per Employee  
<img width="1285" height="731" alt="Emp3" src="https://github.com/user-attachments/assets/1ed8d93d-aa01-4835-a21d-3fb1d1aaaf56" />

---

## Key Strategic Insights  
- **Entry-level and Associate roles dominate headcount**, but also show highest turnover → targeted retention programs needed.  
- **Career Growth opportunities are limited**, with most employees falling under “Poor Career Growth.”  
- **PhD and Contractor employees deliver highest sales per employee**, indicating productivity gains from advanced education and flexible work arrangements.  
- **Turnover rate (19.88%) poses a risk** for organizational stability, especially among junior roles.  
- **Store Operations generates the bulk of sales**, highlighting it as a priority area for workforce investment.  

---

## Conclusion  
The **Employee Growth & Business Impact Dashboard** demonstrates the power of analytics in workforce management. By consolidating employee, performance, and business outcome data into a single reporting model, it empowers decision-makers to act on insights quickly and effectively.  

Whether used in **HR reviews, workforce planning sessions, or executive meetings**, the dashboard provides a unified source of truth on employee growth, engagement, and business outcomes. With its clear KPIs, star schema model, and interactive visuals, this solution enables organizations to strengthen retention, improve engagement, and align workforce strategies with business goals.  

---

## 🚀 Tech Stack  
- **Power BI** (Data Modeling, DAX, Visuals)  
- **Excel** (Data Source)  
- **Star Schema Modeling** (Fact + Dimension Tables)  

---

✨ *This project highlights how analytics can bridge HR, employee engagement, and business outcomes—
