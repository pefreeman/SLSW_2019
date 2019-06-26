
Can you predict whether a country is undergoing a civil war?
---

This dataset contains information about whether a civil war was occurring at
a particular time in a particular country. Country and time information have
been purposely scrubbed from the dataset, as your goal is simply to learn an
association (if it exists) between measures of schooling, exports, population,
etc., and whether a civil war was occuring at the point in time when the data
were gathered.

---

The data are contained in civilWar.Rdata:

predictors: 741 x 7

| name | description |
| ---- | ----------- |
|  exports | a measure of the dependence of a country on commodity exports |
|  schooling | percentage, school enrollment rate for males (*) |
|  growth | annual GDP growth rate |
|  concentration | population concentration, from 0 to 1 (all in one city) |
|  lnpop | natural logarithm of the country's population |
|  fractionalization | index measuring divides on ethnic/religious lines |
|  dominance | 1 if one ethnic group dominates the country, 0 otherwise    |

response: 741 x 1

   -> 1 if a civil war was occurring when the data were gathered, 0 otherwise

