
---

# Steps Data Analysis: Comparing Physical Activity with School Periods

---

## Project Description

This project explores the relationship between my daily step counts, recorded via Apple Health, and different periods of my academic life (e.g., school terms, exam period, and vacations). By analyzing step data over three years, I aim to identify trends in physical activity and how it correlates with my acadamic period.

---

## Motivation

The motivation for this project stems from a curiosity to better understand how my physical activity patterns fluctuate during school-related activities. Specifically:
- Do I walk less during exam periods due to stress and time constraints?
- Are vacations associated with higher physical activity due to more free time?
- Do my physical activity in free time is enough or not? for a person to live a healthy life according to averages?

This project serves as a reflection on my lifestyle habits and encourages better health and time management during intense academic periods.

---

## Data Source

- **Step Data**: Collected from Apple Health, which automatically tracks daily step counts via my iPhone.
- **School Calendar**: The dataset was manually created based on official school term dates, exam schedules, and vacation periods.

---

## Data Analysis

### Techniques and Steps:

1. **Data Preprocessing**:
   - Cleaned and formatted Apple Health step data into a structured CSV file.
   - Created a school calendar dataset with columns for `Start Date`, `End Date`, and `Period Type` (e.g., "Term," "Exam Week," "Vacation").
   - Merged the step data with school periods based on matching dates.

2. **Exploratory Data Analysis (EDA)**:
   - Calculated average daily steps for each period.
   - Compared weekday vs. weekend step counts within school terms.
   - Identified step trends over three years using line plots.

3. **Visualization**:
   - Created bar charts to compare average steps during "Term," "Vacation," and "Exam Week."
   - Developed line graphs to visualize step fluctuations over time.

4. **Statistical Analysis**:
   - Performed t-tests to check for significant differences in step counts between periods (e.g., "Exam Week" vs. "Vacation").
   - Analyzed the distribution of step counts using a plotting technique.

---

## Findings

- **Exam Periods**: Step counts significantly decreased during exam weeks, likely due to time spent studying and reduced physical activity.
- **Vacation Periods**: Step counts were highest, reflecting more leisure time and opportunities for outdoor activities.
- **Weekday vs. Weekend**: Step counts were consistently higher on weekends, even during school terms, indicating increased free time and relaxation.
- **Yearly Trends**: Over three years, my overall step count increased, showing a growing awareness of staying active.

---

## Limitations and Future Work

### Limitations:
1. **Data Gaps**: Some times in a day had missing step data due to technical issues or not carrying my phone for example while actively playing sports, since I can not carry my phone with me in those times I do not have the data of those times..
2. **Bias**: Step data may not fully represent physical activity levels, as other activities (e.g., cycling or gym workouts) are not tracked.
3. **Generalizability**: Findings are personal and may not apply to others.

### Future Work:
1. **Incorporate Additional Data**:
   - Track other health metrics like heart rate, sleep data, and stress levels to gain a more comprehensive view of my well-being.
2. **Automation**:
   - Use Python to automate data cleaning, analysis, and visualization for more efficient updates.
3. **Comparison with Peers**:
   - Collect similar data from friends or family to see if trends are consistent.
4. **Behavioral Changes**:
   - Use the insights gained to create healthier habits, such as planning regular walks during exam weeks or playing active sporgts during exam weeks or school periods.

---

## How to Use This Repository

1. **Data Files**:
   - `steps_data.csv`: Contains daily step counts from Apple Health.
   - `school_calendar.csv`: Contains school periods with start and end dates.

2. **Scripts**:
   - `data_analysis.py`: Python script to preprocess, analyze, and visualize the data.

3. **Visualizations**:
   - Charts and graphs summarizing key insights.

---

