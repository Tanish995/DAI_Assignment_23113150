# DAI_Assignment_23113150
Detailed Analysis Report

1.Overview of the Dataset

The dataset contains records of 1,000 employees across multiple departments. The key attributes include:
- Age (years)
- Salary (annual income in dollars)
- Joining Date
- Department
- Performance Score (1 to 5 scale)

2.Data Quality Check

- Missing Values: 55 entries in the Performance Score column are missing.
- Duplicates: No duplicate records found.
- Data Types: Age and Salary are numeric, while other fields are categorical.

3.Key Statistical Insights

- Age: Employees range from 20 to 59 years; the average age is ~40 years.
- Salary: Salaries vary between $30,028 and $149,922, with a median of $91,750.
- Performance Scores: The average score is 2.84, with most employees scoring between 2 and 4.

4.Visual Analysis & Findings

Age Distribution
- The majority of employees are between 30 and 50 years old.
- There are fewer employees in the younger (20-30) and older (50-59) age groups.
- The distribution follows a normal trend, peaking around the 45-year mark.

Salary vs. Performance Score
- The density plot indicates no strong correlation between salary and performance scores.
- Some high earners (above $120,000) have low performance scores (1 or 2), suggesting salary is not solely based on performance.
- Conversely, some low earners (below $50,000) have high performance scores (4 or 5), hinting at potential disparities in salary distribution.

Performance Score Distribution
- The most common performance scores are 2, 3, and 4.
- Only a small percentage of employees have exceptionally high (5) or low (1) ratings.
- This distribution suggests a majority of employees perform at an average level, with fewer extremes.

Department-wise Salary Trends
- The bargraph reveals considerable salary variation across departments.
- Some departments, likely Marketing and Finance, have higher median salaries.
- Other departments, such as Sales or HR, show lower salary ranges.
- Salary discrepancies could indicate differences in job roles, experience levels, or company priorities.

5.Recommendations & Next Steps

Handling Missing Performance Scores: Fill missing values with the average score ~3 or use predictive modeling to estimate based on other attributes.

Further Analysis:
- Investigate department-wise performance trends to see if certain departments perform better than others.
- Analyze whether longer tenure correlates with higher salaries or better performance.

Performance Improvement Initiatives:
- Identify key drivers of low and high performance to develop targeted employee development programs.
- Assess whether salary adjustments are needed for high performers in low-paying departments.

This analysis provides a strong foundation for workforce insights and decision-making, helping to optimize salary structures and performance evaluation methods.
