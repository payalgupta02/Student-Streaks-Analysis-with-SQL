### Student Streaks Analysis with SQL

#### Overview
Analyzed **27.5k records** from an EdTech platform to study user learning streaks (Dec 2022–Jan 2023). Focused on streak activity, longest streaks, and engagement patterns to uncover where users drop off and how to sustain long streaks.

---

#### Steps
1. Explored dataset (active vs. frozen streaks, date range, unique users).  
2. Computed longest streaks per user.  
3. Bucketed users into streak ranges (1–5, 6–10, … 31–32 days).  
4. Identified and ranked top streak users (≥30 days).  

---

#### Key Results
- **Most users (86%)** drop within **1–5 days**.  
- **87 users** sustained streaks of **30+ days** (max: 32 days).  
- Mid-range streak users (6–20 days) show potential if nudged.  

---

#### Recommendations
- Add milestone badges (7, 14, 21 days).  
- Use reminders to reduce early drop-offs.  
- Build leaderboards & challenges to boost long-term streaks.  
- Expand freeze option to avoid streak breaks.  

---

#### Files
- `streaks_analysis_solved.sql` → SQL queries/solutions  
- `report.pdf` → Detailed analysis & insights  
- `README.md` → Project summary
