# HR-Data-Analysis
## 1. Project Overview
![HR Data Analysis](https://github.com/user-attachments/assets/ff7cfc43-77fc-4f12-b773-74ab5d5a1e5e)

This project involves building a dashboard based on AtliQ’s employee presence data. The goal is to:

- **Visualize Overall Presence Rates**  
- **Track Work-from-Home (WFH) Preferences**  
- **Identify Patterns in Sick Leaves**  
- **Explore Possible Reasons for Sudden Absences**  

By consolidating various data points—such as dates, attendance types, total working days, and more—the dashboard provides actionable insights to help the organization understand employee behavior, improve resource planning, and anticipate trends related to attendance and absenteeism.

---

## 2. Data Description

1. **Dataset Composition**  
   - **Employee Presence Records:** Daily logs indicating whether each employee was present, working from home, or absent (e.g., sick or on vacation).  
   - **Time Period:** Spanning several months in 2022 (e.g., April to June).  
   - **Categorical Fields:** Attendance status (Present, WFH, Sick), Day of the Week, and Date Range.  
   - **Metrics:** Total working days (4,369 as shown in the screenshot), presence percentage, WFH percentage, and sick percentage.

2. **Data Quality Checks**  
   - Each record was verified for a valid date and a corresponding employee identifier or name.  
   - Presence types (Present, WFH, Sick) were confirmed to be consistently labeled.  
   - Any duplicate or conflicting records were removed or reconciled.

3. **Data Preparation**  
   - Date fields were standardized to ensure proper time-series analysis.  
   - Summary metrics were calculated, including total days recorded, total presents, total WFH days, and total sick days.  
   - Additional columns were created for day-of-week analysis (e.g., Monday, Tuesday, etc.).

---

## 3. Dashboard Development
![image](https://github.com/user-attachments/assets/1749ff92-9bf1-4708-9f10-d9f78a786cf9)
Using a Power BI, I built an interactive dashboard titled **“AtliQ Presence Insights.”** The design includes high-level summaries and detailed breakdowns of attendance patterns.

1. **Metrics Cards**  
   - **Total Working Days (4,369)**: Shows the sum of all employee workdays within the dataset.  
   - **Present Percentage (91.83%)**: Indicates how often employees are physically present.  
   - **WFH Percentage (10.00%)**: Highlights remote work adoption.  
   - **Sick Percentage (1.10%)**: Captures how often employees are absent due to illness.

2. **Trend Lines by Date**  
   - **Present Percentage by Date**: A line chart illustrating presence rates over time.  
   - **WFH Preference by Date**: Another line chart comparing remote-work adoption across the same period.  
   - **Sick Percentage by Date**: Shows variations in sick leaves, potentially indicating seasonal illnesses or unexpected spikes.

3. **Day-of-Week Analysis**  
   - **Attendance by Day**: Displays how attendance types (Present, WFH, Sick) are distributed throughout the week.  
   - **Purpose**: Reveals potential patterns, such as higher WFH on certain weekdays or a spike in sick leaves around weekends.

4. **Tabular Breakdown**  
   - **Employee-Level Presence**: A table listing individuals with their respective presence, WFH, and sick rates.  
   - **Purpose**: Identifies employees with high in-office presence, as well as those who may require additional support or schedule adjustments.

---

## 4. Key Visuals and Insights

1. **High Overall Presence**  
   - With over 90% presence, AtliQ maintains a predominantly office-centric culture. This may be due to the nature of roles or company policy.

2. **Work-from-Home Trends**  
   - The 10% WFH rate indicates moderate acceptance of remote work. Certain spikes in WFH on specific days could suggest a preference for remote setups around weekends or personal events.

3. **Sick Leave Fluctuations**  
   - Though the total sick percentage is only around 1.10%, specific clusters on the line chart might align with seasonal illnesses or localized outbreaks.  
   - Cross-referencing sick leaves with external data (e.g., local events, weather changes) could explain sudden increases.

4. **Sudden Holiday Patterns**  
   - The dashboard highlights weeks with a noticeable drop in presence or a rise in sick leaves. Further exploration could link these to festivals, public holidays, or internal stress periods.

5. **Day-of-Week Preferences**  
   - Analysis by weekday suggests employees may favor remote work on Mondays or Fridays, aligning with flexible scheduling or personal commitments.

6. **Potential Actionable Steps**  
   - If recurring sick spikes appear in certain months, HR could prepare in advance by offering flu shots or flexible leave policies.  
   - Management might formalize partial remote work options on days with consistently higher WFH rates to accommodate employee preferences.

---

## 5. Conclusion

The **“AtliQ Presence Insights”** dashboard delivers a comprehensive overview of employee attendance behavior, highlighting in-office presence, remote work adoption, and patterns in sick leave. This data-driven approach helps identify possible reasons for absenteeism—whether tied to health, personal, or cultural factors—and enables a proactive response.

**Key Takeaways**:
- A high presence rate (91.83%) underscores an office-centric environment.  
- A 10% WFH rate points to moderate remote work adoption, often concentrated around specific days.  
- A 1.10% sick rate, though low, reveals periodic spikes that may correspond to seasonal or event-based factors.  
- Understanding the timing and reasons behind sudden holidays can lead to more supportive policies, including flexible scheduling or wellness initiatives.

---

## 6. Potential Next Steps

1. **Correlation with External Data**  
   - Compare sick leave patterns with local flu outbreaks, holiday calendars, or weather events to confirm potential causes of absenteeism.

2. **Forecasting Attendance**  
   - Use predictive modeling to estimate future spikes in WFH or sick leaves, improving resource and staffing plans.

3. **Survey Integration**  
   - Combine attendance data with employee feedback to understand underlying motivations for remote work or sudden leaves.

4. **Policy Optimization**  
   - Align company policies with observed trends, possibly expanding flexible work schedules or health and wellness programs.

By leveraging the “AtliQ Presence Insights” dashboard, organizations can transform raw attendance logs into meaningful insights, ultimately cultivating a more adaptive and supportive workplace.

