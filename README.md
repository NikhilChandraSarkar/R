## Background
This repository is a live learning platform to get started with R, a language and environment for statistical computing and graphics.
R is a free software environment for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows and MacOS. To download R, choose the preferred Comprehensive R Archive Network (CRAN) mirror from here, <https://cran.r-project.org/mirrors.html>.

- Let's get started! First thing is first! You need to have installed R and RStudio on your computer first.
  - To Download and Install R use follwoing link and instruction,
<https://cran.revolutionanalytics.com>.
  - To Download and Install RStudio use,
<https://posit.co/download/rstudio-desktop>. 
- Secondly, you need to install and load packages on your computer. R Packages are collection of functions and data that build on base functionality of R to minimise effort and save time for statistical computing and graphics.

## How to install and Load Packages

- Use **install.packages()** to get started installing R packages. For example, install "packman" package on your computer use
**install.packages('packman')**. 

- Use **library()** function to load the packages that already installed on your computer. For example, load "packman" package on your computer use
**library(packman)**. 
 
 *Note: We need to install any package once on a computer but need to load everytime when we restart the program*.
 
 ## Advanced way to install multiple Packages together
 
 Use **p_load()** to install multiple packages and run libraries together. One more advantage of using **p_load()** is that it will skip installing the packages which are already installed on that computer.
- For example, p_load('tidyverse', 'data.table', 'lubridate')






