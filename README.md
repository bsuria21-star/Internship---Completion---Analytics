# Internship Performance & Completion Analytics

## 📌 Project Overview
This project focuses on analyzing internship completion and dropout rates across three core corporate departments: Engineering, IT, and Marketing. Utilizing a dataset of 20 interns, the analysis tracks key performance indicators, program durations, and weekly mentor sync frequencies to optimize the onboarding process, identify processing bottlenecks, and improve overall talent retention strategies.

## 📊 Live Interactive Dashboard
👉 **[View the Interactive Tableau Dashboard Here]([https://public.tableau.com/app/profile/suria.bano/viz/InternshipAnalyticsDashboard/Dashboard1])**

## 🛠️ Tools & Technologies Used
* **Data Visualization:** Tableau Public
* **Data Processing & Pivot Analysis:** Microsoft Excel / Google Sheets
* **Version Control & Hosting:** GitHub

## 🗂️ Dataset Structure
The analysis was conducted using a structured database tracking 20 intern profiles with the following attributes:
* `Intern_ID`: Unique identifier for each participant.
* `Department`: Engineering, IT, or Marketing.
* `Duration_Weeks`: Length of the internship program (4, 8, or 12 weeks).
* `Mentor_Syncs_Per_Week`: Number of weekly touchpoints with assigned mentors (0 to 5).
* `Status`: Final completion state (Completed vs. Dropped Out).

## 💡 Key Findings from Pivot Analysis

### 1. Departmental Performance & Completion Rates
* **Engineering:** Out of 7 total interns, 5 successfully completed the program while 2 dropped out (~71% completion rate).
* **IT (Information Technology):** Out of 7 total interns, 5 successfully completed the program while 2 dropped out (~71% completion rate).
* **Marketing:** Showed the highest attrition with 3 completions and 3 dropouts (50% completion rate).
* **Overall Cohort:** Across all departments, **13 out of 20 interns successfully completed** the program (65% overall success rate).

### 2. The Impact of Internship Duration
* Short-term programs (**4 weeks**) saw a perfect **100% completion rate** (3 out of 3 completed).
* Longer programs (**12 weeks**) experienced the highest dropout volume (4 out of 9 dropped out), indicating that extended programs need stronger continuous engagement.

### 3. Critical Factor: Mentor Syncs Per Week (The Big Insight!)
* **Zero to Low Guidance:** Every single intern who had **0 or 1 mentor sync per week dropped out** (7 out of 7 total dropouts fell into this category).
* **Optimal Support:** Every single intern who received **2 or more mentor syncs per week successfully completed** the internship (13 out of 13 total completions). 
* *Conclusion:* Regular weekly mentor interaction is the absolute highest determining factor for intern retention and success.

## 🚀 Strategic Recommendations
1. **Mandatory Mentor Thresholds:** Establish a strict policy requiring a minimum of 2 mentor syncs per week for all interns to eliminate the 100% dropout bottleneck seen at lower sync rates.
2. **Marketing Track Intervention:** Revamp the Marketing internship curriculum or onboarding process to address the high 50% drop-out rate.
3. **Mid-Term Engagement for 12-Week Tracks:** Introduce structured milestone reviews at week 6 for the extended 12-week cohorts to re-engage interns and reduce late-stage dropouts.
