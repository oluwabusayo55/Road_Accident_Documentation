# Road_Accident_Documentation

### Project Title: Road Accident Analysis

### Project Overwiew
---
The objective of this project is to generate insights into road accidents and their drivers for 2021 and 2022. The project involved cleaning and processing the data, conducted exploratory analysis to identify trends and insights, creating visualizations of these insights which would enable me to make reasonable conclusions and recommendations from this data.

### Data Sources
---
The source of data used for this analysis is Road_Accident_Data which was provided in csv format and can be gotten from an open source online such as FRED or any data generation site. The key dataset columns include:
 - Accident date
 - Months
 - Year
 - Accident severity
 - Light conditions
 - Light group
 - No of casualties
 - Road surface condition
 - Surface group
 - Road type
 - Vehicle group

### Tools Used
---
- Microsoft Excel
   - Data Cleaning and Processing
   - Data Aanlaysis
   - Data Visualization
     
- Github for documnetation

### Data Cleaning and Processing 
---
In this phase, the following data cleaning and processing actions were done;
- Data loading and Inspection
- Data cleaning and formatting
- Handling duplicates and missing values
- Creation of new columns and introducing formulas for formatting
- Sorting and Filtering

### Data Analysis
---
During this phase, I did exploratory analysis by summarising the data to identify identify patterns and key insights. The analysis identified Monthly trends based on accidents, Casualties caused by Road Type and Road Surfaces, Casualties that occured based on locations, Casualties by Road Lighting Conditions and Casualties by Vehicle types through the use of Pivot tables and their corresponding charts. The analysis revealed;
 - Current and Previous year casualties: A pivot table was created to analyse CY and PY casualties in 2021 & 2022, which revealed that November reported the highest casualties for both years. A line chart was used to visually highlight this peak, suggesting that seasonal factors influenced this surge.

![CY vs PY Casualties](https://github.com/user-attachments/assets/55836ea6-0d83-4fab-8735-7822e43c2517)

![CY vs PY chart](https://github.com/user-attachments/assets/af479dde-148d-49ec-bcc4-db242b6416f9)

 - Casualties by Road Type: A pivot table was used to analyse Road type casualties, showing that Single carriageway accounted for majority of the casualties compared to other Road types, which emphasizes the importance of safety measure such as road design enhancement. A bar chart was used to visualise this distribution.

![Casualties by Road Type](https://github.com/user-attachments/assets/e73c72ee-d1e0-475a-b33b-00e79b88109d)

![Road Type chart](https://github.com/user-attachments/assets/ead899cf-d7ea-40b7-8aac-3e672bb83051)

 - Casualties by Road Surface: Another pivot table was used to compare the number of casualties among the three road surfaces, which revealed that Dry surface had the highest casualties, which indicates that road safety isn't only dependent on weather conditions but also driver behaviour and road management. A treemap was used to visualise this distribution

![Casualties by Road Surface](https://github.com/user-attachments/assets/2df84d97-b94f-4019-8980-1fea4dde8ae9)

![Road Surface chart](https://github.com/user-attachments/assets/a6c6a023-5ccf-4061-a878-da49de624365)

 - Location Analysis: Pivot table was used to examine casualties by location, showing Urban area with the majority of casualties, which emphasizes the need for safety campaigns and implementation in urban area. A doughnut chart highlighted this distribution.

![Casualties by Location](https://github.com/user-attachments/assets/2786e197-604d-4caa-a2e6-ffca3c756088)

![Location chart](https://github.com/user-attachments/assets/efd7714b-1792-4293-a0f8-58c9679be24a)

 - Casualties by Light Conditions: Pivot table was used to analyse the impact of Light conditions on casualties, which indicated that most casualties occured during daylight. This suggest that visiblity does not guarantee, but other factors such as distractions and higher traffic density may contribute to this trend.

![Casualties by Light Conditions](https://github.com/user-attachments/assets/425745e1-2809-45c9-820c-d3b2b7b12dcf)

![Light conditions chart](https://github.com/user-attachments/assets/b0a66118-bffb-4938-8a7b-ef662ce0dee6)

Key Insights Found Include;
- Fatal Casualties: 6,858 (1.2% of Total Casualties)
- Serious Casualties: 67,328 (12.2%)
- Slight Casualties: 475,901 (86.5%)
- Casualties Involving Cars: 438,611 (79.7%)
- Total Casualties: 550,087

This analysis highlights critical areas requiring attention to improve road safety and reduce casualty rates.

### Data Visualization
---
In this phase, i built an interactive dashboard of the analysis to make trends and insights easily interpretable. These visuals were created to provide a comprehensible view of Road performances and region trends over time.

![Dashboard (2)](https://github.com/user-attachments/assets/c6cad148-4b35-40f9-b380-bba8bbe756af)

[View Dashboard Here](https://1drv.ms/x/c/3e32c9b80a7ac08e/ESNlKGp9YPxNo-ZqskjjhMEBYd45qV2aGYQm9ZCb5pv4UQ?e=dQX7iK)

### Conclusion
---
The objective of this data analysis project was to analyse the Road Accident Data of 2021 and 2022 in order to understand their causes and identify patterns in the data. Several key insights were derived from the data:
 - November reported the highest casualties in both 2021 and 2022, suggesting seasonal factors such as increased road usage or adverse weather conditions during this period.
 - A significant number of casualties occurred on the single carriageways, which indicates that safety measures such as road design enhancements may be required to mitigate risks.
 - Dry road surfaces accounted for the majority of casualties, followed by Wet and Snow surfaces. This emphasizes that road safety isn't solely dependent on weather conditions but also on driver behaviour.
 - The majority of incidents occured in the Urban areas, likely due to higher traffic density. this finding emphasizes the need for targeted safety campaigns and enforcement in urban areas.
 - Most Casualties occured in daylight conditions, indicating that visibility alone does not guarantee safety, but factors such as distractions, taffic congestion and speed may contribute to this trend.

### Recommendations
---
From the observations gotten from the data, here are my recommendations;
- Invest in improving road conditions and deploy more safety officers to patrol urban areas which would mitigate high casualty rates.
- Install adequate and efficient lighting systems on roads, especially in high traffic areas to enhabce visiblity and reduce accidents.
- Despite the assumption that dry roads are safer, analysis indicates that accidents occur more on this roads. There should be implementation of speed limits, penalties for reckless driving  and raising driver awareness about the risks of high-speeding.
- Since single-way roads report the highest casualties, consideration should be made for redesigning wider lanes and pedestrian crossings.
- Cars account for the hgihest number of casualties. There should be stricter implementation of traffic laws for car drivers and encourage the use of advanced safety technologies like collision avoidance systems in Vehicles.

