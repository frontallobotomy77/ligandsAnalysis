---
title: "Ligands analysis"
author: "frontallobotomy77"
date: "09 gru 2018"
output: 
  html_document:
    toc: true
    toc_float:
      collapsed: true
    number_sections: true
    theme: spacelab
    highlight: espresso
    df_print: paged
    keep_md: true
---



#Summary <!-- na koniec -->

#Data analysis
##Libraries used in report <!-- opis + kod załączający -->
 - dplyr
 - ggplot2
 - DT
 

 

##Initialization <!-- zapewnienie powtarzalności wykonania -->



#Data loading


```r
# Start the clock!
ptm <- proc.time()

sample <- read.table(file='data/all_summary.csv', header = TRUE, nrows = 100000, sep = ';', stringsAsFactors = FALSE, 
                     comment.char = "", strip.white = TRUE, na.strings = 'NA')

# Stop the clock
proc.time() - ptm
```

```
##    user  system elapsed 
##  112.17    4.48  157.99
```


#Data cleansing

#Missing data processing

#Basic data set specification

#Significant classes extracting

#Correlation between variables

#Cardinality of classes

#Atoms and electrons distribution diagram

#Classes with the greatest inconsistency in selected attributes

#Value distribution chart of selected attributes

#Interactive diagram

#Regression

#Classification
