# 🏥 HealthConnect Clinic: Patient No-Show Analytics

## 📌 Project Overview
This project involves the end-to-end development of an interactive executive dashboard in Power BI to analyze patient appointment data for HealthConnect Clinic. The primary objective is to uncover the root causes of patient no-shows, evaluate operational bottlenecks, and provide data-driven recommendations to optimize scheduling and clinic revenue.

## 📁 Repository Files
* **[Power BI Dashboard File](HealthConnect_Initial_Dashboard.pbix)** - The interactive `.pbix` file containing the data model, DAX measures, and visualizations.
* **[Executive Analytics Report](HealthConnect_Analytics_Report.pdf)** - The formal written report detailing data prep, EDA, and strategic recommendations.
* **[Dashboard Screenshot](HealthConnect%20Executive%20DashBoard.png)** - High-resolution image of the final UI.

## 🛠️ Tools & Technologies Used
* **Power BI:** Data visualization, interactive dashboard design, and DAX calculations.
* **Power Query:** Data cleaning, type standardization, and missing value imputation.
* **Exploratory Data Analysis (EDA):** Trend identification across demographics and logistical variables.

## 📊 The Dashboard
![HealthConnect Dashboard](HealthConnect%20Executive%20DashBoard.png)

## 🧮 Key Performance Indicators (KPIs)
* **Total Appointments:** 5,000 scheduled visits.
* **Total No-Shows:** 2,423 missed appointments (a critical ~48.5% no-show rate).
* **Average Lead Time:** 29.64 days across all bookings.

## 💡 Key Business Insights
1. **The Lead Time Danger Zone:** There is a direct correlation between advanced booking lead times and attendance rates. Patients who successfully attend appointments book ~24 days in advance, while no-shows book significantly further out (~34 days in advance).
2. **Reminder Channel Gaps:** Despite utilizing SMS and WhatsApp, a significant portion of patients receive no reminders (the "None" category), which correlates with missed appointments.
3. **Demographic Variances:** Interactive slicing reveals distinct attendance behaviors across age brackets, indicating that a one-size-fits-all communication strategy is inefficient.
4. **Logistical Baselines:** The median distance to the clinic (8.7 km) and average wait time (24 minutes) establish operational baselines to monitor for patient churn.

## 🚀 Strategic Recommendations
* **Targeted Interventions:** Implement automated "check-in" systems for appointments booked >25 days in advance, requiring mandatory confirmation one week prior to the slot.
* **Optimize Reminder Systems:** Eliminate the "None" reminder category and mandate SMS or WhatsApp confirmations for all bookings to increase engagement.
* **Dynamic Overbooking:** Given the predictable ~48% no-show rate, the clinic can safely test a calculated overbooking strategy for high-risk time blocks to maximize physician capacity without overcrowding the waiting room.

## 📂 Data Preparation & Limitations
* Missing numerical values (distance and wait time) were imputed using median values to prevent extreme outliers from skewing the dataset.
* **Limitations:** The dataset does not account for external variables (e.g., severe weather, localized traffic, acute health changes) or socioeconomic contexts (e.g., transportation barriers) that may heavily influence daily attendance.
