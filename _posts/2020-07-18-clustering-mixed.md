---
title: "Clustering Techniques with Mixed Type of Data"
date: 2020-07-20 09:01:00 -0600
---


K-means algorithm is not applicable to categorical data (it works with only numerical data).  The k-modes proposed by Huang (1998) is applicable to data with a mix of categorical and numerical variables. 
A number of good discussions can be found from the page at "https://datascience.stackexchange.com/questions/22/k-means-clustering-for-mixed-numeric-and-categorical-data". 

* option 2. converting categorical variables to binary variables, and then apply k-means (as if these were numeric)

* read r-bloggers.com/clustering-mixed-data-types-in-r

* read "Survey of Clustering Algorithms"

* visit https://cran.r-project.org/web/packages/clustMixType/clustMixType.pdf

* visit http://varsellcm.r-forge.r-project.org/

