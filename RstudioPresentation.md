RstudioPresentation
========================================================
author: Luis Botero
date:   2/28/2016
Final project of the Developing Data Products course

========================================================

# Objective

This App shows different cluster configurations from the 
mtcars dataset, allows the user to select a variable and
cluster size and plots that variable vs mpg using the 
kmeans algorithm

__The mtcars Dataset__

The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973--74 models).

_Documentation reproduced from R 3.0.2. License: GPL-2._

========================================================

# Variables

Clusters sample using Shiny Apps and the mtcars dataset



The App allows the user to select one of the mtcars variables

```
   Variable          Description
1      cyl  Cylinders           
2      disp Displacement        
3      hp   Horsepower          
4      drat Drat                
5      wt   Weight              
6      qsec qsec                
7      vs   V or Straight engine
8      am   Auto/Manual         
9      gear Gears               
10     carb Carburator          
```
For the clustering sample, the variables hp and mpg will be used for simplicity sake.

Classic Clustering Sample using Kmeans
========================================================
mtcars data set hp~mpg

![plot of chunk unnamed-chunk-2](RstudioPresentation-figure/unnamed-chunk-2-1.png)

Cluster plot using PAM
========================================================

![plot of chunk unnamed-chunk-3](RstudioPresentation-figure/unnamed-chunk-3-1.png)


PAM (Partitioning Around Medoids) is a classic algorithm for k-medoids clustering, more robust in presence of outliers (1)

_http://www.rdatamining.com/docs/data-clustering-with-r_



