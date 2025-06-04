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

## 📂 Data 

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

- **Self-Reported Bias**: Users may misestimate stress/productivity
- **Correlation ≠ Causation**: Observational analysis; experimental validation needed
- **Static Snapshot**: One-time survey; behaviors may evolve
- **No Platform Split**: Does not distinguish social media platforms

---

## 🔭 Future Work

- **Longitudinal Tracking**: Study users over time to observe changes
- **Behavioral Clustering**: Use ML to identify patterns like *Focus Fanatics*, *Doomscrollers*
- **Qualitative Interviews**: Explore deeper reasons behind behaviors
- **Wider Demographics**: Include mental health, income, and family background

---

## 🧪 Testing & Reproducibility

1. Download this GitHub repository or `.zip` it
2. Open `Social_Media_Productivity_Report_Final.pbix` in Power BI Desktop
3. Interact with dashboards using slicers, filters, and drilldowns

---

  ## 📁 Project Structure
```
/The-Scroll-Trap
│
├── data/
│   └── social_media_vs_productivity.csv
│
├── images/
│   ├── overview.png
│   ├── Detailed Findings.png
│   └── Advanced Analytics.png
│
├── The Scroll Trap.pbix
├── README.md
└── LICENSE
```

---

## 📈 Dashboard Visuals

### 🎯 Overview  
![overview](https://github.com/katlakavyasri/The-Scroll-Trap-Social-Media-Productivity/blob/main/images/overview.png)

### 🔎 Detailed Findings  
![Detailed Findings](https://github.com/katlakavyasri/The-Scroll-Trap-Social-Media-Productivity/blob/main/images/Detailed%20Findings.png)

### 📊 Advanced Analytics  
![Advanced Analytics](https://github.com/katlakavyasri/The-Scroll-Trap-Social-Media-Productivity/blob/main/images/Advanced%20Analytics.png)

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
