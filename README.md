# Project Title
**UK Poverty and Inequality Trends (1969 - 2017): Insights from the World Bank PIP Dataset**
<img width="397" height="102" alt="image" src="https://github.com/user-attachments/assets/418ce46c-cf9a-4be5-b7ef-1293b7976da0" />oject-teresa

## Table of Contents UPDATE
  


## **About the Project**
This project analyzes poverty and inequality trends in the United Kingdom between 1967 and 2017 using data from the World Bank’s Poverty and Inequality Platform (PIP). It explores changes in poverty headcount ratios across multiple international poverty lines ($2.15, $3.65, and $6.85 per day), with a particular focus on the upper-middle income threshold, which offers the most relevant benchmark for high-income countries like the UK. By examining long-term shifts in poverty prevalence, income gaps, and inequality indicators, the project highlights how economic restructuring, welfare reforms, and policy choices have shaped deprivation over five decades. The analysis situates UK poverty within a global context and provides a foundation for comparative and policy-relevant insights.
##
**Data Source**
The World Bank Poverty and Inequality Platform (PIP) Dataset:
- URL: https://pip.worldbank.org/home
<img width="607" height="81" alt="image" src="https://github.com/user-attachments/assets/4c13d1b3-7ea6-406e-a25a-70bc043fe198" />
- https://github.com/worldbank/pip
##
**The PIP Dataset Explained**
The PIP dataset provides harmonized poverty and inequality measures across countries and time. Using it ensures that UK trends can be benchmarked against:
- International income standards: $2.15/day, poverty lines
- Lower middle income: $3.65/day, poverty lines
- Upper-middle income: $6.85/day poverty lines).

The dataset provides consistent time-series data (1967 – present) allowing tracking of decades of poverty dynamics

For the UK this is especially important since extreme poverty (international line) is rare, but relative poverty remains an issue

In a high-income country like the UK, the upper-middle income poverty line ($6.85/day) is the most appropriate one to review  

The PIP dataset provides harmonized poverty and inequality measures across countries and time. Using it ensures that UK trends can be benchmarked against:
- International income standards: $2.15/day, poverty lines
- Lower middle income: $3.65/day, poverty lines
- Upper-middle income: $6.85/day poverty lines).

The dataset provides consistent time-series data (1967 – present) allowing tracking of decades of poverty dynamics.

For the UK this is especially important since extreme poverty (international line) is rare, but relative poverty remains an issue
In a high-income country like the UK, the upper-middle income poverty line ($6.85/day) is the most appropriate one to review.  

<img width="553" height="340" alt="image" src="https://github.com/user-attachments/assets/9e613e6a-19e8-424c-96d5-fb68c7397d5b" />
_______________________________________
## **Understanding the PIP Dataset**
The World Bank’s PIP dataset contains two harmonized poverty series, one based on 2011 PPP and one on 2017 PPP. 
Both use the same international poverty lines ($2.15, $3.65, and $6.85/day), but the conversion factors differ.  
The 2017 PPP series provides the most up-to-date global comparability. 
Thus for this project, the 2017 PPP series is used as the reference, as it reflects the latest international calibration.

## **PIP Codebook**
A list of all variables/features included in the datafile. 
The key ones for this project are:
- **headcount_ratio_international_povline**,% of population living in households with an income or expenditure per person below the International Poverty Line: $1.90 a day (in 2011 prices) or $2.15 a day (in 2017 prices).
- **headcount_ratio_lower_mid_income_povline**,% of population living in households with an income or expenditure per person below the lower-middle income poverty line: $3.20 a day (in 2011 prices) or $3.65 a day (in 2017 prices).
- **headcount_ratio_upper_mid_income_povline**,% of population living in households with an income or expenditure per person below the upper-middle income poverty line: $5.50 a day (in 2011 prices) or $6.85 a day (in 2017 prices).
- headcount_international_povline,Number of people living in households with an income or expenditure per person below the International Poverty Line: $1.90 a day (in 2011 prices) or $2.15 a day (in 2017 prices).
- headcount_lower_mid_income_povline,Number of people living in households with an income or expenditure per person below the lower-middle income poverty line: $3.20 a day (in 2011 prices) or $3.65 a day (in 2017 prices).
- headcount_upper_mid_income_povline,Number of people living in households with an income or expenditure per person below the upper-middle income poverty line: $5.50 a day (in 2011 prices) or $6.85 a day (in 2017 prices).
- avg_shortfall_international_povline,The average shortfall from the International Poverty Line per day (averaged across the population in poverty). The International Poverty Line is $1.90 a day (in 2011 prices) or $2.15 a day (in 2017 prices).
- avg_shortfall_lower_mid_income_povline,The average shortfall from the lower-middle income poverty line (averaged across the population in poverty). The lower-middle income poverty line is $3.20 a day (in 2011 prices) or $3.65 a day (in 2017 prices).
- avg_shortfall_upper_mid_income_povline,The average shortfall from the upper-middle income poverty line (averaged across the population in poverty). The upper-middle poverty line is $5.50 a day (in 2011 prices) or $6.85 a day (in 2017 prices).
- total_shortfall_international_povline,"The total shortfall from the International Poverty Line: $1.90 a day (in 2011 prices) or $2.15 a day (in 2017 prices).
xxxxxxx




## **Project Management**
To ensure the success delivery of this project, a Trello was created:
https://trello.com/b/R80xkarD/first-project

#~ **EDA**
##Initital Data Review
1. Read the PIP Dataset Codebook
2. Initial data revew in Excel
3.  

## Features

| Feature # | Description              | Status   | Link |
|-----------|--------------------------|----------|------|
| Feature 1 | User authentication      | ✅ Done  | [View](https://github.com/your-repo/auth) |
| Feature 2 | Real-time notifications  | 🚧 In Progress | [View](https://github.com/your-repo/notifications) |
| Feature 3 | Dark mode toggle         | 📝 Planned | [View](https://github.com/your-repo/dark-mode) |


________________________________________
##Project Structure
project-name/
│── src/
│   ├── main.py
│   └── ...
│── tests/
├── requirements.txt
├── README.md
└── .gitignore
________________________________________
🛠️ Installation
Prerequisites
•	Python 3.X installed
•	pip / venv installed
git clone https://github.com/yourusername/project-name.git
cd project-name
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
________________________________________
🚀 Usage
python src/main.py
Add explanation or examples:
python src/main.py --input data.txt
________________________________________
⚙️ Configuration
Add environment variables or config file information:
API_KEY=your_api_key
DEBUG=True
________________________________________
✅ Running Tests
pytest
________________________________________
## ** Development Setup (VS Code)**
Install recommended VS Code extensions:
•	Python
•	Pylance
•	Black Formatter
•	isort
•	GitLens
Recommended settings (.vscode/settings.json):
{
  "python.formatting.provider": "black",
  "editor.formatOnSave": true,
  "python.linting.enabled": true,
  "python.linting.pylintEnabled": true
}
________________________________________
##**Screenshots / Demo**
Add images or GIF demos here
________________________________________
## **To Contribute**
git checkout -b feature/my-feature
git commit -m "Add new feature"
git push origin feature/my-feature
Open a Pull Request ✅
________________________________________
##**License**
MIT License — feel free to modify
________________________________________
## **Get in Touch**

| 📌 Detail   | 📎 Info                                      |
|------------|----------------------------------------------|
| 👤 Author   | *Teresa McGarry*                                  |
| 📧 Email    | [teresa_mcgarry@hotmail.com)      |
| 💻 GitHub   | xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx |








