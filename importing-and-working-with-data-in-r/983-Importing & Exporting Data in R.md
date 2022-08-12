## Learning Objectives

* Importing .CSV Files in R
* Importing .TXT Files in R
* Export Data From R

## read.csv( )

To read a csv file in R, we use read.csv( ) function. To know more about this function, execute given code in R.

`help("read.csv")`








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_b81ed0d183c54dc4ac1c836b6e572e3e.png)






* There are various methods to import a file in R like
  * **file.choose()** helps you to chose the file. Once you execute the given command in R, you will get options to choose a csv file from your local machine.  
`data = read.csv(file.choose(), header = TRUE)`
  * You can pass the location where your file is located  
`data = read.csv(file = "D:/LungCapData.csv", header = TRUE)`

Note: You can set header as TRUE if your file contains first row as the name of the variable.

* Similar to read.csv() function there are two more functions that help you import data in R.
  * read.table()
  * read.delim()
* Use help() function in R to know more about these functions
* We can read .xls or .xlsx file in R using the readxl package.
* In the video coming up, the tutor will discuss following things in the hands-on tutorial:
  * How to import CSV data into R? We will be using "read.table" function to import comma separated data into R
  * How to import txt data file into R? You will learn to use "read.delim" function to import the tab-delimited text file into R
  * You will also learn to use "file.choose" argument for file location, "header" argument to let R know the data has headers or variable names and "sep" argument to let R know how the data values are separated.

### Import CSV or TXT Data in R













<iframe width="560" height="315" src="https://www.youtube.com/embed/qPk0YEKhqB8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
















### readxl package in R

* The readxl package makes it easy to get data out of Excel and into R and clean up the data before importing, thanks to the dedicated work of those behind readxl - Hadley Wickham and Jenny Bryan!

  ▶︎ With the readxl package in RStudio you can easily import both xlsx and xls files into R from a local file or a URL

  ▶︎ With this RStudio feature you can easily rename your dataset before importing data into R

  ▶︎ You can change column data types when importing data into R

  ▶︎ Using RStudio to import Excel data, you can choose which Excel worksheet to import to R

  ▶︎ In addition, you will be able to decide which rows of your Excel file to read into R and skip the first X rows

  ▶︎ We will also be able to limit the number of rows imported into R

  ▶︎ readxl package in RStudio will let you skip columns of data when importing Excel data in R

  ▶︎ There is also an option to deal with the missing values in your excel data file and select NA identifiers when importing data into R






<iframe width="560" height="315" src="https://www.youtube.com/embed/JYVWufSQ4OI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>









## Export Data From R

* The most flexible command to export data from R is write.table()





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_bbfe6451303842be97392c6adf5cd423.png)





* You can use help() function in R to know more about this command
* Some other commands that are used to export data from R are:
  * write.csv2()
  * write.table()








<iframe width="560" height="315" src="https://www.youtube.com/embed/WjpcbmcJjjM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>