Course Project: Shiny Application and Reproducible Pitch
========================================================
author: 
date: 
autosize: true

About the Course Project
========================================================

This is a deliverable for the course Developing Data Products as part of the Coursera Data Science Specialization.

Instructions:

1. Write a shiny application with associated supporting documentation. The documentation should be thought of as whatever a user will need to get started using your application.

2. Deploy the application on Rstudio’s shiny server.

3. Share the application link by pasting it into the provided text box.

4. Share your server.R and ui.R code on github.


How to use the application
========================================================
- Using the data provided by Iris dataset, we separate the sample into different groups according to their characteristics by using the K-means algorithm

- The application is running on (https://joaquinsepulveda.shinyapps.io/peer/?_ga=2.28119996.1458695858.1624210026-1817511704.1624210026)

- ui.R, and Server.R Code in my github repository (https://github.com/JoaquinSepulveda1/Course-Project-Shiny-Application-and-Reproducible-Pitch)

Iris dataset
========================================================

The Iris Dataset contains four features (length and width of sepals and petals) of 50 samples of three species of Iris.


```
  Sepal.Length    Sepal.Width     Petal.Length    Petal.Width   
 Min.   :4.300   Min.   :2.000   Min.   :1.000   Min.   :0.100  
 1st Qu.:5.100   1st Qu.:2.800   1st Qu.:1.600   1st Qu.:0.300  
 Median :5.800   Median :3.000   Median :4.350   Median :1.300  
 Mean   :5.843   Mean   :3.057   Mean   :3.758   Mean   :1.199  
 3rd Qu.:6.400   3rd Qu.:3.300   3rd Qu.:5.100   3rd Qu.:1.800  
 Max.   :7.900   Max.   :4.400   Max.   :6.900   Max.   :2.500  
       Species  
 setosa    :50  
 versicolor:50  
 virginica :50  
                
                
                
```

Brief Exploratory Analysis
========================================================

- Average Petal Length for each species

```
    setosa versicolor  virginica 
     1.462      4.260      5.552 
```
- Average Sepal Length for each species

```
    setosa versicolor  virginica 
     5.006      5.936      6.588 
```
- Average Sepal Width for each species

```
    setosa versicolor  virginica 
     3.428      2.770      2.974 
```
- Average Petal Width for each species

```
    setosa versicolor  virginica 
     0.246      1.326      2.026 
```


