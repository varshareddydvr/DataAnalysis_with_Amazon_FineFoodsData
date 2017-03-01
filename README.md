# Data Analysis with Amazon Fine Foods Data

## Exploring and preparing the data: 
Amazon Fine Foods reviews data set is from Stanford Large Network Dataset Collection. This dataset consists of around 500,000 reviews of ne foods from amazon for more than 10 years, including all reviews up to October 2012. Reviews include product and user information, ratings, and a plaintext review.


##Collecting data: 
To begin with, we import the data in csv format to data frame. We only consider two attributes, which are Score and Summary. Since Score is a categorical variable, it would be better to convert it into a factor.
