## Reproducible Research
This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals throughout the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.

The documents in this repo are:
* A R markdown file of the data analysis. (project1.rmd)
* A html file corresponding to the rmd file. (project1.html)
* Plots in the document.

##Data

The data for this assignment can be downloaded from the course web site:

* **Dataset**: [Activity monitoring data](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip) [52K]

The variables included in this dataset are:

* **steps**: Number of steps taking in a 5-minute interval (missing values are coded as NA)

* **date**: The date on which the measurement was taken in YYYY-MM-DD format

* **interval**: Identifier for the 5-minute interval in which measurement was taken

The dataset is stored in a comma-separated-value (CSV) file and there are a total of 17,568 observations in this dataset (61 days * 288 time intervals per day).


This assignment creates a report that answers the following questions:
* What is mean total number of steps taken per day?
* What is the average daily activity pattern?
* Imputing missing values
* Are there differences in activity patterns between weekdays and weekends?

To do the project we need to do these tasks:
* Load the data (i.e. read.csv())
* Process/transform the data (if necessary) to ansuer the qustions above.
* Make the Plots
* Make a report in a R markdown document that can be processed by knitr and be transformed into an HTML file.

