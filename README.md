# Project: Analyzing Real Estate Trends on otodom.pl
Otodom.pl is the valuable resource for analyzing real estate market trends in Poland. 
This site helps people to look for rental Apartments/Apartments for Sale, its Prices & details in Poland.

## Objective
The Objective of this Project is to analyse the real estate market trends in Poland like, 
* Average RentalPrice in various cities,
* Average SalePrice in various cities,
* Average RentalPrice based on Surface Area
* Contribution of Business & Private Advertisements
* Top 3 Luxurious Apartments in Capital city

## Step-by-Step Methodology:

1. Data Collection: 
  Downloaded CSV files from Otodom.pl website.

2.Snowflake Setup:
  Created a Snowflake account and set up the environment.
  Established a connection to Snowflake using the provided credentials.

3. Data Staging and Loading:
  Created a stage in Snowflake and uploaded CSV files to the stage.
  Defined table structures and loaded data from the stage into the tables.

4. Querying with SnowSQL:
  Performed initial data exploration and querying using SnowSQL.

5. Python Environment Setup:
  Installed necessary Python libraries for data Preprocessing, data analysis and visualization.
  Connected to Snowflake from Python using SQLAlchemy.

6. Data Analysis and Visualization:
  Executed SQL queries from Python and retrieved data into pandas DataFrames.
  Created various visualizations using Matplotlib to uncover insights.

Conclusion:
The data suggests that in Polish cities, apartment prices tend to increase with larger surface areas, with Warszawa having the highest average prices for both rent and sale. Additionally, a significant proportion of ads are posted by businesses rather than private individuals, and Mokotów, Śródmieście, and Wilanów are the top suburbs for luxurious apartments with prices exceeding 2 million PLN in Warszawa.

