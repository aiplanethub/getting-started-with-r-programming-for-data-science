## Learning Objectives

* Basic Functions to check data in R
* Working with Variables

### Dataset

We will be using the Lung patient dataset. You can download the dataset from the given links:

* [Tab Delimited Text File (CSV)](https://drive.google.com/file/d/12bmZ5M2YQE\_4KrQQ\_3ILFvcDaSHqbH\_2/view?usp=sharing)
* [Excel File](https://drive.google.com/file/d/1bIReYPxxxrDTzJqJnUY5JV2z-51-apVB/view?usp=sharing)

## Basic Functions to Check Data in R

### head( )

* Once you have loaded (or imported) data in R, we can check how our data looks.

* We can take a look at the first six observations of the data using the head() function in R. See the screenshot below




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a226e181ac69464a835c9e98f0eb0a05.png)




### tail( )

* We can take a look at the last six observations of the data using the tail() function in R. See the screenshot below





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2d6f63dd8756469fb3c0316917aa4875.png)




### Checking Particular Records

* We can use the concatenate function ( i.e. c( ) ) to select some random records.






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_08ae6c4578e842e5bea2658f08fae337.png)





### Try Yourself!

If you remember from earlier lesson, we had used colon ( : ) to generate a sequence. Use this to display some data.

### Solution to Previous Problem







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_5bb96f9ac66b4e1b9ac3371b035986d4.png)



### Display the Column Names of the Data

* We can use the names() function to display the column names of the data. See the screenshot below


![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cf7db6e7bb0d40119241af57fcec7fe3.png)

## Working With Variables

### Selecting A Single Column from Data

To select a single variable or column from the dataset we use **$**. For example,

LungCapData$Age







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_bdc13e5bc325481da2ba751d4ef32a61.png)




These are the ages of patient.

### Mean of a Variable

We can use mean() function to calculate the mean of the data points of a variable.

mean(LungCapData$Age)








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cc7eca1c1e414ed2bfaadbb5b5c4ff69.png)



If you access column directly, it will throw error

### Summary of the Dataset

To get the statistical summary of the data we can use summary() function in R.

summary(LungCapData)





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_65157c11d9f842cbb30490412cbb9f78.png)


You can see the summary of **numerical variables** include minimum value (min), quantiles, mean, etc. while that of c**ategorical** (or **character** or **factor**) variables include total data points count, their class and mode.

* In the video coming up in the next slide, the tutor will discuss the following things in the hands-on tutorial:

  ▶︎ How to check variable names for datasets in R?

  ▶︎ How to extract a variable from a dataset in R?

  ▶︎ How to check the variable type (numeric or categorical) in R?

  ▶︎ How to ask R for different levels/categories of a categorical variable?

  ▶︎ How to produce summary for variable in R? summary function in R will produce summary of variables based on their type, for example numeric values will be summarized by mean, median and quartiles, and factors or categorical variables will be summarized as frequencies.



<iframe width="560" height="315" src="https://www.youtube.com/embed/1BcGnHwUT6k?start=21" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>