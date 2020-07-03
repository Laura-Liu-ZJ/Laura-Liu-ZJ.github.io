---
layout: post
title: Project 2
---

## Outline
This project includes seven parts, the first part is a brief introduction of the data, the purpose, and the methods I used in this project. Second part is the detailed description of data, including potential predictors I cared about and fitted linear variables selected by mallow’s cp and BIC. The thrid part is about summarizations, which contains the correlation analysis of fitted linear variables, summary statistics of potential predictors, and calculation of accuracy for original data by contingency table.

The next part is modeling, we use logistic regression to fit our fitted data set (subset of training data set) and bagged tree to fit our training data set, and then we calculate the accuracy of each model for training data set. Then we use above model to fit our testing data set and calculate the accuracy of each model for testing data set. 

In the models comparison part, we combine the accuracy using two models for each data set. Then we calculate the misclassification rate to get the best model. And we find that the bagged tree model fit testing data set better on Monday data and Saturday data, but logistic regression fit testing data set better on other 5 weekdays data.

## Reflection
### what would you do differently? 
The automation process is a different method for me to output data.

### what was the most difficult part for you? 
I think the most difficult part is to select the potential variables because it is totally subjective, and I do not want that to influence too much on model building.

### what are your big take-aways from this project?
I have done the automation process and learned how to use mallow's cp and BIC to select variables.

## Project Content
Here is the link of [my second Project](https://laura-liu-zj.github.io/ST558Project2/).

