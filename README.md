# 🛠️ FP28 Challenge – IT Support Ticket Performance Analysis (Power BI)

Welcome to my submission for the **FP28 Data Storytelling Challenge** titled:

🎯 **Ticket to Resolution: Optimizing IT Support Performance**

In this challenge, I took on the role of an **IT Support Analyst**, analyzing over **1,000+ support tickets**—replicating a real-world service desk system such as **Jira Service Management**—to uncover operational inefficiencies, highlight trends, and offer process improvement insights using **Power BI**.

---

## 📊 Project Objectives

The goal of this analysis was to explore:
- How fast support teams resolve tickets
- What types of issues and tags are most common
- How performance varies by queue, region, and ticket type
- How to improve IT workflows and customer satisfaction

---

## 📁 Dataset Overview

The dataset includes:
- `Ticket ID`, `Created Date`, `Resolution Date`
- `Subject`, `Body`, `Answer`
- `Priority`, `Queue`, `Type` (e.g., Bug, Request, Feature)
- `Tags` (Primary, Secondary, Other)
- `Country`, `City`, `Location`

---

## 🧰 Power BI Features & Techniques Used

### 🔧 Data Modeling
- **Star Schema**: Built a normalized model with:
  - `Fact_Tickets_Data`
  - `Dim_Tags`, `Dim_Priority`, `Dim_Type`, `Dim_Queue`, `Dim_Location`
- **Power Query**:
  - Unpivoted tags
  - Extracted date parts
  - Merged and cleaned data sources

### 🧠 DAX Measures
- `Avg Resolution Time`
- `SLA Breach Rate`
- `Tickets by Tag Type`
- `Top Country / Month by Volume`
- `Tickets Over Time`, etc.

### 📈 Visuals
- Matrix heatmaps with conditional formatting
- Custom tooltips
- **ZoomCharts Drill Down visuals**
- Slicers for queue, tag type, location
- Custom cards and KPI panels

### 🎨 Design
- Custom JSON theme using a modern blue-and-grey palette
- 16:9 canvas layout across **2 pages**:
  1. **Overview & Performance KPIs**
  2. **Tag & Regional Analysis**

---

## 📌 Key Insights

- **Avg Resolution Time**: 2.82 days  
- **SLA Breach Rate**: ~20% of tickets exceed 3-day target  
- **Best Performing Queues**: *Customer Service*, *Product Support*  
- **Most Common Tags**: *Integration*, *Security*, *Documentation*  
- **Heatmap**: Ticket submissions spike midweek  
- **Technical Support** handles the most tickets and maintains strong SLA performance

---

## 🚀 Recommendations

- Automate responses to repeated tag issues  
- Improve support for high-delay regions  
- Enhance routing logic to balance queue workloads  
- Develop self-service content based on frequent tickets

---

## 📎 Files

| File | Description |
|------|-------------|
| `IT_Support_Ticket_Analysis.pbix` | Power BI Desktop file (report) |
| `IT_Support_Ticket_Analysis.pdf` | Report pdf |
| `IT_Support_Ticket_Theme.json` | Custom theme used in the report |
| `Dashboard_Screenshots/` | PNG visuals of key pages |
| `Data Modelling Screenshots/` | PNG visuals of the star schema |
| `Challenge_28_IT_Support_Ticket_Desk.xlsx` | Raw dataset |

---

## 📷 Screenshots

### 📄 Page 1: Overview & Performance

![Overview](./Dashboard_Screenshots/overview.png)

### 🌍 Page 2: Tag & Location Analysis

![Tags](./Dashboard_Screenshots/tag_location.png)


### 🌍 Data Modelling: Screenshot of star schema

![Tags](./Dashboard_Screenshots/tag_location.png)

---

## 👨‍💻 Author

**Olamide Fakorede**  
Data Analyst | Python & Power BI  
[🔗 LinkedIn](https://www.linkedin.com/in/abdulafeezfakorede)  
[🔗 GitHub](https://www.github.com/pythonist4444)

---

## 🏁 Challenge by [FP20 Analytics](https://fp20analytics.com/live-challenge/)  
