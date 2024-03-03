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

![dashboard_snapo](https://user-images.githubusercontent.com/102996550/174096257-11f1aae5-203d-44fc-bfca-25d37faf3237.jpg)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://user-images.githubusercontent.com/102996550/174074051-4f08287a-0568-4fdf-8ac9-6762e0d8fa94.jpg)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 129880

   Number of satisfied Customers (Male) = 28159 (21.68 %)

   Number of satisfied Customers (Female) = 28269 (21.76 %)

   Number of neutral/unsatisfied customers (Male) = 35822 (27.58 %)

   Number of neutral/unsatisfied customers (Female) = 37630 (28.97 %)


           thus, higher number of customers are neutral/unsatisfied.
           
### [2] Average Ratings

    a) Baggage Handling - 3.63/5
    b) Check-in Service - 3.31/5
    c) Cleanliness - 3.29/5
    d) Ease of online booking - 2.88/5
    e) Food & Drink - 3.21/5
    f) In-flight Entertainment - 3.36/5
    g) In-flight service - 3.64/5
    h) In-flight Wifi service - 2.81/5
    i) Leg room service - 3.37/5
    j) On-board service - 3.38/5
    k) Online boarding - 3.33/5
    l) Seat comfort - 3.44/5
    m) Departure & arrival convenience - 3.22/5
  
  while calculating average rating, null values have been ignored as they were not relevant for some customers. 
  
  These ratings will change if different visual filters will be applied.  
  
  ### [3] Average Delay 
  
      a) Average delay in arrival(minutes) - 15.09
      b) Average delay in departure(minutes) - 14.71
Average delay will change if different visual filters will be applied.

 ### [4] Some other insights
 
 ### Class
 
 1.1) 47.87 % customers travelled by Business class.
 
 1.2) 44.89 % customers travelled by Economy class.
 
 1.3) 7.25 % customers travelled by Economy plus class.
 
         thus, maximum customers travelled by Business class.
 
 ### Age Group
 
 2.1)  21.69 % customers belong to '0-25' age group.
 
 2.2)  52.44 % customers belong to '25-50' age group.
 
 2.3)  25.57 % customers belong to '50-75' age group.
 
 2.4)  0.31 % customers belong to '75-100' age group.
 
         thus, maximum customers belong to '25-50' age group.
         
### Customer Type

3.1) 18.31 % customers have customer type 'First time'.

3.2) 81.69 % customers have customer type 'returning'.
       
       thus, more customers have customer type 'returning'.

### Type of travel

4.1) 69.06 % customers have travel type 'Business'.

4.2) 30.94 % customers have travel type 'Personal'.

        thus, more customers have travel type 'Business'.
