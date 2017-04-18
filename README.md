# Udacity Data Visulization

## Summary

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. Public data containing demographics and passenger information from part of 2224 passengers and crew is availabe from Kaggle. This project is to create data visulizations to explain how survival is related with a passenger's characters. Some of the characters included in the data set are passenger's name, sex, boarding class, age, ticket number, fare rate, cabin etc. This project will be focused on the relationship of sex and boarding class with survival. 


## Design

In lesson 2 I discovered that the survival is closely related with gender and passenger's class. Both gender and passenger's classes are categorical values, so I choose to plot as bar chart. In order to compare the number of survived and non-survived for each gender, I choose a stacked bar chart using series to color survived and non-survived differently. As summary, I also plot survival rate so it's quick and easy to convey the conclusion. I plot survival for gender and passenger's class individually, then plot both gender and passenger's class as variables. 

Based on my feedbacks, I changed the order the plots, and now survival rate plot followed it's stacked bar plot showing number of survived or died people. I also added a "Count" column in the end of data sheet with constant value 1, so that the tool tip won't show "Survived" twice with different values. I also customize the tool tip for survival rate to make it easier to read. Legend and what each value represents are added to the stacked bar plots. I also add some conclusive phrase and graph titles to make it easy for audience understand the message. 

## Feedback

### Feedback 1: 
There is no legend on the graph, it's difficult to know what each color represents especially for those stacked bar plots.  

### Feedback 2: 
When mouse over on the column, there are two "Survived" labels with different numbers which is confusing.

### Feedback 3: 
I can see what the graphs are trying to say by reading each plot point by point. It should be easier to understand by adding some conclusive phrase or titles etc along the graphs. 


