# mushrooms
## Objective
Our goal for this project was to create a ML model that is able to identify 
whether mushrooms are poisonous or edible based on a select number of 
biological features. These features included items like the color of the 
cap, the shape of the cap, the root type, and the odor of the mushroom.

We constructed three separate ML models including a Logistic Regression,
 a Random Forest Classifier, and an XGBoost model. Each of these models
 returned similar results where initially with all features included, we 
saw a 100% accuracy. This is due to the fact that certain bio markers in 
mushrooms will always signify a poisonous mushroom. The models were able to 
quickly identify mushroom edibility because of this.

To combat this, we reduced the features analyzed by removing features that 
had a too high of an identifying marker present. Odor, for example, was too strong at identifying whether a mushroom was poisonous or edible.

## Navigation
### Folders
There are two folders present in our repository. The first folder,
plot_htmls, contains all of the html files that our function created for 
the counts and means of features based on their chance of returning either 
poisonous or edible. Similarly, the plot_pngs folder includes all the 
png formats of those files.

### Notebook Files
We had several working notebooks, including our machine learning files, 
and our model files. The [mushroom_functions.ipynb](mushroom_functions.ipynb) 
file has the functions that were used to cleaning and editing the data.
[This file](cleaned_mushroom_df.csv) is the resulting cleaned file.