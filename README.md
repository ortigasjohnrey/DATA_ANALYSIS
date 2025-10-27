# 📱 User Engagement and App Usage Patterns Across Different Demographics

**Authors:**  
- Mel Christian Aniban  
- John Rey Ortigas  
**Program:** BSCS 3-B  
📅 **Date:** December 27, 2024  

---

## 🧾 EXECUTIVE SUMMARY

The analysis explores a dataset containing detailed information on **mobile app usage**, **daily screen time**, and **lifestyle patterns** across different demographics, including age groups, genders, and geographic locations.  
The dataset provides insights into how app usage habits, screen time, and age-specific preferences influence digital engagement.  

This study offers a foundational basis for developing strategies to manage screen time, optimize app engagement, and promote healthier digital habits while contributing to a broader understanding of the interplay between technology use and lifestyle.

### 🔍 Key Findings
- Younger age groups, particularly **teens and adolescents**, exhibit the highest daily screen time, averaging nearly **10 hours per day**.  
- Gender-specific trends indicate that both males and females dedicate similar time to mobile apps, with slight variations in category preference.  
- Teens and adolescents prioritize **social media and gaming apps**, while middle-aged adults lean more towards **productivity tools**.  
- Geographical differences play a role, with locations like **Phoenix** and **Los Angeles** displaying higher app engagement compared to other cities.  

The findings underscore the importance of balancing screen time and app usage to promote overall well-being. Excessive screen time among younger demographics suggests a need for targeted interventions to encourage healthier digital practices.  

### 💡 Recommendations
- Promote **digital literacy programs** and awareness campaigns to manage screen exposure.  
- Encourage app developers to integrate **screen time management features**.  
- Tailor app experiences for diverse age groups and regions.  
- Support research-based initiatives to improve **digital well-being** and promote balanced lifestyles across populations.  

---

## 🧭 INTRODUCTION

### 🎯 Objectives
- To analyze daily screen time across different age groups and identify behavioral trends.  
- To explore app usage patterns based on gender and examine differences in time spent on various app categories.  
- To evaluate app usage across different age groups focusing on social media, gaming, and productivity apps.  
- To assess app usage by location to uncover potential geographic trends in mobile behavior.  

### 🗂️ Data Source
**Dataset:** Smartphone Usage and Behavioral Dataset  
**Platform:** [Dataset](https://github.com/ortigasjohnrey/DATA_ANALYSIS/blob/main/Case-Study-Final/mobile_usage_behavioral_analysis.csv)  

This dataset contains detailed information about smartphone app usage, daily screen time, and behavioral patterns across age, gender, and geographic locations. It offers a robust foundation for analyzing trends in digital behavior and lifestyle.  

### 🌍 Relevance
The dataset is highly relevant for:
- **App developers:** to improve engagement through user insights.  
- **Educators and policymakers:** to promote digital balance and responsible technology use.  
- **Healthcare professionals:** to address mental and physical health effects of excessive screen time.  

---

## 📊 DATASET OVERVIEW

**Dataset Name:** Smartphone Usage and Behavioral Dataset  
**Description:** Daily mobile usage patterns of 1,000 users, covering screen time, app usage, user engagement across categories, and user location.

### 📋 Structure
- **Rows:** 1,000 users  
- **Columns:** 12 attributes  

| Column Name | Description | Example |
|--------------|-------------|----------|
| User_id | Unique identifier for each user | 3 |
| Age | User’s age in years | 32 |
| Gender | Male / Female | Female |
| Total_mobile_app_usage_hours | Total hours spent on apps daily | 9.12 |
| Daily_screen_time_hours | Total daily screen usage | 9.12 |
| Number_of_apps_used | Count of distinct apps used daily | 11 |
| Social_media_usage_hours | Time spent on social apps | 4.58 |
| Productivity_app_usage_hours | Time on productivity/work tools | 1.71 |
| Gaming_app_usage_hours | Time on games | 2.83 |
| Other_act_in_using_mobile | Time for other mobile activities | 0.00 |
| Location | City of residence | Houston |
| Age_group | User’s age category | Young Adults |

---

## ⚙️ METHODOLOGY

### 🧩 Step 1: Data Acquisition
- Downloaded dataset (CSV format) from Kaggle.  
- Imported dataset and essential libraries for processing and analysis.  

### 🧹 Step 2: Data Cleaning
- Checked for **missing values** and **duplicates** to ensure data integrity.  
- Standardized column names for uniformity.  
- Calculated total mobile app usage and ensured it aligned with the sum of app category usage.  
- Derived remaining time spent on mobile outside defined categories.  
- Grouped users into **age-based categories**.  
- Removed unnecessary columns.  

### 📈 Step 3: Data Analysis
- Analyzed average **screen time per age group**.  
- Analyzed average **app usage by gender**.  
- Compared app usage across **age groups**.  
- Examined **app usage by location**.  

### 📉 Step 4: Data Visualization
- Bar chart: Daily screen time across age groups.  
- Grouped bar charts:  
  - App category usage by gender.  
  - App usage by age group.  
  - App usage by location.  

---

## 📊 RESULTS AND ANALYSIS

### 🔑 Key Findings
1. **Daily Screen Time:** Teens and adolescents have the highest daily screen time, while middle-aged adults spend the least.  
2. **Gender-Based Usage:** Females predominantly use social media; males prefer productivity apps.  
3. **App Usage by Age Group:** Teens focus most on social media and gaming; adults lead in productivity.  
4. **Geographic Trends:**  
   - Productivity app usage peaks in **Phoenix** and **New York**.  
   - Social media usage is highest in **Houston**.  
   - Gaming dominates in **Chicago**.  

### 📊 Visualizations
1. **Bar Graph:** Daily Screen Time Across Age Groups  
2. **Grouped Bar Graph:** App Category Usage by Gender  
3. **Grouped Bar Graph:** Social Media, Gaming, and Productivity Apps by Age Group  
4. **Grouped Bar Graph:** App Usage by Location and Category  

---

## 💡 INSIGHTS AND RECOMMENDATIONS

### 📍 Insights
- Teens and adolescents show the highest screen engagement.  
- Middle-aged adults use fewer mobile apps, prioritizing offline activities.  
- Females focus on social media and networking; males engage more with productivity tools.  
- Younger users prefer entertainment; adults emphasize professional use.  
- Regional data show professional-oriented users in **Phoenix** and **New York**, high social media activity in **Houston**, and strong gaming culture in **Chicago**.  

### 🧭 Recommendations
- Add **gamification** and **interactive features** in social and gaming apps for younger users.  
- Introduce **parental controls** and **screen reminders** to reduce digital fatigue.  
- Develop **fitness, finance, and productivity apps** to increase healthy engagement.  
- Localize app campaigns:  
  - **Phoenix/New York:** Focus on productivity.  
  - **Houston:** Strengthen social media marketing.  
  - **Chicago:** Support gaming and entertainment partnerships.  
- Blend features across categories (e.g., productivity + social sharing).  

---

## 🧠 CONCLUSION

This case study followed a structured approach—from **data acquisition** to **cleaning**, **analysis**, and **visualization**—to identify meaningful behavioral patterns in mobile app usage.  

Key findings show demographic and geographic distinctions in app engagement, providing actionable insights for developers, researchers, and policymakers.  

By integrating strong methodology and clear visualization, the study highlights how digital engagement varies across populations and how targeted strategies can enhance well-being and digital literacy.

---

## ⚠️ CHALLENGES

- Limited data for **Children** and **Elderly** groups.  
- Absence of external factors (e.g., **occupation**, **culture**) may affect interpretation accuracy.  
- Required advanced proficiency in Python visualization libraries.  

---

## 💭 REFLECTION

Creating this case study was both challenging and rewarding.  
Difficulties included maintaining documentation accuracy, mastering Python’s analytical libraries, and selecting appropriate datasets.  
However, these challenges strengthened:
- **Analytical and problem-solving skills**  
- **Critical thinking**  
- **Real-world data handling experience**  

This process reinforced persistence, adaptability, and attention to detail—core traits in effective data analysis.

---

**End of Document**  
© 2025 John Rey Ortigas & Mel Christian Aniban — BSCS 3-B
