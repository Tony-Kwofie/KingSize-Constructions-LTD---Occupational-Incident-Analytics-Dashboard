# 💼 OHS Incident Analytics Dashboard – Power BI

## 📊 Overview  
**King Size Construction Ltd.** is a leading Ghanaian construction company known for delivering major infrastructure, engineering, and real estate projects. Operating in hazardous environments, the company places high priority on workplace safety and operational risk reduction.

To support this mission, a Power BI dashboard was developed to analyze **700+ simulated incident records** across sectors such as Construction, Mining, Manufacturing, and Oil & Gas. It provides **real-time safety intelligence** to help the Health, Safety & Environment (HSE) team make data-driven decisions.

---

## 🎯 Objectives  
- Monitor trends in workplace injuries by industry and role  
- Identify high-risk activities and root causes  
- Quantify the impact of PPE usage and supervision  
- Evaluate cost implications of safety non-compliance  
- Enhance training, PPE policy, and hazard response planning

---

## 🧩 Project Tasks & Features

✅ **Severity & Risk by Industry and Year**  
- Visualize annual incident trends by industry to understand sector-specific risk patterns.

📊 **Incident Breakdown by Job Role**  
- Spot top-affected roles (e.g., Technicians, Electricians, Welders) for targeted intervention.

🧪 **Root Cause Insights**  
- A pie chart highlights leading causes: **Chemical Exposure**, **Falls**, **Human Error**, **Fire**, and **Equipment Failure**.

🦺 **Injury Types & Body Parts with PPE Use**  
- Track what injuries (Burns, Fractures, Lacerations) occur, even when PPE is used. Breakdowns by body part provide actionable safety insight.

💰 **Cost Analysis by PPE & Severity**  
- Bar chart compares average costs of incidents with and without PPE. Fatal and major injuries without PPE are significantly more expensive.

🧩 **Interactive Filters**  
- Three binary slicers—**Supervision**, **PPE Used**, and **Hazard Reported**—enable deep dives into specific safety factors.

---

## 📁 Dataset  
*Simulated mock data used for privacy purposes, includes:*  
- `incident_date`  
- `industry`  
- `job_role`  
- `incident_severity`  
- `incident_cause`  
- `ppe_used`  
- `body_part`  
- `injury_type`  
- `cost_estimate_usd`  
- `supervision`  
- `hazard_reported`

---

## 🛠 Tools & Technologies  
- Power BI Desktop  
- Power Query for data preparation  
- DAX for calculated fields and KPIs  
- Microsoft Excel for mock data generation

---

## 💡 Challenges & Learnings  
- Built flexible, reusable DAX measures for OHS KPIs  
- Balanced data density with visual clarity for safety teams  
- Optimized filter interactions for fast root-cause analysis  
- Demonstrated PPE and supervision impact on incident cost reduction

---

## 📸 Screenshot  
<img width="633" alt="image" src="https://github.com/user-attachments/assets/813b27ea-48e1-4ac5-a3f0-1c1b06de0643" >


---

## 👤 Author  
**Anthony Eddei Kwofie**  
[LinkedIn](https://www.linkedin.com/in/anthony-eddei-kwofie-bsc-osha-484ab16a/) | [GitHub](https://github.com/Tony-Kwofie)

---

## 📌 How to Use  
1. Download or clone this repository  
2. Open the `.pbix` file in Power BI Desktop  
3. Interact with slicers to analyze by year, job role, industry, etc.  
4. Customize visuals and KPIs for your organization’s context

---

## 📬 Feedback & Contributions  
Got suggestions or improvements? Open a pull request or start a discussion!  
