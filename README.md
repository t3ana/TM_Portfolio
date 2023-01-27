# Data Science Projects Portfolio

A collection of Python projects completed during my undergrad Data Science minor.

These projects consist of basic concepts of Python and Machine Learning.


## Description

This portfolio includes projects that were completed as group collaboration, individual projects, and graded assessments from my data science classes during my undergraduate studies. Currently the projects presented have a variety of topics. Some more basic in order to display the grasps of understanding the basic concepts of Python. While others are more intermediate projects that include the use of machine learning and using real life data. All projects were completed in Google Colab which was the primary resource we used to complete our coding in class.

Currently, I am obtaining my Masters in Business Analytics. Which will give me more experience using the languages Python and R. In addition to that, other software skills we will learn are AWS, Spark, Hadoop, Pig, and Hive. This portfolio will be updated as new projects are completed and new skills are learned.

## Topics

### Confusion Matrix

https://archive.ics.uci.edu/ml/datasets/haberman%27s+survival

Using the Haberman data, a Confusion Matrix was created to determine who lived, and who died based on patients who had undergone surgery for breast cancer.


### Decision Trees and Support Vector Machine

In this project, I was tasked with completing several assignments based on concepts we had gone over in class. We were provided the teaching assistant evaluation dataset to complete each task. For the first task, a scatterplot was created to denote the three different classes, and have it based on the course and class size. 

For the second task, I created a decision tree based on all the features provided such as:
* Were they a native English speaker?
* How is the course instructor? 
* How is the course itself?
* And When was it being taught?

These were deciding factors on whether or not someone would take the class. 

For task number three, I needed to train a Support Vector Machine(SVM) on course and class size while denoting each class with a different color. For the Support Vector Machine, I used a radial basis function(RBF) kernel with a gamma, of 0.55. Once complete, I displayed the output in a graphic visualization.

For the last task, I needed to make another decision tree, but train the data on an 80/20 split.

### Dendrograms

For the Dendrograms collaboration, it was the basic application completed using a dummy array. This allowed us to understand the basics behind the code before applying it to real data. When incorporating this concept with real data we used the Scotch dataset.

### Index

For my indexing assignment, I used the White Wine Quality dataset and was tasked with finding the first and second closest wine for each wine in the data set. This was done by creating a matrix and filling it with each wine’s nearest match, then proceeding to make a loop to find the first and second choice index before printing it out. This was completed in two ways. The first one, printed out the non-labeled column, which was the first column. This made it confusing to read there wasn’t a clear distinguishment between the wines. So, I created an index number column. This meant when the statement was printed out, it would be easier to compare the wines. As it would be the number that corresponds to the wine and not just the value from the first attribute. If this wasn’t done, some of the wines would look identical as they had the same value in the first column.

### K-Means

K-means was a simple assignment. We used blobs/dummy variables to get a gist of how K-means worked before printing out the SSE and other descriptive statistic factors. This was in addition to the visualization of the clusters created with the centers marked. 

We did several interpretations of this before using a real dataset. The data we used was called Wine which was one of the datasets already programmed in Python. With this dataset, we also compared the homogeneity and completeness. We then looked at the results to determine whether or not this was a good interpretation of the data.

### Linear Regression in R

Although we worked predominantly with Python in my data science classes, we did go over R and worked with it a little bit. In this project, we reviewed the Swiss dataset and created a box plot, scatterplot, and linear regression based on education and agriculture. This was just for us to get a glimpse of how similar, but different R and python can be from one another.

### Kaggle Project

My final project for my last data science class was completing the Titanic Kaggle competition. Within this competition, you needed to create code that helps you separate passengers, those who died and those who lived on the Titanic. You were given a training and test dataset to complete the competition. For this competition, I pre-processed the data and looked to see if there was anything that needed to be cleaned. Once that was complete, I looked at simple visualization such as bar charts to get familiar with the data before trying different models to get the best accuracy on survival. I used models such as Random Forest and SVM then used cross-validation scores to test their accuracies. Based on the results, I would choose the better result between the two and use that as my final submission. By the end of this project, I decided to go with the Random Forest Model, which had the better results of the two.
