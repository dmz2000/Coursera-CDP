---
title       : Course Project Application
subtitle    : Visualizing mtcars Variable Relationships
author      : dmz2000
job         : Coursera Learner
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Overview of Application

The Developing Data Products course project application can be accessed at:

https://dmz2000.shinyapps.io/CDPProj/

Getting started documentation is available on the page.

The application:

1. Was developed using the Shiny library as taught in lectures
2. Aims to facilitate exploration of relationship between data variables
3. Allows application users to visualize data without requiring knowledge of R  

--- 

## The mtcars Dataset

The dataset being explored is mtcars data from the datasets library. The mtcars dataset inspects fuel consumption (in miles per gallon) based on different aspects of car design features. 

Users with R can perform exploration of the data with the commands below, to get an understanding of the data structure:

```r
library(datasets); data(mtcars)
head(mtcars)
```

```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

--- 

## What the Application Does

Application users can select one aspect of car design from the drop down menu and see its relationship to fuel consumption, similar to the below.

For example, if selected variable from dropdown is "Horsepower":

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- 

## Like the Application?

Try it out from the link on slide 2. 

Think it's pretty cool? 

If you like what the application does, and/or the ability of my cool slides that contain embedded R codes and generated graphs. Learn more about:

- the shiny library
- the slidify library
- and other data science topics

from the Johns Hopkin University data science specialization on Coursera!


