# HR Dashboard using Tableau 📊🚀

## Project Overview 🌟
This repository contains a comprehensive Human Resources (HR) Dashboard built using Tableau, designed to provide HR managers with high-level insights and detailed employee records. The dashboard visualizes key HR metrics and allows filtering for in-depth analysis.📈
---
## [Dashboard Link](https://public.tableau.com/app/profile/karan.saxena2220/viz/HRDashboard_17506537511830/HRSummary)
---

![HR _ Summary](https://github.com/user-attachments/assets/1bd9e806-c564-4d23-a336-476a40d34b4a)

----

![HR  Details](https://github.com/user-attachments/assets/089e474b-2a0c-4011-9dd1-c29a9ee7334a)

## User Story 👥
A HR manager want a comprehensive dashboard to analyze human resources data, providing both summary views for high-level insights and detailed employee records for in-depth analysis. 🎯

### Summary View 📋
- **Overview** 🌐
  - Total hired, active, and terminated employees. ✅
  - Hired and terminated trends over years. 📅
  - Employee breakdown by department and job titles. 👩‍💼👨‍💼
  - HQ vs. branch comparison (New York as HQ). 🏢
  - Employee distribution by city and state. 🌍
- **Demographics** 👶👴
  - Gender ratio. ⚧️
  - Age and education level distribution. 🎓
  - Correlation between education and performance. 📊
- **Income Analysis** 💰
  - Salary comparison by education and gender. 📊
  - Age vs. salary correlation by department. 📈

### Employee Records View 📜
- Detailed list of employees with: ID, name, department, position, gender, age, education, salary. 👤
- Filterable by any column. 🔍

## Data Generation 💾
- **Dataset**: 8,950 realistic employee records generated using Python. 🐍
- **Attributes**: Employee ID, name, gender, state/city, hire date, department, job title, education, performance, overtime, salary, birth date, termination date, adjusted salary. 📋
- **Script**: `data_generation.py` uses Faker, Pandas, and NumPy for data creation. 📝
- **Output**: Saved as `HumanResources.csv`. 📄

## Python Script Details 🛠️
- **Libraries**: `pandas`, `numpy`, `faker`. 📦
- **Features**:
  - Custom probabilities for gender (46% Female, 54% Male), states, departments, and job titles. 🎲
  - Hire/termination dates with weighted probabilities (2015-2024). 📅
  - Salary ranges based on department and job title. 💸
  - Adjusted salary with education and age multipliers. 📊
- **Execution**: Run `python data_generation.py` to generate data. ▶️

## Installation & Usage 🖥️
1. Clone repo: `git clone https://github.com/yourusername/hr-dashboard.git` 🌐
2. Install dependencies: `pip install pandas numpy faker` 📦
3. Generate data: `python data_generation.py` 🚀
4. Open `HR_Dashboard.twbx` in Tableau for visualization. 🎨

## Files 📂
- `HumanResources.csv`: Generated dataset. 📊
- `HR_Dashboard.twb`: Tableau workbook. 🎨
- `data_generation.py`: Python script for data generation. 🐍
- `README.md`: This file! 📝

## Contributing 🤝
Fork the repo, make changes, and submit a PR! 💪 Feel free to add features or improve visualizations. ✨

## License 📜
MIT License - Free to use and modify! 🎉

## Acknowledgments 🙏
- Thanks to Tableau for the awesome visualization tool! 🌟
- Inspired by HR data analysis needs. 👏

Happy analyzing! 😄🚀
