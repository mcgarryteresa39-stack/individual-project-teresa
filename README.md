### **UK Poverty and Inequality Trends (1969 - 2017): Insights from the World Bank PIP Dataset**
<img width="397" height="102" alt="image" src="https://github.com/user-attachments/assets/418ce46c-cf9a-4be5-b7ef-1293b7976da0" />
_______________________________________
## **About the Project**
This project analyzes poverty and inequality trends in the United Kingdom between 1969 and 2017 using data from the **World Bank’s Poverty and Inequality Platform (PIP)**. It explores changes in poverty ratios across multiple international poverty lines ($2.15, $3.65, and $6.85 per day), with a particular focus on the upper-middle income threshold, which offers the most relevant benchmark for high-income countries like the UK. 
_______________________________________
##**Data Source**
The World Bank Poverty and Inequality Platform (PIP) Dataset:
- URL: https://pip.worldbank.org/home
- GitHub: https://github.com/worldbank/pip
_______________________________________
###**The PIP Dataset and Assocaitd Resources Explained**

##**The PIP Dataset**
The PIP dataset provides harmonized poverty and inequality measures across countries and time. Using it ensures that UK trends can be benchmarked against:
- International income standards: $2.15/day, poverty lines
- Lower middle income: $3.65/day, poverty lines
- Upper-middle income: $6.85/day poverty lines.

The dataset provides consistent time-series data (1969 – 2017) allowing tracking of decades of poverty dynamics

For the UK this is especially important since extreme poverty (international line) is rare, but relative poverty remains an issue, as identified by this dataset.

In a high-income country like the UK, the upper-middle income poverty line ($6.85/day) is the most appropriate one to use for review.  

The World Bank’s PIP dataset contains two harmonized poverty series, one based on 2011 PPP and one on 2017 PPP. Both use the same international poverty lines ($2.15, $3.65, and $6.85/day), but the conversion factors differ.  The 2017 PPP series provides the most up-to-date global comparability. Thus for this project, the 2017 PPP series is used as the reference, as it reflects the latest international calibration.
_______________________________________
## **PIP Codebook**
A list of all variables/features included in the datafile are available in the PIP codebook. The variables/features fall into 2 classifications: **Poverty** and **Inequality**.
The key ones for this project are:
**Poverty**
- **Mean**: The mean level of income or expenditure per day.
- **Median**The level of income or expenditure per day below which half of the population live.
- **Gini Index**: A measure of income or wealth inequality within a population. It tells you how evenly income or consumption is distributed across the entire income distribution.
- **Palma Index/Ratio**A measure of income inequality that compares the richest 10% to the poorest 40% of a population. It was developed as an alternative to the Gini coefficient, aiming to better capture disparities at the extremes of the income distribution.
- **Polarization**: The growing divide between high-income and low-income groups, often accompanied by the shrinking of the middle class. It’s a key concept in understanding inequality trends, especially in advanced and globalizing economies.
- **MLD(Mean Log Derivation)**: A measure of income inequality that emphasises disparities at the lower end of the income distribution. It’s part of the generalised entropy class of inequality metrics and is especially sensitive to changes among the poorest.
Poverty:
- **Income Gap Ratio**: The mean shortfall in income or consumption from the poverty line, expressed as a percentage of the poverty line, counting the non-poor as having zero shortfall.
- **Average Income Shortfall**: The average shortfall from the International Poverty Line per day (averaged across population in poverty).
- **Headcount ratio**: % of population living in households with an income or expenditure per person below the International Poverty Line ($2.15 a day in 2017 prices) i.e. how many people are poor.
- **Poverty Gap Index**: The depth of poverty by calculating how far below the poverty line poor individuals fall, on average, expressed as a percentage of that line. It complements the poverty headcount ratio by showing not just how many are poor, but how poor they are

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












