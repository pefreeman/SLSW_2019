
The subdirectories contain eight different project datasets, some of which involve regression and the rest of which involve classification. See the README.md files within each subdirectory for more information.

The subdirectories: BLOG_POST, CIVIL_WAR, DIAMOND, EMLINE_MASS, FOREST_FIRE, HOUSE_VALUE, MOVEMENT, WINE_QUALITY

The datasets: blogPost, civilWar, diamond, emline, forestFire, houseValue, movement, wineQuality

To load a dataset into R:

load(url(https://raw.githubusercontent.com/pefreeman/SLSW_2019/master/PROJECTS/subdirectory/dataset.Rdata))

Replace "subdirectory" with an actual subdirectory name, as given above, and replace "dataset" with the matching dataset name. Once a dataset is loaded, you should see the variables `predictors` and `response` in your global environment. The README file in each subdirectory gives some documentation about what the variables represent.

Each SLSW group will be responsible for analyzing one of the datasets and presenting the results incrementally "in class" via slides and finally via poster on Wednesday, July 10th.

That said, each of you should feel free to practice on as many of these datasets as you wish, both during and after the workshop.

