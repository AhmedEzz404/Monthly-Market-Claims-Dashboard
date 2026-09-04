# 📊 Monthly Market Claims & Quality Intelligence Dashboard

An executive Power BI quality analytics dashboard engineered to transform raw customer complaint logs and field failure reports into actionable quality intelligence. This solution enables quality assurance leads and operations management to isolate recurring failure modes, track field performance metrics (PPM), and drive targeted corrective actions.

---

### 📷 Dashboard Overview

![Monthly Market Claims Dashboard](monthly_market_claims_view1.png)

---

### 🎯 Key Analytical Highlights
* **Defect Categorization & Pareto Analysis:** Segregated major industrial defects from secondary sub-defects to identify the critical 20% of failure modes generating the majority of field claims.
* **Time-Series & Reliability Tracking:** Monitored monthly claim fluctuations and rolling PPM (Parts Per Million) trends against total production volume ($8M+$ units baseline).
* **Failure Timeline Segmentation:** Differentiated between infant mortality failures (first warranty month) and wear-and-tear claims occurring later in the lifecycle.
* **Model-Level Traceability:** Mapped quality claims across anonymized product models to isolate specific design or assembly line vulnerabilities.

---

### 🛠️ Technical Implementation
* **Data Modeling & Transformation:** Utilized **Power Query (M)** for data cleaning, column pruning, and structural reshaping across complex complaint records.
* **DAX Measures:** Authored custom dynamic calculations for defect percentages, monthly PPM tracking, claim counts, and time-series comparisons.
* **Interactive UI/UX Design:** Implemented dynamic slicers (Year, Month, Defect Type, Model) with cross-filtering interactions for seamless root-cause drill-down.

---

### 🔒 Data Governance & Privacy
*To comply with enterprise confidentiality and industrial intellectual property standards, proprietary SKU names and internal model identifiers have been masked and generalized into synthetic tags (e.g., Model-A, Model-B).*
