# US Mass Shootings Analysis

## Introduction
The problem we have been facing in America has been the sudden influx of violence and in particular mass shootings. A mass shooting is defined as the fatal or non-fatal shooting of four or more people by a firearm. Based on our research, the common motivations of the shooter that we found were gang violence, armed robbery, and domestic violence. Throughout this study, our goal is to further investigate shooting in the United States as it relates to the pandemic of COVID-19.

![image](https://github.com/user-attachments/assets/900bab16-2a8d-4431-9f1e-2829d7b81589)

## Data Analysis & Computation

### Datasets
We started by defining who was our target audience. Once we could pinpoint our audience, we then moved to find out what datasets we would need to illustrate our hypothesis. Ideal datasets that we were hoping to find to help us deep dive included age, types of weapons used, and locations.

**Data Sources:**  
Our datasets are from [Gun Violence Archive](http://www.gunviolencearchive.org).

### Data Wrangling & Cleaning
Our initial plan was to find multiple datasets and combine them to use as our source, but some of those datasets did not have an identifier for each incident. We were able to find 6 datasets from The Gun Violence Archive that provided most of the required information to answer our business problem.

Next, we downloaded the data in a CSV format to be viewed in Excel dated from 2014-2022. We then performed data cleaning and ensured that all numbers were stored as numbers, date, and text were in their correct format.

Our data was then ready to be used for analysis, and we used Tableau as our primary data analysis tool for this project.

## Exploratory Data Analysis
The exploratory data analysis for this dashboard page focused on viewing the questions related to shooting incidents in the US between 2014-2022.

![image](https://github.com/user-attachments/assets/0e676b3d-2f94-4d0c-aa92-f309b63ed92f)
 
![image](https://github.com/user-attachments/assets/230a083a-dfcd-4a99-836a-2a86e1f878fe)

*In Figure 2, we can see a significant increase in death and injuries in the US during the COVID-19 pandemic.*

![image](https://github.com/user-attachments/assets/abc6047d-a7c2-4c11-9378-113ba759b5bf)
*In Figure 3, we can identify the increase in mass shootings between 2020 and 2022. There was a 46% change in total mass shooting incidents in 2020 and 13% in 2021.*

## Statistical Analysis
To prove our hypotheses that COVID-19 caused an increase in mass shootings, we filtered the datasets by state and city. Then, we included the total incidents, fatalities, and injuries.

![image](https://github.com/user-attachments/assets/eba365f6-5f85-4c25-bf4e-97a2bc9c3a60)
We identified that there has been a clear increase in mass shootings during COVID-19.

![image](https://github.com/user-attachments/assets/ec55ecab-b8b8-411c-aedd-56a85a709d87)


## Dashboard Description

### Use Case
This interactive dashboard allows the user to filter through states and identify shooting statistics in the United States between 2014-2022. It is broken down into several pages to guide the user through an experience.

### Data Engineering
We used Tableau for our case study. Each page of the dashboard represents a section that uses a combination of Bar charts, Line Charts, and Dotted Maps.

1. **Summary**  
    - We used a combination of bar charts and dual line
  
![image](https://github.com/user-attachments/assets/653fa6c0-53b0-4392-8ba5-caebefe004a3)
  
2. **Breakdown**  
    - The breakdown tab allows users to filter data by state. Furthermore, the data is broken down more into subcategories: Total Incidents, Total Deaths, Total Injuries, Mass Shootings, and the specific number of fatalities & injuries over the past 8 years. This information is depicted by a dual line graph.
  
![image](https://github.com/user-attachments/assets/ba82a3b3-fcdf-4f07-b0bf-6a87a12c397b)

  
3. **Map**  
    - This tab allows you to filter through the data in accordance with the number of incidents, fatalities, and injuries. After interpreting this data further, you will notice a pop-up when you hover over the states that will showcase a line graph of the number of incidents filtered through the years 2014-2022.

![image](https://github.com/user-attachments/assets/cbdc02c3-0f39-4c9a-bb5f-f3e47d2e7c3c)
![image](https://github.com/user-attachments/assets/80ea4694-a948-4e5a-b0d9-1d58430ed0bd)

4. **Victim Age**  
    - This tab shows the number of teens and children that were victims of mass shootings. Vital statistics shown are split into the number of teens and children killed and the number of teens and children injured.
  
![image](https://github.com/user-attachments/assets/c40b656b-fccb-4638-a61c-b957e081c795)

![image](https://github.com/user-attachments/assets/3a7fe29f-bc13-4530-ab51-2d419b48799a)


5. **Mass Shootings**  
    - This section highlights mass shootings over time from 2014-2022, emphasizing COVID years. In this chart, you can observe the increase over time and the significant difference in active shootings during COVID-19.
  
![image](https://github.com/user-attachments/assets/d0c2abd8-e884-445b-8bcc-ff9a7cda2fae)


## Conclusions
At the beginning of this proposal, our team sought to prove that the rise of COVID-19 caused an influx of mass shootings across the United States.

If you are a parent, there is a valid reason to be worried for your children’s safety with the increase in mass shootings.

![image](https://github.com/user-attachments/assets/59e550b9-6989-4086-9383-41157e2858aa)

In Figure 5, we noticed a trend between May – September, showing seasonality in our data. If we had time to continue our research, we would perform additional analysis on weather and temperature to confirm this hypothesis.
