# Logistics Dashboard

## 📖 Overview
The **Logistics Dashboard** is a real-world data project built to address a company's need for general metrics such as order volume, pallet utilization, inbound performance, and API bandwidth usage.  

On the technical side, this project required significant data cleaning, dealing with incomplete/multi-source datasets, merging data, gathering information from APIs, and implementing incremental calls for automation. It also included building new metrics with integrity, sometimes deploying small apps to support reporting.

This project is only for visualization no source code available and all data is self generated.
---

## 🚚 Inbound Shipments (Example Tab)

![Inbound Shipments GIF](Dashboard%20Screenshots/ReadmeGIF.gif)

---

## 💡 Business Value
This dashboard provided **tangible impact** to logistics operations:

- 📦 **SLA Control** → Identified containers out of SLA, enabling root-cause analysis and achieving revenue.  
- ⚡ **Operational Efficiency** → Reduced inbound processing times, increasing container throughput.  
- 🗂️ **Pallet Utilization Trends** → Anticipated customer volume changes for proactive adjustments.  
- 📊 **Order & Inbound Forecasting** → Visualized activity by weekday to improve staffing and resource allocation.  
- 🗺️ **Geographic Insights** → Displayed order distribution by state to optimize carrier selection and route planning.  

---
## 🛠️ Tech Stack

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=white&style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white&style=for-the-badge)
![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?logo=microsoftsharepoint&logoColor=white&style=for-the-badge)
![Power Apps](https://img.shields.io/badge/Power%20Apps-742774?logo=powerapps&logoColor=white&style=for-the-badge)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?logo=powerautomate&logoColor=white&style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)

## 💡 Skills Demonstrated

<p align="left">
  <!-- Visualización -->
  <img src="https://img.shields.io/badge/DATA%20VISUALIZATION-7B61FF?style=for-the-badge&labelColor=3b2ecc&logo=powerbi&logoColor=white" alt="Data Visualization">
  <!-- Data Modeling -->
  <img src="https://img.shields.io/badge/DATA%20MODELING-FF7A59?style=for-the-badge&labelColor=B84E2F" alt="Data Modeling">
  <!-- DAX + Power Query -->
  <img src="https://img.shields.io/badge/DAX%20%2B%20POWER%20QUERY-F2C811?style=for-the-badge&labelColor=C7A300&logo=powerbi&logoColor=black" alt="DAX + Power Query">
  <!-- SharePoint / Graph -->
  <img src="https://img.shields.io/badge/SHAREPOINT%20%2F%20GRAPH-0078D4?style=for-the-badge&labelColor=005EA6&logo=microsoftsharepoint&logoColor=white" alt="SharePoint / Graph">
  <!-- Python Automation -->
  <img src="https://img.shields.io/badge/PYTHON%20AUTOMATION-3776AB?style=for-the-badge&labelColor=244A78&logo=python&logoColor=white" alt="Python Automation">
</p>


## 📑 Tabs Documented

| Tab | Screenshot | Documentation |
|-----|------------|---------------|
| Geographic Distribution of Orders | <img src="Dashboard%20Screenshots/Map%20Orders%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Geographic%20Distribution%20of%20Orders%20Tab.md) |
| Inbound Shipments | <img src="Dashboard%20Screenshots/Inbound%20Shipments%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Inbound%20Shipments%20Tab.md) |
| Shipped Orders Processed | <img src="Dashboard%20Screenshots/Orders%20Shipped%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Shipped%20Orders%20Processed%20Tab.md) |
| Pallet Usage | <img src="Dashboard%20Screenshots/Pallet%20Usage%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Pallet%20Usage%20Tab.md) |
| Business KPIs | <img src="Dashboard%20Screenshots/Business%20KPIs%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Business%20KPIs.md) |
| API Bandwidth Consumption | <img src="Dashboard%20Screenshots/API%20Bandwidth%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/API%20Bandwidth%20Consumption%20Tab.md) |

---



## 📂 Folder Structure

```text
Logistics-Dashboard/
├─ README.md                   # Main documentation
├─ Dashboard Screenshots/      # Screenshots for each tab
│  ├─ API Bandwidth Tab Screenshot.png
│  ├─ Business KPIs Tab Screenshot.png
│  ├─ Inbound Shipments Tab Screenshot.png
│  ├─ Map Orders Tab Screenshot.png
│  ├─ Orders Shipped Tab Screenshot.png
│  └─ Pallet Usage Tab Screenshot.png
├─ Dashboard Tabs/             # Detailed docs for each tab
│  ├─ API Bandwidth Consumption Tab.md
│  ├─ Business KPIs.md
│  ├─ Geographic Distribution of Orders Tab.md
│  ├─ Inbound Shipments Tab.md
│  ├─ Pallet Usage Tab.md
│  └─ Shipped Orders Processed Tab.md
└─ Dummy Data/                 # Sample dataset
   ├─ BandwidthData.xlsx
   ├─ Customers.xlsx
   ├─ InboundData.xlsx
   ├─ OrdersData.xlsx
   └─ PalletUsage.xlsx
