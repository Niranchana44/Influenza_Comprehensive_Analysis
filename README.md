### Overview of the project and the goals

The project deals with performing exploratory data analysis on the Influenza dataset obtained from WHO.This information can help in understanding the trends in the disease to better track and handle the influenza spread. Influenza dataset provides the count of the cases tested positive for influenza across regions and countries. The virus type for the recorded cases have also been specified. Additionally, the accompanying FLUID dataset also provides information about influenza-like-illness cases,their seriousness and fatalities.


Analyzed WHO influenza and Influenza-like Illness (ILI) data, focusing on region-wise and country-wise trends in recent years. The analysis involved cleaning and pre-processing the data (handling missing values, duplicates, and inconsistencies), understanding global trends, and examining regional distributions across WHO's 6 regions. Explored yearly and seasonal trends in select countries, identified the most contagious virus strains, and tracked changes over two decades. The analysis also examined the relationship between ILI, Acute Respiratory Illness (ARI), Seriously Acute Respiratory Illness (SARI), and fatalities, with a focus on age-group-related mortality trends.

### Goals related to the analysis plans:-
- The analysis is focussed on areas with highest values of reported count of influenza and Influenza-like illness region-wise and country-wise in the recent years.
- Perform EDA by removing missing and inconsistent values,removing duplicate rows,unwanted rows and columns.I may group together suitable columns,change data type /column name to make it more appropriate and perform other required pre-processing.
- Understand the worldwide trend of total influenza cases.I would liked to determine the region wise(WHO has 6 regions) distribution of influenza cases and also find out countries with the - highest count of influenza cases in the recent years.
- Understand the recent yearly and seasonal trends in the selected countries.
- Understand the more contagious virus-type and virus trends in influenza and influenza-like illness across the countries.
- Explore the trends in influenza in the past two decades and identify changes.
- Perform analysis based on total influenza like illness (ILI) cases reported,cases of Acute Respiratory Illness (ARI)and Seriously Acute Respiratory Illness ( SARI) and percentage deaths. I would like to understand the trends and also see if any relationship between age-groups and fatalities is visible in these areas.
- I believe, this analysis could possibly also help in developing a time-series forecast model as a future scope.

#### Why I chose this project

I am very interested in the application of data science and artificial intelligence to transform different industries.
Covid-19 caused a massive upheavel in the society and affected numerous people.There are other respiratory illnesses that affect significant proportion of population around the world.Influenza is a common illness that cause mild to severe symptoms and could also be deadly. I feel better understanding and tracking incidence of the illness can help in better managing them.

I chose this data because it is very comprehensive,covers data pertaining to incidence of influenza across counties on a weekly and yearly basis, provides classification according to influenza type A or B or mention of other category of respiratory illness when tested for influenza. Data in the other data file can also help in estimating the seriousness of the incident lung infections .I believe this can facilitate in depth anaylsis to yield several informative insights.It can help to better understand the disease spread,identify trends,determine the contagious type of virus and fatality of respiratory illness across the age groups etc.
This type information can help public health organizations track the disease,understand trends in virus and impact and take effective action to control the spread. It can help in administering vaccines,develop more effective flu shots, forecast future spread and take preventive measures.It can also help healthcare providers in better decision-making.

### Data sources
The datasets for the project have been chosen from WHO(World Health Organization). The World Health Organization is a specialized agency of the United Nations responsible for international public health. The Global Influenza Programme of WHO provides a global platform for influenza surveillance information reporting, analysis and presentation. The dataset is shared through FluNet and FluID by the Global Influenza Surveillance and Response System (GISRS) and national epidemiological institutions. The count for influenza for various virus types and other ILI types is recorded respectively country wise and on a weekly basis The FluNet and FluID csv data files have been used in this project.The link is:

https://www.who.int/teams/global-influenza-programme/surveillance-and-monitoring/influenza-surveillance-outputs

### Some key insights from analysis
- America as Major Contributor: The American region consistently reported the highest number of influenza-positive cases across years, except in 2010 and 2011, with the United States being the primary contributor, often along with Canada.

- Increase in Influenza Spread: There has been a general increase in influenza cases over the past decade, with regions like Europe and the Western Pacific also showing a rise in recent years.

- Seasonality and Distribution: The data reveals a seasonal pattern—most influenza cases occur during winter months (especially December to January), and weekly trends show peaks in the first 10 weeks and last 5 weeks of the year.

- 2022 as an Outlier Year: The year 2022 showed unusual patterns with an earlier peak and a longer duration of reported cases in countries like the US, Canada, and China, prompting investigation into virus types and trends for 2023.

- Country-Level Impact: Besides the US, China also consistently reported high numbers of cases, indicating the need to examine country-specific drivers behind repeated influenza outbreaks.
- Analysis of pie charts reveals that Influenza Type A is the more contagious and dominant virus type in the U.S.

-The contribution of Type A cases has increased significantly from 2020 to 2022.

- Within Type A, A_OTHER (unsubtyped virus) consistently showed the highest contribution, both in the U.S. and globally.


### Disclaimer
This is an entirely independent and original project conducted using publicly available data from the World Health Organization’s Global Influenza Surveillance platforms—FluNet and FluID. All data preprocessing, analysis, visualizations, and documentation were solely performed and written by me.
This project was not replicated from any existing source and reflects my own exploration, interpretation, and findings.


### License
This project is licensed under **All Rights Reserved**. All rights to the code, documentation, and any related content are retained by the author. No part of this project may be reproduced, distributed, or modified without explicit permission.

For permissions or inquiries, please contact niranchanar.07@gmail.com.
