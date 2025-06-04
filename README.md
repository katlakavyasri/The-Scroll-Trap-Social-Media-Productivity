# 📘 The Scroll Trap: Exploring the Interplay Between Social Media, Productivity, and Well-being (Power BI Project)

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🚀 Project Overview

This Power BI project dives into a behavioral dataset to examine how daily social media habits affect productivity, stress levels, and digital well-being. Through visual storytelling and data modeling, the goal is to empower individuals and organizations to better understand digital fatigue and foster mindful digital usage.

---

## 📊 Quick Summary

| 📁 Category       | 📌 Details                                          |
|------------------|-----------------------------------------------------|
| 📊 Dataset        | 30,000 simulated user entries                       |
| 🎯 Focus Areas    | Productivity, Screen Time, Stress, Lifestyle        |
| 📈 Visuals Used   | Decomposition Tree, Key Influencers, Correlation Matrix, DAX KPIs |
| 🛠 Tools          | Power BI, Power Query, DAX, GitHub                  |

---

## 📂 Data Source

- The dataset is a realistic simulation derived from survey responses of 30,000 users on factors such as screen time, productivity scores, notifications, coffee intake, and stress.
- *The raw dataset, `social_media_vs_productivity.csv`, is available in the `/data` folder within this repository.*

---

## 🛠️ Tools & Technologies

| Tool             | Purpose                                              |
|------------------|------------------------------------------------------|
| Power BI Desktop | Data modeling, DAX measures, interactive dashboards  |
| Power Query      | Data transformation, column renaming, filtering      |
| DAX              | Custom metrics like Productivity Gap, Stress Categories |
| Excel (Optional) | Data sanity checks                                   |
| GitHub           | Project versioning and sharing                       |

---

## 🔍 Key Insights

### 1. 📉 **Social Media Impacts**
- Negative correlation between `daily_social_media_time` and `actual_productivity_score`.
- Higher screen time → higher stress levels.
- Males peak in stress at ~30 notifications/day.
- Females at moderate stress use phones more before sleep.

### 2. 🧠 **Productivity Gap by Age**
- Ages **25–34** and **35–44** often overestimate their productivity (based on gap between perceived and actual scores).

### 3. 📊 **Demographic Behavior Patterns**
- Lowest sleep in **18–24** and **45–54** groups.
- Coffee positively correlates with productivity in males.
- Violin plots show wide usage variance in younger groups.

### 4. 🌱 **Lifestyle and Digital Hygiene**
- `breaks_during_work`, `focus_apps`, and `sleep_hours` → improve productivity & reduce stress.
- `number_of_notifications` → consistent stress booster.
- **Decomposition Tree** pinpoints low- and high-performing segments by job, age, and gender.

---

## ✅ Recommendations

### 🔐 Promote Healthy Digital Boundaries
- **Individuals**: Use app timers, reduce notification clutter, sleep hygiene.
- **Organizations**: Normalize focus hours and encourage midday breaks.

### 🌙 Improve Sleep & Self-Awareness
- Create workshops targeting groups with poor sleep (e.g., **18–24**, **45–54**).
- Address illusion of productivity in **25–44** through self-assessment tools.

### 📈 Leverage Positive Drivers
- Promote **focus apps**, **break routines**, and mindful caffeine use.
- Customize interventions for age and job cohorts.

### 🎯 Build Smart Platforms
- Offer **customizable notifications**, **personal usage insights**, and **wellness nudges**.

---

## 👥 Who Can Use This?

- **Students & Professionals**: Reflect on your own digital habits.
- **HR & Wellness Teams**: Build awareness campaigns.
- **UX Designers & Developers**: Understand real-world behavior metrics.
- **Researchers**: Base for extended behavioral studies.

---

## ⚠️ Limitations

- **Self-Reported Bias**: Users may misestimate stress or productivity.
- **Correlation ≠ Causation**: Observational analysis; needs further experiments.
- **Static Snapshot**: One-time survey; behaviors can evolve.
- **Lacks Platform Split**: Social media isn't broken down by app (e.g., Instagram, LinkedIn).

---

## 🔭 Future Work

- **Longitudinal Tracking**: Study users over months to see shifts in stress/productivity.
- **Behavioral Clustering**: Use ML to segment users as *Focus Fanatics*, *Doomscrollers*, etc.
- **Qualitative Interviews**: Understand root psychological reasons.
- **Wider Demographics**: Add mental health, income level, family environment for richer segmentation.

---

## 🧪 Testing & Reproducibility

1. Download this GitHub repository or `.zip` it.
2. Open `Social_Media_Productivity_Report_Final.pbix` in Power BI Desktop.
3. Explore the dashboards interactively using slicers, filters, and visual-level drilldowns.
---
## 📁 Project Structure

/The-Scroll-Trap
│
├── data/
│   └── social_media_vs_productivity.csv
│
├── images/
│   ├── page1_overview.png
│   ├── page2_key_findings.png
│   ├── page3_advanced_insights.png
│   └── dashboard_demo.gif
│
├── Social_Media_Productivity_Report_Final.pbix
├── README.md
└── LICENSE
---

## 📈 Dashboard Visuals

### 🎯 Executive Dashboard
![Dashboard Overview](images/page1_overview.png)

### 🔎 Key Findings
![Key Findings](images/page2_key_findings.png)

### 📊 Advanced Visuals
![AI Visuals](images/page3_advanced_insights.png)

### 🎥 Dashboard Interaction (GIF Demo)
![Dashboard Interaction](images/dashboard_demo.gif)

---

## 🔗 Live Demo

- 📹 YouTube walkthrough: *(Add link if available)*
- 🌐 Power BI Service: *(Add published link if public)*

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, or share with proper credit.

---

## 🙏 Acknowledgments

- Simulated data inspired by Kaggle's behavioral datasets.
- Power BI visuals designed using best practices from Microsoft and the PowerBI community.
- Thanks to wellness researchers and digital behavior psychologists whose insights guided the storytelling.

---

## 💬 Contact

For collaborations or questions, reach out:

[![Connect on LinkedIn](https://img.shields.io/badge/Kavya%20Sri%20Katla-LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/katlakavyasri)  
[GitHub Portfolio](https://github.com/katlakavyasri)
