# *UK Poverty and Inequality Trends (1969 - 2017): Insights from the World Bank PIP Dataset* #
_______________________________________
## **Project Background**
This project analyses poverty and inequality trends in the United Kingdom between 1969 and 2017 using data from the **World Bank’s Poverty and Inequality Platform (PIP)**. It explores changes in poverty ratios across multiple international poverty lines ($2.15, $3.65, and $6.85 per day), with a particular focus on the upper-middle income threshold, which offers the most relevant benchmark for high-income countries like the UK. 
_______________________________________
## **Data Source**
The World Bank Poverty and Inequality Platform (PIP) Dataset:
- URL: https://pip.worldbank.org/home
- GitHub: https://github.com/worldbank/pip
_______________________________________
## **The Project Context** ##

## **1. The PIP Dataset** ##
The PIP dataset provides consistent time-series data allowing tracking of decades of poverty dynamics across countries and time (1967 - present). For the UK the data spans 1969 - 2017. There is sparse coverage in the 1970s and 1980s. From 1994 there is fairly consistent annual reporting.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/981cf5ee-2c75-4c81-8772-b84ed9f8b11a" />

The dataset provides harmonized poverty and inequality measures. Using it ensures that UK trends can be benchmarked against:
- International income standards: $2.15/day, poverty lines
- Lower middle income: $3.65/day, poverty lines
- Upper-middle income: $6.85/day poverty lines.

In a high-income country like the UK, the **upper-middle income poverty line ($6.85/day)** is the most appropriate one to use for review.  

The World Bank’s PIP dataset contains two harmonized poverty series, one based on 2011 PPP and one on 2017 PPP. Both use the same international poverty lines ($2.15, $3.65, and $6.85/day), but the conversion factors differ.  The 2017 PPP series provides the most up-to-date global comparability. Thus for this project, the 2017 PPP series is used as the reference, as it reflects the latest international calibration.

## **2 The PIP Codebook**
A list of all 108 features included in the datafile are available in the PIP codebook. 

The features fall into 2 classifications: **Inequality** and **Poverty**.

The key ones for this project are:

**Inequality:**

- **Mean:** The mean level of income or expenditure per day.
- **Median:** The level of income or expenditure per day below which half of the population live.
- **Gini Index:** A measure of income or wealth inequality within a population. It tells you how evenly income or consumption is distributed across the entire income distribution.
- **Palma Index/Ratio:** A measure of income inequality that compares the richest 10% to the poorest 40% of a population. It was developed as an alternative to the Gini coefficient, aiming to better capture disparities at the extremes of the income distribution.
- **Polarization:** The growing divide between high-income and low-income groups, often accompanied by the shrinking of the middle class. It’s a key concept in understanding inequality trends, especially in advanced and globalizing economies.
- **MLD(Mean Log Derivation):** A measure of income inequality that emphasises disparities at the lower end of the income distribution. It’s part of the generalised entropy class of inequality metrics and is especially sensitive to changes among the poorest.

**Poverty:**
- **Income Gap Ratio:** The mean shortfall in income or consumption from the poverty line, expressed as a percentage of the poverty line, counting the non-poor as having zero shortfall.
- **Average Income Shortfall:** The average shortfall from the International Poverty Line per day (averaged across population in poverty).
- **Headcount ratio**: % of population living in households with an income or expenditure per person below the International Poverty Line ($2.15 a day in 2017 prices) i.e. how many people are poor.
- **Poverty Gap Index:** The depth of poverty by calculating how far below the poverty line poor individuals fall, on average, expressed as a percentage of that line. It complements the poverty headcount ratio by showing not just how many are poor, but how poor they are
_______________________________________
## **3. Motivation for choosing the PIP Dataset and specifically focusing on the UK as a case study** ##
- The World Bank’s PIP dataset offers a validated, respected, and globally harmonized perspective on poverty and inequality, covering 170+ countries across 50 years.

- Its sheer volume makes it ideal for comparative analysis, but also demands strategic scoping.

- Focusing exclusively on the United Kingdom provides two key advantages:

  - It enables an in-depth exploration of inequality and poverty in a single region without being overwhelmed by global complexity.
  - It offers a sandbox environment to:

    - 	Understand the dataset’s structure, variables, and features before scaling up.
  
    - 	Troubleshoot and refine code for reproducible analysis across other countries or regions.
  
    - 	Validate outputs for plausibility and consistency.
  
    - 	Develop and polish visualizations for clarity and audience impact.
_______________________________________
## **4. Initial goal and project adaptation**

**Initial goal**

My initial goal was to use the full World Bank PIP dataset to explore poverty and inequality worldwide

I aimed to answer:
- Which countries and regions are most affected?
- Who has improved or worsened over time?
 
I had also planned to integrate GDP data for economic context.

**Early Challenges**

- Both datasets were large and conceptually challenging
- The creation of visualisations raised doubts, namely I wasn’t confident the results produced were accurate and correct
- My limited subject knowledge made interpretation difficult

**Project pivoting**

I decided to “chunk” the dataset and focus solely on the United Kingdom which offered:
- A manageable scope
- A sandbox for learning the concepts involved in the PIP dataset and troubleshooting
- A way to easily validate outputs before scaling up
- Confidence that the data was accurate and explainable by cross-checking with the equivalent Excel dataset
_______________________________________
## **5. Project Reflection**

**1. Spend (a lot of) time choosing and reviewing a dataset that:**
- Intrigues you: you genuinely want to uncover what it reveals about the world
- Has concepts you can understand and explain clearly
- Offers sufficient features and observations for valid and insightful analysis
- Allows you to cross-check and validate any new features you create

**2. Start with a manageable scope:**
- Begin with a single country or region to build confidence before scaling globally
- Use case studies to test your workflow and refine your approach
  
**3. Validate at every step:**

- Cross-check outputs against trusted sources (e.g., Excel, documentation)
- Use plausibility checks to catch potential errors early

**4. Build reusable resources:**

- Create region mapping dictionaries, plotting functions, and validation steps that can be reused e.g. across other countries
- Document your logic so others (or future you) can follow it

**5. Visualize with clarity and purpose:**

- Be clear about what you want to say with the data
- Customize plots for clarity, ordering, and audience impact
- Annotate key trends to make findings accessible and compelling

**6. Reflect and adapt:**

- Be willing to pivot your project scope when complexity arises
- Treat challenges as learning opportunities to strengthen your analytical workflow
_______________________________________
## **UK Poverty and Inequality Trends (1969 - 2017): Insights from the World Bank PIP Dataset** ##
## **Project Conclusions**
**Key Takeaways from the UK PIP Dataset Survey Trends (1969-2017)**

**Inequality:**
-	Inequality indicators show modest but persistent increases across five decades, with notable fluctuations.
-	Peaks in inequality—especially in the early 2000s—appear across multiple measures, suggesting that during this period, the poorest became significantly poorer.
  
**Poverty:**
-	Relative poverty measures (e.g. Income Gap Ratio, Average Income Shortfall) show a steady upward trend, with sharp peaks around the early 2000s.
-	More concerning, extreme poverty (Headcount Ratio at the international poverty line) shows a slight increase over time, while the Poverty Gap Index reveals deeper and more persistent deprivation.
_______________________________________
## **Findings**

## **Inequality Measures**

**Mean and Median:** 

The consistently higher Mean implies rising inequality among the poor i.e. the poorest became much poorer. 3 of the 5 largest (mean-median) gaps occur** between 2000-2003  

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/55bb377e-c048-4d47-9593-628de0bc527e" />

**Palma Ratio and Gini Index:**

There is a strong positive correlation between these two inequality measures.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/ff5b828a-cb54-476d-a386-da9b164a4526" />

**Palma Ratio and Gini Index:**

Both measures show that income inequality has risen modestly over time.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/1c8c2685-26a7-40c3-8722-f8044c614261" />

**Polarization:** 

While there is only a modest positive trend when comparing 1969 to 2017, there is a lot of fluctuation evident over this timeline.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/026fad0f-6eb0-453c-870a-e1ebff3f0fc3" />

**MLD:**

A slightly stronger positive relationship between time and inequality, with a further consistent upward trend in inequality.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/f6b87cd4-f589-4053-8139-616b5c9fbbca" />

## **Poverty Measures**

**Income Gap Ratio:**

Whilst each poverty measure shows a persistent incline over time, the upper-middle income poverty line shows the largest increase.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/2a311912-323f-4d37-b17f-e9e842001096" />

**Average Income Shortfall:**

Again, the upper-middle income poverty line shows the biggest increase over time. There are notable spikes in each measure in 2000.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/fee1ddf0-b097-4128-a7e5-a6e9783c9548" />

**Headcount Ratio:**

While fluctuations exist throughout the years, extreme poverty shows an increase over time.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/da8c84fe-b15c-4d71-a319-7e04796a8105" />

**Poverty Gap Index:**

Extreme poverty is rare and stable. The upper-middle income line started high in 1969 but over time exposes deeper and more persistent deprivation. All lines show a peak in 1986.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/56404698-3032-4cb0-8ac6-f27f2dd13444" />

_______________________________________
## **Recommendations for further research** ##
Broaden the research scope by:

- Comparing the UK with:
    
  -  Other high-income countries or Western Europe
  -  Use built in regional aggregates e.g. “World” and “High Income” or create new aggregate variables to deepen analysis
    
- Make the analysis reproducible:
  
  -  Build reusable region mapping dictionaries so that any country can be swiftly analysed
  - Create reusable functions for analysis and visualization for other countries
   
-	Make the presentation slide deck reproducible:
  - Create a slide deck that can be a template for further analysis with other countries or regions
_______________________________________
## **Project Managment**

I created a detailed Trello Board to help guide the analysis process.

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/1f30dc10-3027-4b75-97c0-c19dd6429182" />

link: https://trello.com/b/R80xkarD/tm-individual-project
______________________________________

## **Libraries needed to create visualisations**

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

import plotly.express as px

plt.style.use('ggplot')

sns.set_theme()

## **Get in Touch**

| 📌 Detail   | 📎 Info                                      |
|------------|----------------------------------------------|
| 👤 Author   | *Teresa McGarry*                                  |
| 📧 Email    | [teresa_mcgarry@hotmail.com)      |
| 💻 GitHub   | mcgarryteresa39-stack/individual-project-teresa  |


















