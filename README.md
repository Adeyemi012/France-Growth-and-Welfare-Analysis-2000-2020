# France's Growth and Welfare Analysis (2000-2020)

## Introduction
### Context

From 2000 to 2020, France has faced a persistent trade deficit, meaning the country has been importing more than it exports. This situation is like a family spending more money than they earn, creating financial strain. At the same time, France has worked to improve the quality of life for its citizens, especially in urban areas where population growth has put pressure on resources and infrastructure. The challenge for France is to find a way to balance economic growth, social welfare, and sustainability, while addressing the ongoing trade deficit. In this analysis, we’ll explore how France can achieve these goals and create a more stable, prosperous future for its people.

### Problem Statement

Over the past two decades, France has faced a persistent trade deficit, importing more than it exports, while trying to balance economic growth and social welfare. With a growing urban population demanding better living standards, the country faces increasing pressure on resources and infrastructure. These challenges are compounded by the need to stay competitive globally and ensure sustainable development. How can France reduce the trade deficit, foster economic growth, and improve social welfare, all while ensuring long-term sustainability?

### Objectives

The primary objectives of this analysis are:
1. To assess economic growth by evaluating France's economic growth over time.
2. To examine trade balance by assessing France's trade balance annually.
3. To analyze population and urbanization by examining trends in population and urbanization.
4. To evaluate social welfare and public services by evaluating the effectiveness of social welfare and public services.
5. To provide recommendations based on the analysis.

## Data Description 
### Data Source

The data used in this analysis was downloaded from the World Bank’s open data portal for France, available at this [link](https://data.worldbank.org/country/france). The dataset was provided in Excel format and includes various economic and social indicators for France.

### Data Collection

The dataset consists of two main sheets: one with metadata-indicators, and another containing the actual data. After downloading the file, we extracted the relevant indicators from the "metadata-indicators" sheet and selected the necessary data points from the main data sheet for our analysis. These indicators were specifically chosen to focus on France's trade deficit, economic growth, and social welfare.

### Data Characteristics 

The dataset used for this analysis consists of three tables, each focusing on distinct aspects of the data:

**1. Demographics and Population Data**
This table contains information about the population distribution and composition, with the following fields:
- **Year:** The specific year for the data point.
- **Urban Population:** The number of people living in cities and towns.
- **Urban Population (% of total):** The percentage of the total population that lives in cities and towns.
- **Rural Population:** The number of people living in countryside areas.
- **Rural Population (% of total):** The percentage of the total population that lives in the countryside.
- **Total Population:** The total number of people in the country.
- **Male Population:** The number of males in the country.
- **Male Population (% of total):** The percentage of the total population that is male.
- **Female Population:** The number of females in the country.
- **Female Population (% of total):** The percentage of the total population that is female.

**2. Economic Indicators**
This table provides economic metrics to assess the country's performance, with fields such as:
- **Year:** The specific year for the data point.
- **GDP (current US$):** The total value of all goods and services produced in the country, measured in current US dollars.
- **Gross National Expenditure (constant 2015 US$):** The total amount of money spent on goods and services in the country, adjusted to reflect the value of money in 2015, so we can compare spending over different years without worrying about inflation.
- **Final Consumption Expenditure (% of GDP):** The percentage of GDP that is spent on goods and services for final consumption by households and the government.
- **Gross Capital Formation (% of GDP):** The percentage of GDP that is invested in fixed assets like buildings, machinery, and infrastructure.
- **External Balance on Goods and Services (current US$):** The difference between the value of goods and services exported and imported by the country, measured in current US dollars. A negative value indicates a trade deficit.

**3. Social and Public Services**
This table focuses on government and household consumption and public service metrics:
- **Year:** The specific year for each data point.
- **General Government Final Consumption Expenditure (current US$):** Government spending on goods and services for public use.
- **Households and NPISHs Final Consumption Expenditure (current US$):** Spending by households and non-profits on goods and services.
- **Fixed Telephone Subscriptions (per 100 people):** Number of landline subscriptions per 100 people.
- **Refugee Population by Country or Territory of Asylum:** Number of refugees living in the country.

## Methodology
### Data Cleaning 
The data cleaning process involved several key steps using Excel: 

**Verification of Data Types:** Confirmed that each column had the correct data type (e.g., numerical, text, or date) to avoid issues during analysis. 

**Validation of Extracted Data:** Reviewed the extracted data to ensure it aligned with the intended indicators and was suitable for analysis.

### Data Modeling
For the analysis, data modeling was used to establish relationships between the three tables. A one-to-one relationship was created between the tables using the Year column as the linking key. This allowed for a direct connection of data points across the three tables—Demographics and Population Data, Economic Indicators, and Social and Public Services—ensuring consistency and enabling accurate analysis across all datasets. 

This approach ensured that each year’s data from all three tables could be joined seamlessly, allowing for comprehensive analysis while maintaining the integrity of the dataset.

### Tools Used
**Microsoft Excel:** Utilized for data cleaning processes, including verifying data types and validating extracted data. [Download here](https://www.microsoft.com/en-us/microsoft-365/excel)

**Microsoft Power BI:** Used for data modeling to establish relationships between tables and create an interactive report for analysis and visualization. [Download here](https://apps.microsoft.com/detail/9NTXR16HNW1T?hl=en-us&gl=NG&ocid=pdpshare)

## Analysis
### Analysis Questions

- How has economic growth in France evolved over time?
- What is the annual trade balance of France?
- What are the trends in population and urbanization in France?
- How effective are the social welfare and public services in France?
- What recommendations can be made based on the analysis?

## Dashboard Overview

### Interact with Dashboard [here](https://app.fabric.microsoft.com/view?r=eyJrIjoiZTYxOTM0ZGYtMDU2ZS00MDU0LWI5ZjgtMzA1ODBiYThlMDg2IiwidCI6ImRhZjMyMGRmLTc4ODMtNDA0Ny1hZWVjLTAxNTliMjRkZGFmZSIsImMiOjZ9)

![](https://github.com/Adeyemi012/France-Growth-and-Welfare-Analysis-2000-2020/blob/main/Screenshot%202024-12-18%20191527.png)

## Insights

### KPI Overview:

![](https://github.com/Adeyemi012/France-Growth-and-Welfare-Analysis-2000-2020/blob/main/Screenshot%202024-12-18%20193339.png)

The average population in France during the analyzed period was 64.75 million, showing a steady upward trend. The total GDP over this period amounted to $50.55 trillion, with fluctuations but an overall growth pattern. The trade deficit as a percentage of GDP was -0.62%, indicating a decreasing trend over time. Additionally, the total Gross National Expenditure (GNE) reached $48.80 trillion, reflecting a consistent increase throughout the years.

This overview provides a snapshot of key economic indicators and their trends, helping to understand France's economic trajectory over the analyzed period.

![](https://github.com/Adeyemi012/France-Growth-and-Welfare-Analysis-2000-2020/blob/main/Screenshot%202024-12-18%20194415.png)

**Economic Growth:** The analysis of France's GDP from 2000 to 2020 reveals a general upward trend, punctuated by significant peaks in 2008 and 2011. Despite these increases, there were noticeable fluctuations, particularly in 2009, likely due to the global financial crisis. This period reflects economic instability and challenges faced by France during that time.

Comparing GDP with Gross National Expenditure (GNE), it is evident that GNE consistently exceeded GDP. This indicates substantial consumer and government spending, which played a critical role in driving economic activities. Post-2010, GDP showed recovery, peaking in 2018 before experiencing slight declines in subsequent years, likely influenced by various global market conditions.

The data from 2020 shows a decline in GDP, attributed to the global impact of the COVID-19 pandemic. This period highlights the vulnerability of economic structures to unforeseen global events.

Overall, the insights suggest that while France's economy experienced periods of instability, the long-term trend indicates growth and resilience, supported by strong national expenditure. This comprehensive view provides a clear understanding of France's economic performance over the past two decades.




