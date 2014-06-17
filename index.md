---
title       : Iris Clasification
subtitle    : Data Reproducible Assesment
author      : Leticia Rodriguez Brey
job         : Data Analyst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}

---

## Iris Classification application

This app helps you to predict the classification of an Iris specie. For the classification, the iris data set is used. You can find the data on this [link](https://archive.ics.uci.edu/ml/datasets/Iris)

The app predicts the specie from a given width and length measures of sepals and petals. Random Forest is used in order to predict the classification.



---

## Iris Data

This is a parallel plot. It helps us to identify paterns for each Iris specie and possible outliers.
![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

---

## Decision Tree and Random Forest

This is the classification table for the testing subset of the data. 

```
##                  
## testPred          Iris-setosa Iris-versicolor Iris-virginica
##   Iris-setosa              10               0              0
##   Iris-versicolor           0              12              2
##   Iris-virginica            0               0             14
```

---

## Iris classification APP

You can find and try out the application in the following [link](https://letirodribrey.shinyapps.io/Assessment/)

The application Github repository can be found on this [link](https://github.com/letirodribrey/ShinyApp)

The slidify Github repository is available in this [link](https://github.com/letirodribrey/Slidify)
