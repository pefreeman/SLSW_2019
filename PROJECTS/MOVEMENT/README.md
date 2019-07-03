
What elements of a movement indicate whether or not it will be successful?
---

This dataset contains information about 267 movements around the world, both
violent and non-violent, and your goal to learn the association between
measures of violence, democracy, etc., and the outcome of the movement. A
secondary goal is to predict the probability of success for those movements
for whom the outcome is ambiguous.

---

The data are contained in movement.Rdata:

predictors: 218 x 8

   nonviol: 1 for non-violent movements, 0 otherwise
   democracy: measure of democracy, from -10 (undemocratic) to 10 (democratic)
   sanctions: 1 if country was under international sanctions, 0 otherwise
   aid: 1 if country received aid to deal with the movement, 0 otherwise
   support: 1 if the *movement* received foreign aid, 0 otherwise
   viol.repress: 1 if the government utilized violence, 0 otherwise
   defect: 1 if substantial portions of government forces defected, 0 otherwise
   duration: duration of movement, in days

response: 218 x 1

   -> 1 if movement fully achieved its aims; 0 if movement failed

predictors.half: 49 x 8

   same as predictors, but for movements viewed as partially achieving their
   aims. in the original dataset, the response values for these movements
   was 0.5, hence the "half" in the variable name.

id: 218 x 8

   identifier information for each movement in predictors variable

id.half: 49 x 8

   identifier information for each movement in predictors.half variable

