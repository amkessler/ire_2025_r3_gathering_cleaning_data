# IRE 2025 Conference - R3: Gathering and Cleaning Data

## Loading What You'll Need

**To install the packages we'll use, run this line of code in the console:**

`install.packages("tidyverse", "babynames", "rvest", "janitor", "readxl", "googlesheets4", "usethis")`

**Then to load this project repo with the class materials, run this line:**

`usethis::use_course("https://github.com/amkessler/ire_2025_r3_gathering_cleaning_data/archive/refs/heads/main.zip")`

## What We're Doing

In this session, we're going to show you two things:

**1. The many ways to get data in RStudio!** *We'll practice loading data from:*

-   a built-in R dataset

-   an R package

-   a local csv file

-   an Excel file

-   an html table.

-   a Google Sheet (if the wifi cooperates)

**2. Some data cleaning tricks in R!** *We'll practice:*

-   cleaning up column names

-   parsing and manipulating strings

-   correcting erroneous values

-   converting data types

## What You'll Get Out of This

-   You will leave here understanding some basic loading and cleaning data concepts in R, a list of helpful packages, and some resources for further learning.

## R packages We'll Use

We'll utlize the goodness of several packages for this class.

They are:

-   The [babynames](https://cran.r-project.org/web/packages/babynames/index.html) package for loading social security babyname data.

-   The [Tidvyerse](https://www.tidyverse.org/) collection of packages. We'll be making extensive use of the readr, dplyr and stringr packages,which all load as part of the tidyverse core ([readr](https://readr.tidyverse.org/), [dplyr](https://dplyr.tidyverse.org/), [stringr](https://stringr.tidyverse.org/))

-   The [rvest](http://rvest.tidyverse.org/) package for web scraping.

-   The [janitor](https://github.com/sfirke/janitor) package for data cleaning.

-   The [readxl](https://readxl.tidyverse.org/) package for loading Excel files.

-   The [googlesheets4](https://googlesheets4.tidyverse.org/) package for reading -- and writing -- data stored in a Google Sheet.

-   The [usethis](https://usethis.r-lib.org/) package to help with loading the class project onto your local machine
