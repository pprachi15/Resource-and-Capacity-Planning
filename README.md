# 📊 Resource & Capacity Planning Dashboard
<img width="1512" height="982" alt="image" src="https://github.com/user-attachments/assets/5e9143b2-0e3d-4e90-a334-6bad68d3e06c" />

### Filters:
<img width="1498" height="57" alt="image" src="https://github.com/user-attachments/assets/923fcd8b-4ecf-43e5-86fa-24313adf1f7c" />
<p align="left">
  <img src="https://github.com/user-attachments/assets/9cd94881-f790-4355-a540-79d33ea0c419" width="400"/>
  <img src="https://github.com/user-attachments/assets/f9737cd4-bed0-417e-9087-ea43fd21e26b" width="400"/>
  
</p>
<p align="left">
  
   
  <img src="https://github.com/user-attachments/assets/396d8850-33b5-48b0-a656-56d770f558f6" width="400"/>
  <img src="https://github.com/user-attachments/assets/33b4633f-239c-4347-9a26-d9b6bf12f599" width="400"/>
</p>
<p align="left">
 <img src="https://github.com/user-attachments/assets/a21b961f-556b-4c29-a648-37ffbe156e44" width="400"/>
  <img src="https://github.com/user-attachments/assets/5eff7097-71c6-4436-9b89-45edfd4d9a1d" width="400"/>
</p>



## 1. Project Overview
The **Resource & Capacity Planning Dashboard** is designed to simulate how FP&A and Operations teams monitor and optimize workforce, production capacity, and capital expenditures.  
The goal is to provide **decision-ready insights** into:
- How actual production compares to forecast.
- Where capacity is under- or over-utilized.
- Which departments are overstaffed, understaffed, or on target.
- Whether capital expenditures are delivering ROI.
- How overtime levels and labor costs affect operational efficiency.

---

## 2. Data & Methodology

### 📂 Dataset
- Synthetic dataset (~500 rows, 24 months, 6 departments).
- Variables:
  - **Production Metrics:** Max Capacity, Forecast Output, Actual Output.
  - **Workforce Metrics:** Headcount Forecast, Headcount Actual, Total Hours, Overtime Hours.
  - **Financial Metrics:** Labor Cost, CapEx Investment, Output Increase.

### 🔧 KPI Calculations
- **Capacity Utilization %** = Actual Output / Max Capacity
- **Headcount Variance** = Headcount Actual – Headcount Forecast
- **Labor Cost per Unit** = Labor Cost / Actual Output
- **CapEx ROI** = Output Increase / CapEx Investment
- **Overtime %** = Overtime Hours / Total Hours
- **Output Variance %** = (Actual – Forecast) / Forecast

---

## 3. Dashboard Components

### 🔹 Filters
- Department
- Month
- Measures
- Headcount Variance (On Target, Overstaffed, Understaffed)
- Overtime Band (Healthy, Moderate, High)
- CapEx Category (No Investment, Small, Medium, Large)

### 🔹 Charts
1. **Actual vs Forecast Output Over Time (Line)**  
   Compares actual production to forecast, showing over/under performance trends.

2. **Capacity Utilization % by Department (Bar)**  
   Highlights efficiency across departments (green zone >90%, red <80%).

3. **CapEx Investment vs Output Increase (Scatter)**  
   Evaluates ROI on capital expenditures with bubble size/color showing ROI.

4. **Headcount Variance (Bar/Waterfall)**  
   Shows staffing gaps vs forecast (Overstaffed, Understaffed, On Target).

5. **Overtime % by Department and Month (Stacked Bar)**  
   Categorizes overtime levels (<5%, 5–10%, >10%) to spot undercapacity.

6. **Labor Efficiency Trend (Area Chart)**  
   Tracks Labor Cost per Unit over time to monitor efficiency.

7. **Overtime % vs Target (Bullet/Bar)**  
   Benchmarks each department against a 5% overtime target line.

---

## 4. Why This Matters for Tesla
- **FP&A Relevance**  
  - Forecast vs Actual variance analysis.  
  - Workforce planning & headcount optimization.  
  - CapEx ROI tracking.  

- **Operations Relevance**  
  - Overtime management = undercapacity detection.  
  - Capacity utilization = bottleneck identification.  
  - Labor efficiency = cost per unit optimization.  

- **Strategic Value**  
  This dashboard answers the daily FP&A + Ops questions:  
  1. Are we hitting forecasts?  
  2. Do we have the right staffing levels?  
  3. Are we overspending on labor or CapEx?  
  4. Where are our biggest risks (underperformance, high overtime, low ROI)?  

---

## 5. Technical Stack
- **Data Generation:** Python (NumPy, Pandas)  
- **Visualization:** Tableau  
- **Design Principles:**  
  - Tesla-style color coding (Green = Good, Red = Bad).  
  - Filters for interactive exploration.  
  - Clear titles + tooltips for quick insights.  

---

## 6. Future Improvements
- Connect to **real datasets** (ERP, HR, Solar/Storage data).  
- Add **forecasting models** (ARIMA, Prophet) to predict capacity/labor needs.  
- Integrate **financial statements** (OpEx, CapEx from P&L).  
- Build **alert system** (e.g., notify when Overtime >10% or ROI < threshold).  

---

## 7. Conclusion
The **Resource & Capacity Planning Dashboard** demonstrates how FP&A and Ops leaders can turn raw operational data into **actionable insights**. By tracking production, labor, and financial efficiency in one unified view, it equips leadership to make better staffing, investment, and capacity decisions — exactly the type of analysis Tesla expects from its Finance & Ops teams.

---

## 📬 Let’s Connect
If you’re a recruiter, hiring manager, or industry professional interested in learning more about this project, feel free to reach out. I’d be happy to walk through the methodology, KPIs, and decision-making insights in more detail, and discuss how this type of analysis can be applied to real-world FP&A and operations use cases.  
