---
title: "Ligands analysis"
author: "frontallobotomy77"
date: "12 gru 2018"
output: 
  html_document:
    fig_caption: yes
    highlight: espresso
    keep_md: yes
    number_sections: yes
    theme: spacelab
    toc: yes
    toc_float:
      collapsed: yes
---



# Summary 

# Data analysis
## Libraries used in report 
 - dplyr
 - ggplot2
 - DT
 

 

## Initialization 



# Data loading


```
##    user  system elapsed 
##   7.274   0.152   7.455
```

# Data cleansing

```r
unwanted <- c('UNK', 'UNX', 'UNL', 'DUM', 'N', 'BLOB', 'ALA', 'ARG', 'ASN', 'ASP', 'CYS', 'GLN', 'GLU', 'GLY', 'HIS', 'ILE', 'LEU', 'LYS', 'MET', 'MSE', 'PHE', 'PRO', 'SEC', 'SER', 'THR', 'TRP', 'TYR', 'VAL', 'DA', 'DG', 'DT', 'DC', 'DU', 'A', 'G', 'T', 'C', 'U', 'HOH', 'H20', 'WAT')
tryout_clean <- tryout %>% filter(!res_name %in% unwanted)  
print(paste0('tryout size: ', nrow(tryout)))
```

```
## [1] "tryout size: 50000"
```

```r
print(paste0('clean size: ', nrow(tryout_clean)))
```

```
## [1] "clean size: 49586"
```

```r
print(paste0('delta: ', nrow(tryout)-nrow(tryout_clean)))
```

```
## [1] "delta: 414"
```

# Missing data processing
ter

# Basic data set specification

# Significant classes extracting

# Correlation between variables

# Cardinality of classes

# Atoms and electrons distribution diagram

# Classes with the greatest inconsistency in selected attributes

# Value distribution chart of selected attributes

# Interactive diagram

# Regression

# Classification
