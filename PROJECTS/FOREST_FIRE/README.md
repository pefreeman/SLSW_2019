
Can you predict the area consumed by a forest fire?
---

This dataset contains data on forest fires that occured in Portugal during
the years 2000 to 2003 (inclusive). Your goal is to learn an association
(if it exists) between measured variables such as the "Fine Fuel Moisture 
Code" and the overall area consumed.

---

The data are contained in forestFire.Rdata:

predictors: 517 x 12

   X: coordinate from 1 (west) to 9 (east)
   Y: coordinate from 1 (south) to 9 (north)
   month: month of year
   day: day of week
   FFMC: fine fuel moisture code
   DMC: Duff moisture code
   DC: drought code
   ISI: initial spread index
   temp: outside temperature (Celcius)
   RH: outside relative humidity (percentage)
   wind: outside wind speed (in km/hour)
   rain: outside rainfall within previous 30 minutes (in mm per meter-squared)

response: 517 x 1

   -> area burned in hectares (values smaller than 0.1 rounded up to 0.1)

