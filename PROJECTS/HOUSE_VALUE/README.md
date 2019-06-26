
Can you predict the median house value for these locales?
---

This dataset contains information about house values in particular tracts.
Specific state names and such were scrubbed from the original dataset but
latitude and longitude remain. Your goal is to learn an association between
the population, location, age, and number of bedrooms, etc., and a house's
median value.

---

The data are contained in houseValue.Rdata:

predictors: 10605 x 13

| name | description |
| ---- | ----------- |
|  POPULATION | population of the tract in question |
|  LATITUDE | latitude of the tract |
|  LONGITUDE | longitude of the tract |
|  Total_units | the total number of housing units |
|  Vacant_units | the total number of vacant units |
|  Median_rooms | median number of rooms per unit |
|  Mean_household_size_owners | average number of people in owned homes |
|  Mean_household_size_ranters | average number of people in rented homes |
|  Owners | the percentage of units that are owned |
|  Median_household_income | self-explanatory |
|  Mean_household_income | also self-explanatory |
|  Built_1990_or_later | the percentage of units built after 1989 |
|  Bedrooms_4_or_more | the percentage of units with more than three bedrooms |

response: 10605 x 1 |

   -> median unit value

