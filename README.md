# README

Welcome to this Git repository where you can produce the base plot that turned into this: 
![The U.S. Supreme Court](https://github.com/whiteellie/supreme-court/blob/master/outputs/mean_mq_scores.png)


This repository contains an R Markdown file that you can use to analyze data or create reports. To use the R Markdown file, you need to have the following:

1. R installed on your computer
2. RStudio (an integrated development environment for R) installed on your computer
3. The necessary R packages installed on your computer

## Installation

### 1. Install R

If you haven't already done so, please download and install R from the following website:

https://cran.r-project.org/

### 2. Install RStudio

Once you have installed R, you should then download and install RStudio from the following website:

https://www.rstudio.com/products/rstudio/download/

### 3. Install the necessary R packages

To run the R Markdown file, you will need to install the following packages:

- `ggplot2`
- `knitr`
- `rmarkdown`

To install these packages, open RStudio and run the following commands in the console:

```
## Install the necessary packages
install.packages("ggplot2")
install.packages("knitr")
install.packages("rmarkdown")
``` 

You can customize the package list as per your requirements. Simply include this code block in your markdown file, and the packages will be installed when the code is executed.

## Usage

### 1. Download the R Markdown file

You can download the R Markdown file from this Git repository by clicking on the "Download" button or by cloning the repository using the following command:

git clone https://github.com/whiteellie/supreme-court.git


### 2. Open the R Markdown file in RStudio

Once you have downloaded the R Markdown file, open it in RStudio by navigating to the file location and double-clicking on the file.

### 3. Run the R Markdown file

You can run the R Markdown file by clicking on the "Knit" button in RStudio, or by running the following command in the console:



## Conclusion

Thank you for using this Git repository! We hope that you find the R Markdown file useful for your data analysis or report writing needs. If you have any questions or feedback, please feel free to contact me white.elaheh@gmail.com.



## Want to Update with new data?

Data was last updated 05/22/2023.

Justices.csv is a copy pasted table from: http://scdb.wustl.edu/documentation.php?var=justice#norms

SCDB_2019_01_justiceCentered_Citation.Rdata includes justcie centered data downloaded from: http://scdb.wustl.edu/data.php

measures.csv includes segal-cover and martin-quinn scores downloaded from: http://scdb.wustl.edu/data.php?s=5
This is old data so use this instead 

mqscores.csv was downloaed from: https://mqscores.lsa.umich.edu/measures.php