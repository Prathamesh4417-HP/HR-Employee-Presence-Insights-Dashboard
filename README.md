# 👥 HR – Employee Presence Insights Dashboard | Power BI

An interactive **Power BI analytics report** designed to monitor employee presence, work-from-home (WFH), and sick leave (SL) patterns across time, employees, and weekdays.  
This dashboard enables HR teams to track attendance trends, identify absenteeism patterns, and support workforce planning decisions.

---

## 📌 Project Overview

The **Employee Presence Insights Dashboard** provides a centralized analytical view of workforce attendance data.  
It helps HR and management teams understand:

- Overall employee presence percentage
- Work-from-home and sick leave trends
- Employee-level attendance behavior
- Day-wise and month-wise presence patterns

This project is ideal for:
- 👩‍💼 HR & People Analytics Teams  
- 📊 Business & Data Analysts  
- 🏢 Operations & Workforce Managers  
- 🎓 Power BI Portfolio & Case Study Projects  

---

## 🛠️ Tech Stack

The dashboard was built using:

- 📊 **Power BI Desktop** – Data visualization and report development  
- 📂 **Power Query** – Data cleaning and transformation, And Custom Fuctioning for Reusability 
- 🧠 **DAX (Data Analysis Expressions)** – KPI calculations and attendance logic  
- 🗂️ **Data Modeling** – Optimized employee-date model  
- 📁 **File Formats**
  - `.pbix` – Power BI report file  
  - `.png` – Dashboard preview images  

---

## 📊 Dataset Description

The dataset contains employee attendance records including:

- Employee Name
- Date
- Attendance Status:
  - Present (P)
  - Work From Home (WFH)
  - Sick Leave (SL)
  - Weekly Off (WO)
  - Holiday (HML)
- Working Days
- Month & Weekday details

---

## 🚀 Features & Dashboard Highlights

### 🧩 Business Problem

HR teams often struggle to:
- Monitor attendance consistency
- Track WFH and sick leave impact
- Identify weekday attendance patterns
- Analyze employee-level presence trends

Manual tracking lacks visibility and scalability.

---

### 🎯 Goal of the Dashboard

To deliver an **interactive HR analytics dashboard** that:
- Tracks workforce presence KPIs
- Highlights WFH and sick leave trends
- Enables employee-level attendance analysis
- Supports data-driven HR decisions

---

### 📈 Walkthrough of Key Visuals

#### 🔢 KPI Cards
- **Total Working Days:** 4,369  
- **Present Days:** 4,012  
- **Presence %:** 91.83%  
- **WFH %:** 10.00%  
- **SL %:** 1.20%  
- **Total Employees:** 99  

---

#### 👤 Employee Presence Table
- Employee-wise breakdown of:
  - Presence %
  - WFH %
  - SL %
  - WFH Count
- Helps identify attendance consistency at an individual level

---

#### 📅 Presence by Weekdays
- Weekday-wise analysis of:
  - Presence %
  - WFH %
  - Sick Leave %
- Identifies patterns such as lower presence on specific days

---

#### 📊 WFH, SL % and Count by Weekdays
- Combined visual showing:
  - WFH %
  - SL %
  - WFH Count
- Helps understand remote work and absenteeism trends

---

#### 📈 Presence % by Month and Day
- Day-wise presence trend across months
- Highlights attendance dips and peaks

---

#### 📉 WFH % by Month and Day
- Shows work-from-home adoption over time
- Useful for policy evaluation and planning

---

#### 📉 SL % by Month and Day
- Identifies sick leave patterns
- Supports workforce health analysis

---

#### 🗓️ Month Selector
- Dynamic slicer to analyze data by month:
  - April 2022
  - May 2022
  - June 2022

---

## 💡 Key Insights

- 📈 **Overall employee presence remains above 90%**
- 🏠 **WFH contributes significantly to total attendance**
- 📅 **Mid-week days show higher presence compared to Fridays**
- 🚑 **Sick leave percentage remains low but consistent**
- 👥 **Employee-level analysis helps identify outliers**

---

## 🖼️ Dashboard Preview

![Employee Presence Dashboard](https://github.com/Prathamesh4417-HP/HR-Employee-Presence-Insights-Dashboard/blob/master/Snapshot_HR_Analytics.png)

> *Alt text: Power BI HR dashboard displaying employee presence KPIs, weekday analysis, attendance trends, and employee-level attendance table.*

---

## 📂 Repository Structure

```text
📦 hr-employee-presence-dashboard
 ┣ 📁 data
 ┃ ┗ employee_attendance_data.csv
 ┣ 📁 screenshots
 ┃ ┗ employee_presence_dashboard.png
 ┣ 📄 HR_Employee_Presence.pbix
 ┗ 📄 README.md
