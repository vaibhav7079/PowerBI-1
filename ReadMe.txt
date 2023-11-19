Business Context/Summary:
The objective of the exercise is working and managing multiple tables. As part of this exercise, we are loading the data from multiple sources
and defining and managing relationships between them. We will be using the DAX syntax to enhance our dataset.



Situation:
We have been provided with retail data. the data are in 4 disparate files. Our eventual goal is to make a high level dashboard with different cuts, and some insights. As a first step, we need to get all 4 tables in your data model and ensure the relationships between the tables are well defined for further use. We  also requir to add some fields in the data - to enable the different views - Net Units, Weekday vs Weekend performance, etc.



Tasks:
1: Loaded all the files, one by one into the data model


2: Droped records from table ‘PinCode-Geo’ where ‘Zone’ is missing. Droped records from ‘Mod3_Raw_CityTier_v0 1’ where ‘CityTier’ is missing.

3: For the common columns between tables, make sure the relationship is present. For the table ‘Mod3_Raw_CityTier_v0 1’, make sure the ‘City’ field has a relationship with ‘City’ from ‘PinCode- Geo’ table

4: Using DAX formulas, created a new column ‘Net_Units’ as difference of ‘Units’ and ‘Cancelled_Units’ in the sale table

5: Renamed ‘City’ to ‘City_Old’, created new column ‘City’ with only the city name i.e. removing the country part; from the two files ‘‘Mod3_Raw_CityTier_v0 1‘ and ‘PinCode-Geo’.
6: Created a field called ‘OrderDayOfWeek’ which contains the day of week, e.g. ‘Monday’

7: To be able to look at weekly trends, using DAX formulas, created a field called ‘OrderWeekStart’ which contains the date for the start of the week of sale.


8: Updated the relationships to ensure all tables are connected as expected

9. Created different analysis/reports like
-	Total revenue, Total quantity, Total cancelations, number of customers, number of transactions, by Month, week, weekday, product group, city, zone, city tier etc.. 

10. Created Dashboard with above analysis
