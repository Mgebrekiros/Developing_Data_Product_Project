Developing data products_Slidify
===
author: Michale Gebrekiros
date: 8/22/2015

===
 Reproducible Pitch Presentation

I have made my  shiny app, it can be found at https://mgebrekiros.shinyapps.io/developingData_shiny.  
Here's what I tried to follow the assignment questions

### It must be done in Slidify or Rstudio Presenter
### It must be 5 pages
### must be hosted on github or Rpubs
### must contained some embedded R code that gets run when slidifying the document

===
# Motor Trend Car Road Tests
The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973–74 models).

===
# Source
Henderson and Velleman (1981), Building multiple regression models interactively. Biometrics, 37, 391–411


===


```r
library(datasets)
head(mtcars, 3)
```

```
               mpg cyl disp  hp drat    wt  qsec vs am gear carb
Mazda RX4     21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
Mazda RX4 Wag 21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
Datsun 710    22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
```


===
mtcars dataset - Format

A data frame with 32 observations on 11 variables.

Index  Field	Detail
[, 1]	mpg	Miles/(US) gallon
[, 2]	cyl	Number of cylinders
[, 3]	disp	Displacement (cu.in.)
[, 4]	hp	Gross horsepower
[, 5]	drat	Rear axle ratio
[, 6]	wt	Weight (lb/1000)
[, 7]	qsec	1/4 mile time
[, 8]	vs	V/S
[, 9]	am	Transmission (0 = automatic, 1 = manual)
[,10]	gear	Number of forward gears
[,11]	carb	Number of carburetors



===




===
