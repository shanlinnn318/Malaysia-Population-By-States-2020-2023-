# Malaysia-Population-By-States-2020-2023-Dashboard

### Dashboard Link :https://app.powerbi.com/reportEmbed?reportId=82ed6b56-004d-4bbc-b97d-3857322b01ac&autoAuth=true&ctid=6ac7a1f4-5fb1-4153-bb4f-12d2020a1f7d

## Dataset Link
https://data.gov.my/data-catalogue/population_state

## Dataset description
This dataset tabulates the population of Malaysia at state level, by sex, ethnicity, and 5-year age group, from 2020 to 2023.

## Variable definitions

Date - The date in YYYY format

State - One of 16 states

Ethnicity - One of six mutually exclusive ethnic groups

Age Group - Five-year age groups e.g. 0-4, 5-9, 10-14, etc. 85+ is the oldest category.

Female - Total population (Female)

Male - Total population (Male)

### Steps followed 
- Step 1 : Before loading data into Power BI, data cleaning and data transformation process have been executed. The purpose is to get rid of the unwanted observations in the dataset and also convert data into a proper and suitable format. The details of these processes are shown as below:
  1.Extract the year data from the date data by using TEXT function
    * Another option: using custom date format, YYYY
  2. Population data
    * Extract population data from ('000) format to exact total number of population data
  3. Sex data
    * Clear overall_sex data (total number of population by sex)
  4.  Ethnicity data
    * Clear overall_ethnicity data (total number of population by ethnicity)
 5. Age data
    * Clear overall_age data (total number of population by age)

 Summary: After data cleaning process, number of data has decreased from 25537 to 13825. 

- Step 2 : Load data into Power BI, dataset is a xlsx file.
- Step 3 : 4 donut charts were used to represent population rate by different ethnicities. 
- Step 4 : A stacked bar chart was also added to the report design to view the total number of population by age group and sex.
- Step 5 : Line chart was added to the report design area representing the growth of population by year and sex. While creating this visual, field named "date" added to X-axis, "sum of population" is added to Y-axis while "sex" is added to legend.    
- Step 6 : A dashboard was created to visualize the graphs and charts created earlier. Also, I added total number of population within these 4 years, male population and female population.
- Step 7 : Visual filters (Slicers) were added for a field named "Year".
- Step 8 : The report was then published to Power BI Service.
 
 
# Snapshot of Dashboard (Power BI Service)

![image](https://github.com/shanlinnn318/Malaysia-Population-By-States-2020-2023-/assets/113488502/6eeee1a1-0c40-4b6a-8ef6-6d2dfa26ff12)


# Some Insights of the report

4 pages report was created on Power BI was published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Population in 2020 = 32442600

   Number of population (Male) = 16964600

   Number of population (Female) = 15478000
   
           thus, higher number of population are Male in 2020.
           
### [2] Sabah and Sarawak have the highest number of "other bumiputera" population in Malaysia.

    This is because Sabah has three largest indigenous groups : Kadazan-Dusun, Bajau and Murut. Also, Sarawak has Iban, Bidayuh, Melanau and Orang Ulu.

    

