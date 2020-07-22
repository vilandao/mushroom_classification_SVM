## Mushroom classification with Support Vector Machine

Although this dataset was originally contributed to the UCI Machine Learning repository nearly 30 years ago, 
mushroom hunting (otherwise known as "shrooming") is enjoying new peaks in popularity.

Our goal for this project is to build a machine learning model that can predict whether a mushroom is poisonous or edible based various mushroom features!

### About the dataset
The dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom 
drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, 
or of unknown edibility and not recommended. This latter class was combined with the poisonous one.

Some of the features provided are: cap shape, cap surface, cap color, odor, gill size, gill color, stalk shape, stalk root, veil type, ring number, population, etc.

### Kernel content
1. Load an clean the dataset
2. Exploratory data analysis
3. Build and compare different predictive machine learning algorithms

### Conclusion
After trying 5 different algorithms (Logistic regression, Decision tree classifier, KNN classifier, Random forest classifier, and Support Vector Machine), 
we conclude that Decision tree, Random forest, and KNN gave us the highest R-squared score.
