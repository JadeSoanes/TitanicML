# TitanicML
Classic Kaggle ML competition - [Here](https://www.kaggle.com/competitions/titanic)

Uses the **random forest algorithm**. When used in a classification problem it takes a bunch of random features and the model decides how to classify each and then takes the majority result as an output.

Example for this titanic problem:
* For each passenger random selection of attributes are chosen, e.g., male or female, age over or under 50 etc. 
* It works with a little decision tree for each attribute, each decision tree decides whether the person being assessed would survive or not based on that feature.
* The final result for that person if the majority of all these decision trees.
