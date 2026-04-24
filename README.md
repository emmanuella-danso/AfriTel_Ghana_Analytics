AfriTel Ghana – Customer Churn Analytics
Python • SQL • Power BI • Telecom Analytics
This project delivers a full end to end churn intelligence solution for AfriTel Ghana, a simulated telecom operator modeled on real customer behaviour. The analysis integrates Python, SQL, and Power BI to uncover churn drivers, quantify revenue loss, and build actionable retention strategies.
⭐ Project Overview
AfriTel Ghana is experiencing a 14.55% churn rate, driven primarily by:
•	Service failure — customers with 4+ service calls churn at 48%–100%
•	International plan dissatisfaction — plan users churn at 43.7% vs 11.27% for non users
•	High value customer loss — churned customers generate $64.84 average revenue
The analysis confirms that AfriTel is not losing low usage customers — churned customers actually use the network more than retained ones (1,045 mins vs 983 mins). This makes churn a service experience problem, not a usage problem.
📁 Repository Structure
Code
AfriTel_Ghana_Analytics/
│
├── README.md
│
├── Data/
│     └── raw_data.csv / raw_data.xlsx
│
├── Reports/
│     └── AfriTel_Ghana_Churn_Analytics_Report.pdf
│
├── PowerBI/
│     └── PBIX_Link.txt
│
📥 Power BI Dashboard (PBIX)
🔗 PBIX Download: 
https://drive.google.com/file/d/1AXDZK-UcVGlNcmeklpRkbfr1waV6l0_b/view?usp=sharing

📄 Full PDF Report
The full consulting grade report is available in the /Reports/ folder:
AfriTel_Ghana_Churn_Analytics_Report.pdf
🧠 Key Insights
1. Service Calls Are the #1 Churn Trigger
•	Churn jumps from 14% → 48% at 4 service calls
•	Reaches 100% at 9 calls
•	Indicates unresolved complaints, not engagement
“The 3rd service call is the last point where churn is still preventable.”
2. International Plan Users Are 4x More Likely to Churn
•	Plan users churn at 43.7%
•	Non users churn at 11.27%
•	118 customers at risk → $7,651 monthly revenue at risk
3. High Usage Does NOT Prevent Churn
•	Churned customers: 1,045 mins
•	Retained customers: 983 mins
This disproves the assumption that low usage drives churn.
4. Revenue Loss Is Significant
•	Avg revenue (churned): $64.84
•	Avg revenue (retained): $58.43
•	Monthly revenue lost: $25,182
•	Annualised loss: $302,189
5. Risk Segmentation
Segment	Churn Rate	Notes
High Risk	46.7%	Immediate intervention needed
Medium Risk	7.4%	Prevent escalation
Low Risk	8.2%	Monitor & maintain
Retaining just 50% of High Risk customers protects $6,938/month.
🛠️ Tools & Technologies
•	Python — data cleaning, feature engineering, risk scoring
•	SQL (SQLite) — churn validation queries
•	Power BI — dashboards, segmentation visuals, KPI modelling
•	Pandas / NumPy — data manipulation
•	Matplotlib / Seaborn — exploratory analysis
📐 Data Modelling & Feature Engineering
Feature Engineering Included:
•	Total_minutes (day + eve + night + intl)
•	Risk_Score (service calls + plan type + usage)
•	Risk_Level (High / Medium / Low)
KPIs Defined:
•	Churn Rate
•	Avg Revenue (Churned vs Retained)
•	Service Call Churn Trigger
•	International Plan Churn Rate
•	High Risk Segment Size
📊 Dashboards Included
•	Executive Overview
•	Churn Drivers & Behaviour
•	Customer Segmentation
•	Revenue at Risk
•	Usage vs Churn Analysis
Screenshots are available in the /Screenshots/ folder.
📌 Business Recommendations
1. Implement the 3 Call Intervention Rule
Trigger a senior agent callback at the 3rd service call.
2. Conduct an International Plan Emergency Review
High churn indicates pricing or experience issues.
3. Deploy an Early Warning Churn Scoring System
Flag customers with:
•	3+ service calls
•	International plan
•	High usage + complaints
4. Launch Targeted Retention Campaigns
Prioritise the 214 High Risk customers.
5. Establish Monthly Churn Intelligence Reporting
Track churn rate, risk segment size, and revenue at risk.
👩🏽‍💻 Author
Emmanuella Danso Data Analyst | Business Intelligence | Power BI 📧
 Email: nuelladee7@gmail.com 🔗 
