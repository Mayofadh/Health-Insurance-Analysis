# Health Insurance Analysis

## Table of contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Tools](#data-tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)


### Project Overview
Health Insurance Analysis exploring uninsured rates from 2010–2015 and changes in Medicaid enrollment from 2013–2016. Includes data cleaning, exploration, visualization, and key insights on insurance coverage trends.

### Data Sources

Health Insurance Data: The primary dataset used for this analysis is the "Health_Insurance.csv" file containing information about made in different countries.

### Data Tools

- Power BI - Creating Dashboard
- Power Query - Data Cleaning

### Data Cleaning

The following tasks were performed:
1. Data Loading and Inspection
2. Data Cleaning and Formatting

### Exploratory Data Analysis
-  What change occured in the medicaid enrollment between 2013 and 2016?
-  Average monthly tax credit by state in the year 2016?
-  What is the percentage change in uninsured rate between the year 2010 and 2015?
-  Is there an increase in the enrollment for health insurance?

### Data Analysis

```DAX
Avg Uninsured Rate 2015 = AVERAGE('Health Insurrance'[Uninsured Rate (2015)])
Total States = COUNT('Health Insurrance'[State])
```

### Findings

The analysis results are summarized as follows:
1. Uninsured rate trends (2010–2015): dropping from 14% to 9%, highlighting improvements in coverage.
2. Medicaid enrollment (2013–2016): showing increased access to healthcare for more people.
3. California stands as the state with the highest medicaid enrollment with 4.1M between the year 2013 and 2016, whereas other states falls below 2M.

### Recommendations
1. Focusing on states with under 2M enrollees by providing awareness campaigns, digital tools, or simplified enrollment support to help increase coverage and attract potential customers.
2. As uninsured rate dropped from 14% to 9%, we can focus on states where the decline is slower. These regions may have more opportunities for outreach, enrollment support, or tailored plans.


