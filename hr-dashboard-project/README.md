# HR Dashboard | Employee Data Analysis

## 📖 Overview
This project focuses on creating a comprehensive HR dashboard for an HR manager to analyze human resources data. The dashboard provides both **summary views** for high-level insights and **detailed employee records** for in-depth analysis.

---

## 🔑 User Story
**As an HR Manager**, I want a dashboard that provides:

1. **Summary Views**: High-level insights into employee metrics, demographics, and income analysis.
2. **Employee Records View**: Detailed employee records with necessary information and the ability to filter records.

---

## 🧠 Summary View

### 1. **Overview**
- Display the total number of hired employees, active employees, and terminated employees.
- Visualize the number of hired and terminated employees over the years.
- Breakdown of employees by department and job titles.
- Compare the total number of employees between headquarters (HQ) and branches (New York is the HQ).
- Display employee distribution by city and state.

### 2. **Demographics**
- Show the gender ratio in the company.
- Visualize the distribution of employees by age groups and education levels.
- Display the total number of employees within each age group and education level.
- Present the correlation between employees' educational backgrounds and their performance ratings.

### 3. **Income Analysis**
- Compare salaries across different education levels for both genders.
- Analyze how age correlates with the salary for employees in each department.

---

## 📝 Employee Records View
The employee records section will include the following details:
- **Employee ID**: Unique identifier for each employee.
- **First Name**: Randomly generated first name.
- **Last Name**: Randomly generated last name.
- **Gender**: Randomly selected with a 46% probability for Female and 54% for Male.
- **State and City**: Randomly assigned from a predefined list.
- **Hire Date**: Randomly generated with custom probabilities for each year from 2015 to 2024.
- **Department**: Randomly selected with specified probabilities.
- **Job Title**: Selected based on the department, with specific job title probabilities.
- **Education Level**: Determined based on the job title and pre-defined mapping.
- **Performance Rating**: Randomly selected with specified probabilities for ratings.
- **Overtime**: Randomly chosen with a 30% probability for ‘Yes’ and 70% for ‘No’.
- **Salary**: Generated based on department and job title, within specific ranges.
- **Birth Date**: Generated based on age group distribution.
- **Termination Date**: Assigned to a subset of employees with specific probabilities.
- **Adjusted Salary**: Calculated using specific gender, education level, and age multipliers.

---

## 🧑‍💻 Data Generation

### Python Script

The Python script will generate a realistic dataset of **8950 employee records**, with the following attributes:

1. **Employee ID**: A unique identifier.
2. **First Name and Last Name**: Randomly generated.
3. **Gender**: 46% Female and 54% Male.
4. **State and City**: Randomly assigned from a predefined list.
5. **Hire Date**: Random with custom probabilities.
6. **Department**: Random selection with custom probabilities for each department.
7. **Job Title**: Based on department and its specific job titles.
8. **Education Level**: Based on job title and predefined mapping.
9. **Performance Rating**: Randomly assigned.
10. **Overtime**: 30% chance for Yes, 70% for No.
11. **Salary**: Department and job title-based ranges.
12. **Birth Date**: Based on age group and job title requirements.
13. **Termination Date**: For 11.2% of the employees, assigned probabilistically.
14. **Adjusted Salary**: Calculated based on gender, education, and age.

The Python script will ensure that the data adheres to real-world scenarios for HR data analysis. The code will be structured using functions to maintain readability and clarity.

---

## 🛠️ Tools & Technologies

- **Python** for data generation and analysis
- **Pandas** for data manipulation and storage
- **Matplotlib/Seaborn** for data visualization
- **NumPy** for random data generation
- **Jupyter Notebooks** for data exploration

---

## 🚀 How to Use
1. Clone or download this repository.
2. Open the Python script `generate_hr_data.py`.
3. Run the script to generate the employee dataset with 8950 records.
4. Visualize the data using the dashboard built in Power BI/Tableau.
5. Use filters to analyze employee metrics by department, age, gender, salary, and more.

---

## 📈 Future Enhancements
- Add a detailed **employee performance analysis** based on performance ratings and salary.
- Implement a **prediction model** for employee retention or termination.
- Integrate **employee feedback** and insights into the dashboard for a complete HR analysis.
- Add **time-series analysis** for hire and termination trends over the years.

---

## 👨‍💻 Author
**Pratik Mishra**  
📊 *Aspiring Data Analyst | Python & Power BI Enthusiast | SQL Learner*  
🔗 [LinkedIn](https://github.com/Pratik1419) | [GitHub](www.linkedin.com/in/pratik-mishra-profile)

---

⭐ *If you found this project useful, don't forget to star the repository!* ⭐
