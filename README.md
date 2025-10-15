# Exploratory Data Analysis of Influenza and Influenza-Like Illness (ILI) Data

## Project Overview
This project performs exploratory data analysis (EDA) on the Influenza dataset obtained from the World Health Organization (WHO). The goal is to understand trends in influenza spread across regions and countries, identify the most contagious virus types, and examine associated fatalities.

The dataset includes counts of influenza-positive cases, categorized by virus type, and the accompanying FLUID dataset provides information on influenza-like-illness (ILI) cases, their seriousness, and fatalities.

The analysis explores:
- Regional and country-level trends across WHO’s six regions.
- Seasonal and yearly trends in selected countries.
- Relationships between ILI, Acute Respiratory Illness (ARI), Seriously Acute Respiratory Illness (SARI), and fatalities, with emphasis on age-group-specific mortality.

### Analysis Goals
- Identify regions and countries with the highest counts of influenza and ILI in recent years.
- Perform EDA by removing missing and inconsistent values, duplicate rows/columns, and irrelevant data; group or rename columns as needed for clarity.
- Understand global influenza trends and region-wise distributions.
- Examine yearly and seasonal trends in selected countries.
- Determine the most contagious virus types and analyze trends across influenza and ILI cases.
- Explore long-term changes in influenza spread over the past two decades.
- Analyze relationships between ILI, ARI, SARI, percentage deaths, and age groups.
- Provide insights for potential time-series forecasting of influenza cases.

### Motivation
Respiratory illnesses, including influenza, affect a significant portion of the global population and can range from mild to deadly. Due to the challenging impact of COVID-19 , my interest in applying data science and AI to public health grew and this project aims to:
- Track and analyze influenza incidence worldwide.
- Understand disease spread and trends in virus types.
- Assess severity and fatalities across age groups.
- Provide actionable insights for public health organizations, including vaccine administration, flu shot improvements, and preventive strategies.

### Data Sources
The datasets are obtained from the **World Health Organization (WHO)**:
- **FluNet and FluID**: CSV datasets provided by the Global Influenza Surveillance and Response System (GISRS) and national epidemiological institutions.
- Weekly counts of influenza cases by virus type and ILI cases by severity.
- Link: [WHO Global Influenza Programme Surveillance Outputs](https://www.who.int/teams/global-influenza-programme/surveillance-and-monitoring/influenza-surveillance-outputs)

### Key Insights
- **Region-Wise Impact**: The Americas consistently reported the highest influenza cases across years (except 2010–2011), with the US and Canada as major contributors.
- **Increasing Spread**: Europe and the Western Pacific regions have shown rising influenza cases in recent years.
- **Seasonality**: Influenza cases peak during winter months (December–January) and in the first 10 weeks and last 5 weeks of each year.
- **2022 Outlier**: Earlier peak and longer duration of cases in the US, Canada, and China prompted further investigation.
- **Country-Level Trends**: The US and China consistently report high case numbers, indicating country-specific drivers behind repeated outbreaks.
- **Virus-Type Analysis**: Type A influenza is more contagious and dominant, with A_OTHER (unsubtyped virus) contributing the most globally and in the US. Contribution of Type A cases increased significantly from 2020 to 2022.

### Key challenges

** The datasets were messy and inconsistent, making cleaning time-consuming. Age-wise analysis of ILI fatalities was not possible due to missing age data. Merging FLUID and FLUNET was difficult because of mismatched dates and repeated counts, leading to many NaN values. Also, many recent cases were labeled as untyped “virus type-A other,” reducing precision.**


### Disclaimer
This is a completely original project including the definition of goals, analysis plans, and insights. All work  from problem formulation to exploratory analysis and interpretation  was entirely self-conceived and executed by the author.


### License
This project is licensed under **All Rights Reserved**. All rights to the code, documentation, and related content are retained by the author. No part of this project may be reproduced, distributed, or modified without explicit permission.

For permissions or inquiries, contact: **niranchanar.07@gmail.com**
