## Learning Objectives

* Sort/Select Data in R
* Logical Statements in R
* cbind & rbind functions in R



## Introduction

* When working with a large data set, you might only be interested in a small portion of it. How do you sort through all the variables and observations and extract only the data that you need? R has several ways of sorting and selecting data in a process called "subsetting." Brackets in R lets you select or subset data from a vector, matrix, array, list, or data frame.
* R's operators can be summarized as:
  * [ for subsets,
  * [[ for extracting items, and
  * $ for extracting by name.





## Selecting a Subset From Dataset

We already have our dataset **LungCapData** loaded in the R environment. Let's say we want to see the details of male patients. We can select the required data, as shown in the screenshot.






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c0ac7b027bb041f0896f3b747d0b226b.png)





* In the video coming up in the next slide, the tutor will discuss
  * Subsetting data from a vector and matrix in R
  * Subsetting data from a dataset with given conditions












<iframe width="560" height="315" src="https://www.youtube.com/embed/jGf7WNh-LX8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>









### True / False Indicator for Observations

Let's say we want to check if the observations satisfy the given conditions as TRUE or FALSE indicator. Suppose we want to create a TRUE/FALSE indicator vector for those who are female and they smoke. So if both the conditions satisfy, then return TRUE else FALSE.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f7585a87f68f46f1a57486a0fc5d7818.png)




### cbind

We can attach vectors or matrices in a column-wise fashion using the **cbind** command and in a row-wise fashion using the **rbind** command. Don't worry; you will get more clarity by seeing an example.






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f48046d78c1343b0916acfc0f65d3520.png)





### rbind







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_244cea02f9274138a7f44ce06a7b6786.png)






* In the video coming up in the next slide, the tutor will discuss the following topics:
  * how to create a logical vector or variable in R Statistical Software
  * how to turn True or False indicators into 0's and 1's in R using the "**as.numeric**" function
  * how to use multiple logical statements within an R command/function to have a logical vector answering multiple questions (step-by-step example)
  * how to attach vectors or matrices in a column-wise fashion using the "cbind" function or in a row-wise fashion using the "rbind" function in R
  * two different ways of cleaning R's workspace: using RStudio's menu or "**rm**" command/function





<iframe width="560" height="315" src="https://www.youtube.com/embed/NFaK1Qn4u3A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>