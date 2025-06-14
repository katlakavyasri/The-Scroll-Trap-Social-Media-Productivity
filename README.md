# 📘 The Scroll Trap: Exploring the Interplay Between Social Media, Productivity, and Well-being (Power BI Project)

[![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)](https://powerbi.microsoft.com/)
[![Tableau](https://img.shields.io/badge/Tableau-Storytelling-blue)](https://www.tableau.com/)
[![Status](https://img.shields.io/badge/Project-Completed-brightgreen)](https://github.com/katlakavyasri/The-Scroll-Trap-Social-Media-Productivity)
[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/licenses/MIT)


---

## 🚀 Project Overview

This Power BI project dives into a behavioral dataset to examine how daily social media habits affect productivity, stress levels, and digital well-being. Through visual storytelling and data modeling, the goal is to empower individuals and organizations to better understand digital fatigue and foster mindful digital usage.

---

## 📊 Dataset Summary

| Metric                     | Description                                        |
|----------------------------|----------------------------------------------------|
| 🧠 Users                   | 30,000 simulated survey responses                  |
| 📱 Variables               | Screen time, stress levels, notifications, sleep   |
| 🎯 Targets                 | Productivity score (actual vs perceived), wellness |
| 🧹 Cleaned File            | `cleaned_social_media_productivity_data.csv`       |


---

## 📂 Data 

- The dataset is a realistic simulation derived from survey responses of 30,000 users on factors such as screen time, productivity scores, notifications, coffee intake, and stress.
- *The raw dataset, `social_media_vs_productivity.csv`, is available in the `/data` folder within this repository.*

---

## 🛠️ Tools Used

| Tool      | Purpose                            |
|-----------|------------------------------------|
| Power BI  | DAX modeling, advanced analytics    |
| Tableau   | Visual storytelling & interactivity |
| GitHub    | Version control, documentation      |
| Excel     | Initial data checks (optional)      |

---

## 🔍 Key Insights

### 1. 📉 **Social Media Impacts**
- Negative correlation between `daily_social_media_time` and `actual_productivity_score`
- Higher screen time → higher stress levels
- Males peak in stress at ~30 notifications/day
- Females at moderate stress use phones more before sleep

### 2. 🧠 **Productivity Gap by Age**
- Ages **25–34** and **35–44** often overestimate their productivity (based on gap between perceived and actual scores)

### 3. 📊 **Demographic Behavior Patterns**
- Lowest sleep in **18–24** and **45–54** groups
- Coffee positively correlates with productivity in males
- Violin plots show wide usage variance in younger groups

### 4. 🌱 **Lifestyle and Digital Hygiene**
- `breaks_during_work`, `focus_apps`, and `sleep_hours` improve productivity & reduce stress
- `number_of_notifications` → consistent stress booster
- **Decomposition Tree** pinpoints high- and low-performing segments by job, age, and gender

---

## ✅ Recommendations

### 🔐 Promote Healthy Digital Boundaries
- **Individuals**: Use app timers, reduce notification clutter, and practice sleep hygiene  
- **Organizations**: Normalize focus hours and encourage midday breaks

### 🌙 Improve Sleep & Self-Awareness
- Create workshops targeting groups with poor sleep (e.g., **18–24**, **45–54**)
- Address illusion of productivity in **25–44** through self-assessment tools

### 📈 Leverage Positive Drivers
- Promote **focus apps**, **break routines**, and mindful caffeine use
- Customize interventions for age and job cohorts

### 🎯 Build Smart Platforms
- Offer **customizable notifications**, **personal usage insights**, and **wellness nudges**

---

## 👥 Who Can Use This?

- **Students & Professionals**: Reflect on your digital habits
- **HR & Wellness Teams**: Design awareness campaigns
- **UX Designers & Developers**: Understand user behaviors
- **Researchers**: Use as a base for extended behavioral studies

---

## ⚠️ Limitations

- **📏Self-Reported Bias**: Users may misestimate stress/productivity
- **⚖️Correlation ≠ Causation**: Observational analysis; experimental validation needed
- **⏱️Static Snapshot**: One-time survey; behaviors may evolve
- **🌐No Platform Split**: Does not distinguish social media platforms

---

## 🔭 Future Work

- **🧬 Behavioral Clustering**: (e.g., Focus Fanatics vs Doomscrollers)
- **🧪Longitudinal Tracking**: Study users over time to observe changes
- **📉Behavioral Clustering**: Use ML to identify patterns like *Focus Fanatics*, *Doomscrollers*
- **🎙️Qualitative Interviews**: Explore deeper reasons behind behaviors
- **🧠Wider Demographics**: Include mental health, income, and family background

---

## 🧪 Testing & Reproducibility

1. Download this GitHub repository or `.zip` it
2. Open `Social_Media_Productivity_Report_Final.pbix` in Power BI Desktop
3. open 'Scroll Trap.twb' in Tableau
4. Interact with dashboards using slicers, filters, and drilldowns

---

  ## 📁 Project Structure
```
/The-Scroll-Trap
│
├── data/
│   └── social_media_vs_productivity.csv
    └── cleaned_social_media_productivity_data
│
├── images/
│   ├── Overview.png
│   ├── Detailed Findings.png
│   └── Advanced Analytics.png
│
├── Social_Media_Productivity_Report_Final.pbix
├── Scroll Trap.pbix
├── README.md
└── LICENSE
```

---

## 📈 Visualizations

### 🔸 Power BI (Advanced)
- ✅ Decomposition Tree
- ✅ Key Influencers
- ✅ DAX-driven Productivity Gap
- ✅ Stress Category Distribution

📁 Download Tableau File: [`Scroll Trap.pbix`](https://github.com/katlakavyasri/The-Scroll-Trap-Social-Media-Productivity/blob/main/Social_Media_Productivity_Report_Final.pbix)


### 🔹 Tableau (Storytelling)
- 🟢 **Scatter Plot**: Social Media Time vs Productivity
- 🟢 **Bar Chart**: Productivity Gap by Platform
- 🟢 **Box Plot**: Social Media Time by Age Group

📁 Download Tableau File: [`Scroll Trap.twb`](https://github.com/katlakavyasri/The-Scroll-Trap-Social-Media-Productivity/blob/main/Scroll%20Trap.twb)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, or share with proper credit.

---

## 🙏 Acknowledgments

- Simulated data inspired by Kaggle's behavioral datasets  
- Power BI visuals designed using best practices from Microsoft  
- Thanks to wellness researchers and behavioral scientists who inspired the insights

---

## 💬 Contact

For collaborations or questions, reach out:

[![Connect on LinkedIn](https://img.shields.io/badge/Kavya%20Sri%20Katla-LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/kavya-sri-katla/)  
[GitHub Portfolio](https://github.com/katlakavyasri)
