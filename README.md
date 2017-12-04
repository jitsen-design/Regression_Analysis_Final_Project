## Correlation and Regression Analysis for Movies

This analysis is part of an online course on regression and correlation which I completed. The data has been collected randomly based on all data available on two motion picture databases prior to 2016. The objectives of the analysis are given below:

What is the definition of a 'popular' movie? We can use both the audience score as well as critics' score to measure a movie's popularity. We can also consider the level of interest the public has in a movie, by looking into the number of votes a movie received ( both favorable and unfavorable). For this exercise, We will consider 'audience_score' as the primpary measure for a movie's popularity. We should ask the following questions in determining which variables have a significant relationship with a movie's popularity. 


1)Does audience score have a high correlation with the followingt numerical variables?
  1.Critics' Score
  2.Runtime
  3.IMDB Number of Votes
  4.Release Month
  5.Release Year
  

2)Which of the following categorical variables contribute significantly to the audience score?
  1.Genre
  2.Best Picture Win?
  3.Best Director Win?
  4 Best Actor Win?
  5.Best Actress Win?

You will need to install R. It is also recommended that you install R Studio, and run both data file and code through R Studio. 

Install R: Go to https://cran.r-project.org/ and follow the link for your operating system.
Install RStudio: Go to https://www.rstudio.com/products/rstudio/download/ and click on the installer link for your operating system.

Also install the following packages and libraries in this sequence:

install.packages("devtools")
library(devtools)

install.packages("dplyr")
install.packages("rmarkdown")
install.packages("ggplot2")
install.packages("broom")
install.packages("gridExtra")
install.packages("shiny")
install.packages("cubature")
install.packages("dplyr")
install.packages("ggplot2")
install.packages("GGally")
install_github("StatsWithR/statsr")

Once you open R studio, load data file 'movies.Rdata'



