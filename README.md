# Random-Forest_identifying-attributes-causing-high-sales_company-dataset

Problem Statement:
A cloth manufacturing company is interested to know about the segment or attributes causes high sale. 
Approach - A Random Forest can be built with target variable Sales (we will first convert it in categorical variable) & all other variable will be independent in the analysis

# Ensemble method----Random-Forest using Python

## Random Forest
It also comes under Bagging Technique, But here model used is strictly decision tree.

Random Forest can be used for both classification and regression task.Random Forest is a model made up of many decision trees rather than simply averaging the prediction of trees.

The model uses two key concepts:-

a) Random Sampling of training data points when building trees.\
b) Random Subsets of features considered when splitting nodes.

It can also be used for Feature Engineering.

 **Random forest pseudocode:**
 
      1)	Randomly select “k” features from total “m” features.
              Where,  k << m
      2)	Among the “k” features,calculate the node “d” using best split point.
      3)	Split the node into daughter nodes using best split.
      4)	Repeat 1 to 3 steps until “1” number of nodes has been reached.
      5)	Build forest by repeating steps 1 to 4 for “n” number times to create “n” number of trees.

The main advantage of random forest is it eliminates *Overfitting problem* observed in Decison tree.

## Data Used :
                            Company dataset - for knowing the attribute that causes high sale using random forest.
                            
## Programming:
                              Python


**The Codes regarding  Random Forest for *classification of company data with company dataset* are present in this Repository in detail.**


