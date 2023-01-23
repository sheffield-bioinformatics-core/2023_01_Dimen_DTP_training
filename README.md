# DiMeN DTP Data Manipulation and Visualisation Training

![](sbc.png)

- January 23rd - 24th, University of Sheffield
- Bartolome House, Seminar Room EG03

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2379.7129257392867!2d-1.4909138836084257!3d53.38418577957657!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4879788327d13c2b%3A0x76151ebce3e59f6!2sBartolom%C3%A9%20House%2C%20Sheffield!5e0!3m2!1sen!2suk!4v1673020230144!5m2!1sen!2suk" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

## Overview

As the data generated from high-throughput biological experiments increase in volume and become more complex, the ability to manipulate and visualise data is a highly-desirable skill in academia and industry. Whilst familiar tools such as Excel allow basic manipulations, they are often not scalable to larger datasets and are not ameanable to reproducible analysis.

R is a highly-regarded, free, software environment for statistical analysis, with many useful features that promote and facilitate reproducible research.

In this course, we give an introduction to the R environment and explain how it can be used to import, manipulate and visualise tabular data.

After the course you should feel confident to start exploring your own dataset using the materials and references provided.


## Schedule (Provisonal)

### Monday 23rd January

- 12:00 - 13:00, Arrival and Lunch
- 13:00 - 15:15 Introduction to R and RStudio
- 15:30 - 17:00 Subsetting and Filtering Data in R

### Tuesday 24th January

- 09:00 - 11:00 Introduction to plotting with ggplot2
- 11:15 - 12:30 Customising and configuring plots
- 12:30 - 13:15 LUNCH
- 13:15 - 15:00 Summarizing and joining tables

## Materials

- [Slides](https://sbc.shef.ac.uk/r-online/intro_slides.html)
- [Part 1](https://sbc.shef.ac.uk/r-online/part1.nb.html)
- [Part 2](https://sbc.shef.ac.uk/r-online/part2.nb.html)
- [Part 3](https://sbc.shef.ac.uk/r-online/part3.nb.html)

## Setup

These instructions are also described in a video:- [https://youtu.be/QIubJ8W8R4g](https://youtu.be/QIubJ8W8R4g)

1) First, install both R **and** RStudio for your operating system. 

### Windows

Install R by downloading and running [this .exe file](http://cran.r-project.org/bin/windows/base/release.htm) from CRAN. Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

### Mac

Install R by downloading and running [this .pkg file](https://cran.r-project.org/bin/macosx/base/R-4.2.2.pkg) from CRAN. Also, please install the free [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download) 

### Linux

You can download the binary files for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please install free [the RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download). 


  
2) Please download and extract (un-zip) this zip file into the directory on the computer that you wish to work in

- [https://github.com/sheffield-bioinformatics-core/r-online/raw/master/CourseData.zip](https://github.com/sheffield-bioinformatics-core/r-online/raw/master/CourseData.zip)

3) Type the following into the R console to install some extra R packages required for the workshop

```
install.packages("dplyr")
install.packages("ggplot2")
install.packages("readr")
install.packages("rmarkdown")
```



**Mac Users may get the following error message when trying to install these packages**

```
xcrun error: inactive developer path (/Library/Developer/CommandLineTools), missing xcrun at:.....

```

If this is the case, you will need to follow the instructions from this link to install "Xcode"

[https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a](https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a)

**Window users might get a message that Rtools is required. This shouldn't be necessary, but you might need it for other packages. It can be installed here:-**

[https://cran.r-project.org/bin/windows/Rtools/](https://cran.r-project.org/bin/windows/Rtools/)


4) Check your installation. You can check everything is installed by copying and pasting this into the R console

```
source("https://raw.githubusercontent.com/sheffield-bioinformatics-core/r-online/master/check_packages.R")


## Feedback

Please let us know what your thought of the course by filling-in this short feedback form

- [Feedback form](https://docs.google.com/forms/d/e/1FAIpQLSduKv0ej_bgAYrK5_5AMfZhdQiOKPYu1ZhbWzHC7v4rRDsZbA/viewform)
```
