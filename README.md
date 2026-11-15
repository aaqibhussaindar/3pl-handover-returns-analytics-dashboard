# 📦 3PL Handover & Returns Analytics Dashboard

An end-to-end operational Business Intelligence (BI) dashboard built using **Looker Studio**, **Google Sheets**, and **Advanced Excel** to track high-volume 3PL parcel handovers, returns, branch holds, and district-level delivery distribution[cite: 3].

![Dashboard Overview](dashboard-overview.png)

---

### 🎯 Business Problem
Managing thousands of daily inbound scans, 3PL handovers, and return exceptions across multiple delivery districts creates tracking bottlenecks when monitored through raw spreadsheet logs. This dashboard consolidates daily operational sheets into a single, real-time decision-making view for branch monitoring and exception resolution[cite: 3].

---

### 📊 Key Operational Metrics Tracked
- **19,217** Total In-Scanned Shipments[cite: 3]
- **19,030** Total 3PL Handovers[cite: 3]
- **688** Total Returns (**501** 3PL Returns | **187** Branch Returns)[cite: 3]
- **6** Active Branch Hold Shipments[cite: 3]
- **10 Regional Districts Covered:** Warangal (22.6%), Nizamabad (14.0%), Karimnagar (11.7%), Sangareddy (11.7%), Rangareddy (10.2%), Mahabubnagar (6.6%), Nalgonda (6.3%), Siddipet (6.1%), Kamareddy (5.5%), and Jagtial (5.4%)[cite: 3]

---

### 🛠️ Architecture & Workflow
1. **Data Cleaning & Preparation (Advanced Excel):** Standardized consignment numbers, article IDs, weights, dates, and exception remarks; removed duplicates and reconciled daily in-scan vs. handover logs[cite: 3].
2. **Automated Data Management (Google Sheets):** Structured clean relational tabs for In-Scans, 3PL Handovers, 3PL Returns, Branch Returns, and Hold Shipments to feed live data into Looker Studio[cite: 3].
3. **Interactive Visualization (Looker Studio):**
   - **Executive KPI Scorecards:** Instant visibility into total in-scans, handovers, returns, and holds[cite: 3].
   - **Time-Series Trend Analysis:** Daily and monthly handover vs. return trends (March – September 2026) to identify peak dispatch volumes (e.g., 4.1K handovers in April 2026)[cite: 3].
   - **Root-Cause Exception Tracking:** Breakdown of return reasons (*Insufficient Address*, *Invalid Receiver Phone Number*, *Refused by Customer*, *Receiver Door Locked*, *Failed To Save API Error*)[cite: 3].
   - **Shipment-Level Drill-Down:** Interactive search filters by **Consignment No.** and **Article No.** alongside date-range controls for rapid floor-level reconciliation[cite: 3].

---

### 🧰 Tools & Skills Demonstrated
- **BI & Visualization:** Looker Studio (Google Data Studio)[cite: 3]
- **Data Preparation & Reporting:** Advanced Excel (Pivot Tables, XLOOKUP, Data Validation), Google Sheets (QUERY, ARRAYFORMULA)
- **Domain Analytics:** Logistics Operations, 3PL Manifest Reconciliation, Return-to-Origin (RTO) Root-Cause Analysis, SLA & Exception Monitoring[cite: 3]
