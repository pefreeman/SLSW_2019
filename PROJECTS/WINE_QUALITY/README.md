
Can you predict the quality of a wine?
---

This dataset contains information on the quality of wines along with their
acidities, their densities, etc., etc. Your job is to learn an association
(if it exists) between wine properties and the quality score of each wine.
Note that in the original dataset, the quality scores range from 1 (poor)
to 10 (excellent); to make the present analysis easier, we've collapsed this
down to BAD (quality scores <= 5) and GOOD.

---

The data are contained in wineQuality.Rdata:

predictors: 6497 x 12

   fix.acid: fixed acidity (in grams of tartaric acid per decimeter cubed)
   vol.acid: volatile acidity (in grams of tartaric acid per decimeter cubed)
   citric: citric acid (in grams per decimeter cubed)
   sugar: residual sugar (in grams per decimeter cubed)
   chlorides: chlorides (in grams of sodium chloride per decimeter cubed)
   free.sd: free sulfur dioxide (milligrams per decimeter cubed)
   total.sd: total sulfur dioxide (milligrams per decimeter cubed)
   density: 1 (= <0.99 g/dm^3), 2 (= [0.99,1] g/dm^3), or 3 (= >1 g/dm^3)
   pH: wine acidity
   sulphates: grams of potassium sulphate per decimeter cubed
   alcohol: percentage of the volume
   type: red or white

response: 6497 x 1

   -> wine quality: BAD or GOOD

