# *UK Poverty and Inequality Trends (1969 - 2017): Insights from the World Bank PIP Dataset* #
_______________________________________
## **About the Project**
This project analyzes poverty and inequality trends in the United Kingdom between 1969 and 2017 using data from the **World Bank’s Poverty and Inequality Platform (PIP)**. It explores changes in poverty ratios across multiple international poverty lines ($2.15, $3.65, and $6.85 per day), with a particular focus on the upper-middle income threshold, which offers the most relevant benchmark for high-income countries like the UK. 
_______________________________________
## **Data Source**
The World Bank Poverty and Inequality Platform (PIP) Dataset:
- URL: https://pip.worldbank.org/home
- GitHub: https://github.com/worldbank/pip
_______________________________________
## **The PIP Dataset and Associated Resources Explained** ##

## **1. The PIP Dataset** ##
The PIP dataset provides consistent time-series data allowing tracking of decades of poverty dynamics across countries and time (1967 - present). For the UK the data spans 1969 - 2017.

The dataset provides harmonized poverty and inequality measures. Using it ensures that UK trends can be benchmarked against:
- International income standards: $2.15/day, poverty lines
- Lower middle income: $3.65/day, poverty lines
- Upper-middle income: $6.85/day poverty lines.

In a high-income country like the UK, the **upper-middle income poverty line ($6.85/day)** is the most appropriate one to use for review.  

The World Bank’s PIP dataset contains two harmonized poverty series, one based on 2011 PPP and one on 2017 PPP. Both use the same international poverty lines ($2.15, $3.65, and $6.85/day), but the conversion factors differ.  The 2017 PPP series provides the most up-to-date global comparability. Thus for this project, the 2017 PPP series is used as the reference, as it reflects the latest international calibration.

## **2 The PIP Codebook**
A list of all 108 variables/features included in the datafile are available in the PIP codebook. 

The variables/features fall into 2 classifications: **Inequality** and **Poverty**.

The key ones for this project are:

**Inequality:**

- **Mean**: The mean level of income or expenditure per day.
- **Median**The level of income or expenditure per day below which half of the population live.
- **Gini Index**: A measure of income or wealth inequality within a population. It tells you how evenly income or consumption is distributed across the entire income distribution.
- **Palma Index/Ratio**A measure of income inequality that compares the richest 10% to the poorest 40% of a population. It was developed as an alternative to the Gini coefficient, aiming to better capture disparities at the extremes of the income distribution.
- **Polarization**: The growing divide between high-income and low-income groups, often accompanied by the shrinking of the middle class. It’s a key concept in understanding inequality trends, especially in advanced and globalizing economies.
- **MLD(Mean Log Derivation)**: A measure of income inequality that emphasises disparities at the lower end of the income distribution. It’s part of the generalised entropy class of inequality metrics and is especially sensitive to changes among the poorest.

**Poverty:**
- **Income Gap Ratio**: The mean shortfall in income or consumption from the poverty line, expressed as a percentage of the poverty line, counting the non-poor as having zero shortfall.
- **Average Income Shortfall**: The average shortfall from the International Poverty Line per day (averaged across population in poverty).
- **Headcount ratio**: % of population living in households with an income or expenditure per person below the International Poverty Line ($2.15 a day in 2017 prices) i.e. how many people are poor.
- **Poverty Gap Index**: The depth of poverty by calculating how far below the poverty line poor individuals fall, on average, expressed as a percentage of that line. It complements the poverty headcount ratio by showing not just how many are poor, but how poor they are
_______________________________________
## **Motivation for choosing the PIP Dataset and specifically focusing on the UK as a case study** ##
- The World Bank’s PIP dataset offers a validated, respected, and globally harmonized perspective on poverty and inequality, covering 170+ countries across 50 years.

- Its sheer volume makes it ideal for comparative analysis, but also demands strategic scoping.

- Focusing exclusively on the United Kingdom provides two key advantages:

  - It enables an in-depth exploration of inequality and poverty in a single region without being overwhelmed by global complexity.
  - It offers a sandbox environment to:

    - 	Understand the dataset’s structure, variables, and features before scaling up.
  
    - 	Troubleshoot and refine code for reproducible analysis across other countries or regions.
  
    - 	Validate outputs for plausibility and consistency.
  
    - 	Develop and polish visualizations for clarity and audience impact.

## ***Conclusions**
**Key Takeaways from the UK PIP Dataset Survey Trends (1969-2017)**

**Inequality:**
-	Inequality indicators show modest but persistent increases across five decades, with notable fluctuations.
-	Peaks in inequality—especially in the early 2000s—appear across multiple measures, suggesting that during this period, the poorest became significantly poorer.
  
**Poverty:**
-	Relative poverty measures (e.g. Income Gap Ratio, Average Income Shortfall) show a steady upward trend, with sharp peaks around the early 2000s.
-	More concerning, extreme poverty (Headcount Ratio at the international poverty line) shows a slight increase over time, while the Poverty Gap Index reveals deeper and more persistent deprivation.
_______________________________________
## ** Recommendations for further research** ##
Broaden the research scope by:
-	Comparing the UK with:
  -	Other high-income countries or Western Europe
  - Use built in regional aggregates e.g. “World” and “High Income” or create new aggregate variables to deepen analysis
  -  Make the analysis reproducible:
-  Build reusable region mapping dictionaries so that any country can be swiftly analysed
  - Create reusable functions for analysis and visualization for other countries
  -	Make the presentation slide deck reproducible:
  - Create a slide deck that can be a template for further analysis with other countries or regions
_______________________________________
##**Initial goal and project adaptation##**

**Initial goal:**

My initial goal was to use the full World Bank PIP dataset to explore poverty and inequality worldwide

I aimed to answer:
- Which countries and regions are most affected?
- Who has improved or worsened over time?
 
I had also planned to integrate GDP data for economic context.

**Early Challenges:**

- Both datasets were large and conceptually challenging
- The creation of visualisations raised doubts, namely I wasn’t confident the results produced were accurate and correct
- My limited subject knowledge made interpretation difficult

**Project pivoting**

I decided to “chunk” the dataset and focus solely on the United Kingdom which offered:
- A manageable scope
- A sandbox for learning the concepts involved in the PIP dataset and troubleshooting
- A way to easily validate outputs before scaling up
- Confidence that the data was accurate and explainable by cross-checking with the equivalent Excel dataset

**Project Reflection**
**Spend (a lot of) time choosing and reviewing a dataset that:**

- Intrigues you: you genuinely want to uncover what it reveals about the world
- Has concepts you can understand and explain clearly
- Offers sufficient features and observations for valid and insightful analysis
- Allows you to cross-check and validate any new variables you create

**Start with a manageable scope:**
- Begin with a single country or region to build confidence before scaling globally
- Use case studies to test your workflow and refine your approach
  
**Validate at every step:**

•	Cross-check outputs against trusted sources (e.g., Excel, documentation)
•	Use plausibility checks to catch errors early

**Build reusable resources:**

- Create region mapping dictionaries, plotting functions, and validation steps that can be reused across countries
- Document your logic so others (or future you) can follow it

**Visualize with clarity and purpose:**

- Be clear about what you want to say with the data
- Customize plots for clarity, ordering, and audience impact
- Annotate key trends to make findings accessible and compelling

**Reflect and adapt:**

Be willing to pivot your project scope when complexity arises
Treat challenges as learning opportunities to strengthen your analytical workflow
<img width="1926" height="633" alt="image" src="https://github.com/user-attachments/assets/b1278433-8d29-4f28-a4ef-82811b575eda" />

## **Project Management**
To ensure the success delivery of this project, a Trello board was created:
https://trello.com/b/R80xkarD/first-project

## **Get in Touch**

| 📌 Detail   | 📎 Info                                      |
|------------|----------------------------------------------|
| 👤 Author   | *Teresa McGarry*                                  |
| 📧 Email    | [teresa_mcgarry@hotmail.com)      |
| 💻 GitHub   | xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx |














