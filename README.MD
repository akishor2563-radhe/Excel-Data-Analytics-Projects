# 🏥 Hospital Emergency Room (ER) Patient Analytics & Operations Dashboard

## 📌 Executive Summary
An interactive multi-sheet Excel dashboard built to analyze Hospital Emergency Room (ER) patient flow, operational bottlenecks, wait times, department referrals, and demographic distributions. The goal is to provide hospital administration with actionable insights to optimize staffing, reduce wait-time delays, and improve patient care delivery.

---

## 📊 Core Performance Metrics (KPIs)
* **Total ER Patients:** 4,878 (Year 2024)
* **Average Patient Satisfaction Score:** 4.96 / 10
* **Average Wait Time:** 36.32 minutes
* **Operational Wait-Time Status:**
  * **Delayed (>30 mins):** 2,561 patients (52.5%)
  * **Normal (≤30 mins):** 2,317 patients (47.5%)
* **Admitted to Inpatient Care:** 2,455 patients (approx. 50.3% admission rate)

---

## 🖥️ Dashboard Architecture & Sheets
The workbook features a custom Dark/Navy UI with shape-based button hyperlinks for seamless navigation:

1. **🏠 HOME:** Central landing page with one-click navigation buttons to all operational views.
2. **📈 OVERALL DASHBOARD:** Executive KPI cards, Year/Month interactive slicers, monthly admission trendlines, and departmental patient volume.
3. **👥 AREA DASHBOARD (Demographics Analysis):**
   * **Gender Distribution:** 52% Male (2,504) vs 48% Female (2,347).
   * **Age Group Segments:** Mid-Age Adults (1,841) and Seniors (1,160) make up over 61% of total ER visits.
   * **Racial Representation:** White (1,346), African American (1,031), Two or More Races (835), Asian (564), Declined to Identify (554), Pacific Islander (286), Native American (262).
4. **🏥 DEPARTMENT DASHBOARD:**
   * Workload breakdown across medical specialties.
   * Donut chart tracking **Normal vs Delayed Wait-Time Status**.
5. **📋 PATIENT DASHBOARD:** Drill-down view filtered by patient demographics and intake details.
6. **💾 DATA & PIVOTS:** Normalized raw dataset (`hospital_emergency_room_data_1c`) powering structured Pivot Tables.

---

## 💡 Top Business & Healthcare Insights
1. **High Unreferred Inflow (Triage Challenge):** 
   * **59.2% of all patients (2,886)** arrived as "Not Referred", meaning the majority were unscheduled walk-ins creating sudden surges in ER reception.
2. **Departmental Bottlenecks:**
   * Out of referred cases, **General Practice (966)** and **Orthopedics (532)** handle 72% of the referral load.
3. **Operational Delays Need Attention:**
   * Over **52.5% of visits experienced waiting time delays**, indicating a pressing need to optimize nurse-to-patient triage during peak admission hours.
4. **Target Demographic Demands:**
   * With **1,160 Senior patients (60+)** and **1,841 Middle-aged patients**, hospital resources should prioritize cardiovascular, orthopedics, and chronic care pathways.

---

## 🛠️ Technical & Excel Tools Applied
* **UI/UX Design:** Custom Navigation Bar with Hyperlinked Shapes, Dark Mode contrast, and polished KPI Cards.
* **Data Processing:** Pivot Tables, calculated fields, sorting, and conditional logic.
* **Dynamic Interactivity:** Multi-criteria Slicers (Year, Month, Patient Race) connected across multiple Pivot Tables.
* **Data Visualization:** Clustered Bar/Column Charts, Donut charts, and Monthly Area Trendlines.
