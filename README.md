# Rent-price-pridction-
A multiple regression to predict rental prices for properties in a large metropolitan area, incorporating a mix of quantitative, categorical, and temporal variables. The model should account for interactions between variables, seasonality, and location-specific trends to deliver accurate, interpretable predictions.
# ABOUT DATASET
<BR>
Dataset Specification
<br>
Here’s what the dataset will include:
<br>

Property Information:
<br>

Property_ID: Unique identifier for each property.
<br>
Size_sqft: Size of the property in square feet.
<br>
Bedrooms: Number of bedrooms.
<br>
Bathrooms: Number of bathrooms.
<br>
Property_Type: Type of property (e.g., "Apartment," "House," "Condo," "Townhouse").
<br>
Age_Years: Age of the property in years.
<br>
Renovation_Year: Year of last renovation (some entries will have missing values to simulate messy data).
<br>
Location Data:
<br>

Latitude and Longitude: Spatial data for property location.
<br>
Neighborhood_Safety_Index: Safety index of the neighborhood (scale from 1 to 10).
<br>
Proximity_to_Public_Transport_km: Distance to the nearest public transport in kilometers.
<br>
Walkability_Score: Index measuring walkability (scale from 1 to 10).
<br>
Zoning: Zoning classification (e.g., "Residential," "Commercial," "Mixed-use").
<br>
Economic and Social Indicators:
<br>

Median_Income_Area: Median income of the area in thousands of dollars.
<br>
Unemployment_Rate: Unemployment rate in the area (as a percentage).
<br>
School_District_Rating: Rating of the local school district (scale from 1 to 10).
<br>
Crime_Rate_per_Capita: Number of crimes per capita in the neighborhood.
<br>
Temporal Data:
<br>

Monthly_Rent_2020_to_2024: Monthly rent price over a 5-year period, capturing seasonality.
<br>
Month: Month of the rent record (e.g., "2023-05" for May 2023).
