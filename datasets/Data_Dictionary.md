# KashmirTech Solutions — Data Dictionary

**Company:** KashmirTech Solutions (Fictional)
**Employees:** 500
**Industry:** Technology / Services
**Purpose:** Used throughout the HR Analytics course for all exercises, descriptive analytics, diagnostic analytics, and predictive analytics.

---

| Variable | Type | Values | Description |
|----------|------|--------|-------------|
| Employee_ID | Text | E001–E500 | Unique employee identifier |
| Age | Numeric | 25–48 | Employee age in years |
| Gender | Categorical | Male, Female | Employee gender |
| Department | Categorical | Sales, IT, HR, Finance, Operations | Department the employee belongs to |
| Job_Level | Categorical | Junior, Mid, Senior, Manager | Seniority level within the organization |
| Salary | Numeric | 34000–112000 | Annual salary in Indian Rupees (INR) |
| Years_at_Company | Numeric | 0.6–14.5 | Number of years employed at KashmirTech |
| Performance_Rating | Numeric (1–5) | 2, 3, 4, 5 | Annual performance rating (1=Poor, 5=Excellent) |
| Training_Hours | Numeric | 8–40 | Total training hours received in the past year |
| Job_Satisfaction | Numeric (1–5) | 2, 3, 4, 5 | Self-reported job satisfaction score (1=Very Low, 5=Very High) |
| Overtime | Categorical | Yes, No | Whether the employee regularly works overtime |
| Manager_Rating | Numeric (1–5) | 2, 3, 4, 5 | Manager's rating of the employee (1=Poor, 5=Excellent) |
| Promoted_Last_2_Years | Categorical | Yes, No | Whether the employee was promoted in the last 2 years |
| Attrition | Categorical | Yes, No | Whether the employee has left the company (target variable) |

---

## Key Patterns in the Dataset

These patterns are intentionally built in for teaching purposes:

1. **Junior employees in Sales with Overtime=Yes** have the highest attrition
2. **IT Senior and Manager employees** have the lowest attrition
3. **Low Job_Satisfaction (2) correlates strongly with Attrition=Yes**
4. **Employees with Years_at_Company < 2** are at higher attrition risk
5. **Higher Training_Hours correlates with lower attrition**
6. **Manager_Rating of 2 is associated with higher attrition**

---

## How to Use This Dataset

| Lecture | What to Calculate |
|---------|------------------|
| Lecture 2 | Attrition rate, avg salary, dept headcount |
| Lecture 3 | Descriptive stats — mean, median, distribution by dept |
| Lecture 4 | Diagnostic — why is Sales attrition high? |
| Lecture 5 | Workforce planning — forecast headcount needs |
| Lecture 6 | Predictive — which employees are likely to leave? |
