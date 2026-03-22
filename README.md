# Tableau_AirBnB
Tableau Dashboard visualizing AirBnB listing data from 2016.

## Dataset
A Pre-processed dataset still containing all the needed data is given under the name "Tableau_Full_Project_AirBnB_noReviews". The full dataset can be found on Kaggle: https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset.

## Tableau Dashboard
The Tableau Dashboard is posted on Tableau public and can be found here: https://public.tableau.com/app/profile/sem.de.vries/viz/AirBnB_Full_Project_17741855305670/AirBnBFullDashboard?publish=yes

As this dashboard looks different from the one on my system, a picture of the dashboard on my computer is shown below:
<img width="1658" height="851" alt="image" src="https://github.com/user-attachments/assets/fa3cb7ae-8ae6-4019-9aaf-446ec20fe1cc" />

## What does the data tell us?
Average Yearly Return per N Bedrooms
  - Shows total yearly revenue per listing (SUM(Price) / COUNT(Id)) by number of bedrooms
  - Clear upward trend: more bedrooms → higher yearly return
  - 6-bedroom listings generate the highest returns

Average Price for N Bedrooms
  - Displays average price per listing by bedroom count
  - Strong positive relationship: more bedrooms → higher average price
  - Price increases steadily from 1 to 6 bedrooms

Count of Listings with N Bedrooms
  - Distribution of listings across bedroom counts
  - Majority are 1-bedroom listings, sharply decreasing as bedrooms increase
  - 5–6 bedroom listings are rare

Map Price & Zipcode
  - Geographic distribution of prices by zipcode
  - Highlights spatial variation in pricing
  - Some areas clearly more expensive than others

Price by Zipcode
  - Bar chart ranking zipcodes by average price
  - Identifies most and least expensive areas
  - Large variation across zipcodes (roughly ~70 to 210+)

Revenue per Week
  - Time series of total revenue over weeks
  - More Revenue during summer and winter break
Filters (right side)
Bedrooms and Zipcode filters allow slicing the dashboard
Enables focused analysis on specific segments
