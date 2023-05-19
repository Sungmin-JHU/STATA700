# Abstract

Sungmin Park, MD(KM)
Johns Hopkins Bloomberg School of Public Health

```
Increasing access to United States the Infant Mortality Data via a User-friendly Stata Program
```
## Background
Stata is a robust statistical software package capable of conducting various types of analyses. However, it lags in terms of content dissemination over the internet compared to other programs such as R or Python. The National Bureau of Economic Research (NBER) maintains an extensive range of economic datasets that can be utilized for a multitude of economic analyses. Nevertheless, some Stata users may encounter difficulties when trying to access NBER datasets due to format incompatibilities. Thus, we have developed a Stata program as an initial proof of concept that can readily access economic data from NBER for the period 1983-2013. This data could then be linked with other datasets to further extend the research possibilities.

## Methods
Using Jupyter software, we created a book to demonstrate 1) How to openly publish while using Stata and 2) How our Stata program works to import mortality data from NBER. The code for our Stata program, called "nberlbid" is provided in the last chapter of this book.

## Results
The program will import the infant mortality data from the NBER for any specified range between the years of 1983 and 2013. For instance, the user may enter 2003 and 2013 and the program will import mortality data from each of the years between 2003 and 2013. Then, the program will construct a line graph to show the trends in mortality over the user-specified time frame.

![Figure output](Graph.jpg)

## Conclusions
We hope that this project will encourage Stata and its users to promote open science, where code and new programs are shared on platforms such as Github. Additionally, we hope that the "nberlbid" program will serve as a preliminary example of how flexible Stata programs can increase access to publicly available data, such as NBER and NHANES.