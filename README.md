# Introduction to essential packages and concepts in R for Data Science

First of all, we will familiarize ourselves with the "packages" concept in `R`. `R` packages are collections of functions and data sets developed by one specific person or community. They increase the power of R by improving existing base R functionalities, or by adding new ones.

One of the biggest strengths of `R` is that it is an open project. As a result, everyone can create their own packages/suites of packages and upload to the official `R`'s reporitory, the Comprehensive R Archive Network (CRAN). Recently, CRAN has reached 10,000 packages published, and many more are publicly available through the internet.

This repository helps to cover some, or more ambitiously most of the packages necessary when it comes to dealing with datasets. Applying the philosophy of Hadley Wickham, this is an opiniated suites of packages that helps finish as many steps as possible in any customized workflow, with the highest proficiency.

Next, this repository aims to introduce the most important/common concepts of mathematics and/or data science. These concepts may be scattering inside tens of thousands of packages of `R`, so introducting the whole package may be time-consuming and unnecessary.

# Structure of the repository

The repository is organized by packages (suites of packages), followed by its sub-packages.

The first part of this repository will be dedicated to cover `tidyverse`, an opiniated sets of packages designed for data science. The tutorials include an overview of the suit, along with separate tutorials for each of the packages of its core. Finally, there will be some projects applying all of the function from different packages, as a complete work flow.

The second part of the repository will be an introduction about different parameters to quantify the correlation between two variables. It will investigate the correlation between all kinds of variables, namely continuous/numerical and categorical/discrete variables.

There will be one folder dedicated for each notebook/tutorial. Each of these files will contain

+ One `RMarkdown` file
+ One `HTML` file knitted from the markdown file
+ One `.bib` file indicating references for the respective markdown file

# Technical requirements

All of the tutorials/source code here are written by `RMarkdown`, which is a part of `RStudio`. As a result, in order to display the file or replicate the work/code done in the tutorials, the installation of `RStudio` is required. `Rstudio Desktop` (with Open Source License) can be downloaded at: https://rstudio.com/products/rstudio/download/.

Moreover, as there are different packages installed, and each of them would be compatible from a certain version of `RStudio`, it is also recommended to install the latest version of the software. Currently, the latest version is `1.2.5019`, published on November 1st, 2019.

At the beginning of each tutorial, there will be a script that checks whether the required packages for that particular tutorial, and then install the missing packages. For the sake of the publication of tutorials, in the source code, that chunk is labeled as `eval = FALSE`, which means that while rendering the file into `HTML`, that chunk will not be executed. If you want to replicate or apply the tutorials to similar situations,you are encouraged to run that chunk, simply by deleting `eval = FALSE`, or change to `eval = TRUE`.  
  
# Publication
 
All of the tutorials within this repository will be upload on `RPubs`, a website that allows users to upload RMarkdown files under the HTML format. The links to the tutorials are listed below:
 
+ Introduction to `tidyverse`

  + **Part 1: An overview** : https://rpubs.com/hoanganhngo610/553547

+ Correlation between variables

  + **Correlation between numerical variables** : https://rpubs.com/hoanganhngo610/556786

  + **Correlation between discrete (categorical) variables**: https://rpubs.com/hoanganhngo610/558925


# Acknowledgement

The author would like to express my special thanks of gratitude to 

+ Professor Erwan Le Pennec, CMAP, Mathematics Professor at École Polytechinque, in charge of the course MAA204: Introduction to Statistics
+ Clément Mantoux, CMAP, Teaching Assistant of the course MAA204: Introduction to Statistics

For further information or concerns, please contact the author at: hoang-anh.ngo@polytechinque.edu