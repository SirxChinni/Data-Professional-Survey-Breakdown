
# 📊 Data Professional Survey Breakdown - Power BI Dashboard

This Power BI dashboard provides insights into a survey conducted among data professionals. The dataset includes details such as job roles, salaries, demographics, work satisfaction, and career preferences.
## 🧹 Data Cleaning
1. Removed Unnecessary Columns

- Dropped irrelevant fields (e.g., ID fields, redundant information).

2. Converted Salary Ranges to Numeric Values

- The dataset had salary ranges (e.g., 100k - 150k).
- Standardized salaries by calculating the average of the lower and upper bounds (e.g., 125k).

3. Grouped Less Common Categories

- Columns such as Job Title, Favorite Programming Language, Country, and Industry contained too many unique values.
- Kept the most common categories and grouped the remaining ones under **Other** for better visualization.

4. Formatted Data Types

- Converted salary and age fields to numerical values.
- Ensured categorical variables were correctly formatted.
## 📊 Key Visualizations & Insights
1. **Average Salary by Job Title** 
- Displays salary variations across different job roles.
2. **Career Switch vs. Average Salary** 
- Analyzes salary differences between professionals who switched careers and those who didn't.
3. **Employee Satisfaction** 
- Insights on how satisfied employees are with salary, work-life balance, and colleagues.
4. **Average Salary by Industry** 
- Compares salaries across different sectors.
5. **Favorite Programming Languages** 
- Identifies the most preferred programming languages for each job title.
6. **Job Change Priorities** 
- Shows the most important factors (e.g., salary, remote work) when considering a job switch.
7. **Average Salary by Gender** 
- Highlights salary differences based on gender.
## 📷 Dashboard Preview
![Image](https://github.com/user-attachments/assets/755f5638-93e2-4607-bb92-002b1c7e903c)
