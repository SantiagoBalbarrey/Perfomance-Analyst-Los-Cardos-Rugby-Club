# 🏉 Rugby Performance Analytics – Los Cardos Rugby Club
### LongoMatch Event Data + Qlik Sense Dashboards


![Qlik Sense](https://img.shields.io/badge/Qlik%20Sense-009848?style=for-the-badge&logo=qlik&logoColor=white) ![Data Analytics](https://img.shields.io/badge/Data%20Analytics-1A73E8?style=for-the-badge&logo=google-analytics&logoColor=white) ![Sports Analytics](https://img.shields.io/badge/Sports%20Analytics-FFB000?style=for-the-badge) ![ETL](https://img.shields.io/badge/ETL-4B8BBE?style=for-the-badge) ![Data Modeling](https://img.shields.io/badge/Data%20Modeling-FF6F00?style=for-the-badge) 

<p align="center">
  <img src="images/cover/banner_github.png" width="400"/>
</p>

## 📌 Overview
This project analyzes match performance for **Los Cardos Rugby Club** using event‑based data exported from **LongoMatch** and processed in **Qlik Sense**.  
The goal is to automate post‑match reporting and provide actionable insights to the coaching staff through interactive dashboards.

---

## 🧱 Tech Stack
- LongoMatch (event tagging & data export)  
- Qlik Sense (ETL, data modeling, dashboards)  
- Excel / CSV (raw data handling)  
- Data modeling: star‑schema‑inspired structure  
- Visualization: KPI dashboards, trend analysis, performance categories  

---

## 📊 Dashboards
- Overview dashboard  
- Attack Performance 
- Set Piece Acquisition (Scrum & Lineout)  
- Set Piece Launches (Scrum & Lineout)  
- Breaks  
- Discipline  

### Overview
<img src="dashboards/Torneo%20UNRMDP%20%20-%20Dashboard.png" width="800"/>

### Attack Performance
<img src="dashboards/Torneo%20UNRMDP%20%20-%20Attacking%20Perfomance.png" width="800"/>

### Set Piece Acquisition
<img src="dashboards/Torneo%20UNRMDP%20%20-%20Set%20Piece%20Aquisition.png" width="800"/>

---

## 🔍 Key Metrics
- Try origin & attacking patterns  
- Break efficiency & outcomes  
- Scrum and lineout success rates  
- Launch effectiveness  
- Penalties by type and phase  
- Turnovers & multiphase play  
- Points scored, conceded & efficiency indicators  

---

## ⚙️ Workflow Summary
1. Export match events from LongoMatch (CSV).  
2. Clean, normalize, and structure the data.  
3. Build a data model in Qlik Sense.  
4. Create dashboards with automated reloads.  
5. Generate post‑match insights for weekly analysis.

---
## 📁 Repository Structure

```
Perfomance-Analyst-Los-Cardos-Rugby-Club/
│
├── scripts/
│   └── qlik/
│       ├── Fact_Partidos.qvs
│       ├── Dim_Fecha.qvs
│       ├── Dim_Rival.qvs
│       ├── Dim_Metrica.qvs
│       └── Global_Variables.qvs
│
├── dashboards/
│   ├── Torneo UNRMDP - Dashboard.png
│   ├── Torneo UNRMDP - Attacking Perfomance.png
│   ├── Torneo UNRMDP - Set Piece Aquisition.png
│   ├── Torneo UNRMDP - Set Piece Launches.png
│   ├── Torneo UNRMDP - Breaks.png
│   ├── Torneo UNRMDP - Discipline.png
│   └── torneo2025video.mp4
│
├── docs/
│   ├── project_overview.md
│   ├── etl_overview.md
│   ├── data_model.md
│   ├── workflow.md
│   └── next_steps.md
│
├── images/
│   └── cover/
│
├── README.md
└── LICENSE
```---

## 🚀 Next Steps
- Full automation of the ETL pipeline  
- Integration with GPS/tracking data  
- Predictive analytics for performance forecasting  
- Additional KPIs for player‑level analysis  

---

## 👤 Author
**Santiago Balbarrey**  
Data Analytics | BI | Sports Analytics


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santiagobalbarrey/)

You can reach me on LinkedIn for feedback, collaboration, or project discussions.