# Data-Analyst-Intern-role-at-Zylentrix.
# 📊 Zylentrix Online Learning Platform - User Engagement Analysis

## 📁 Project Overview

This project focuses on analyzing user engagement and behavior across various cohorts, courses, and demographics for **Zylentrix**, an online learning platform offering tracks like Python, Digital Marketing, UI/UX, etc.

As a Data Analyst Intern, the goal was to clean, process, and extract insights from student activity and feedback data to help the platform improve its engagement, course effectiveness, and overall user satisfaction.

---

## 📂 Datasets Used

1. **students.csv**
   - Contains student information: `Student_ID`, `Name`, `Age`, `Gender`, `Location`, `Enrolment_Date`

2. **course_activity.csv**
   - Logs user interactions: `Student_ID`, `Course_ID`, `Date`, `Time_Spent_Minutes`, `Completion_Percentage`

3. **feedback.csv**
   - Feedback given by students: `Student_ID`, `Course_ID`, `Rating (1-5)`, `Feedback_Text`

---

## 🛠️ Tasks Performed

### 1. Data Cleaning & Preparation
- Handled missing and duplicate records
- Converted date and numeric fields to appropriate types
- Created additional columns such as **Cohort** (based on `Enrolment_Date`)

### 2. Descriptive Analysis
- Calculated average time spent, completion rates, and feedback scores
- Analyzed user behavior by:
  - Age
  - Gender
  - Location
  - Cohort
  - Course

### 3. Insights & Visualizations
- Used `matplotlib` and `seaborn` to create:
  - Bar charts (average completion by age, gender, location)
  - Line chart (cohort performance over time)
  - Rating trends by age and course
- Rounded numerical values for readability
- Translated data outputs into meaningful sentences for easy understanding

### 4. Advanced Analysis
- Merged activity and feedback to analyze:
  - Correlation between **completion percentage** and **ratings**
  - Identified **top-performing students** based on time spent, completion %, and ratings

---

## 📈 Key Insights

- **Top Age Groups by Rating**: Students aged 22–28 tend to give the highest average ratings.
- **Top Courses by Completion**: Certain courses consistently show higher completion percentages, indicating better engagement.
- **Cohort Trends**: Newer cohorts show varying performance, helping track the impact of platform or content changes.
- **Top Students**: Identified top 3 students based on high time spent, high completion %, and excellent feedback.
- **Gender & Location Analysis**: Engagement levels vary by demographic, offering opportunities for personalized targeting.

---

## 📌 Why It Matters

Analyzing user engagement at this depth helps Zylentrix:
- Personalize the learning experience
- Improve course content and structure
- Identify high-performing user segments
- Optimize marketing and onboarding strategies
- Make data-driven business decisions

---

## 📚 Tools & Libraries Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 👨‍💻 Author

**Shivani whachal**  
Data Analyst Intern  
Email: shivaniwac@gmail.com 

---

