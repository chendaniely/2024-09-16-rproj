---
title: "read_data"
author: "Daniel Chen"
date: "2024-09-16"
output: 
  html_document: 
    keep_md: true
---

## Load Packages


``` r
library(tidyverse)
```

<h2>Load Data</h2>
## Load Data


```
## [1] "/home/dan/Desktop/2024-09-16-rproj"
```



``` r
read_csv("data/data.csv")
```


``` r
read_csv("data/data.csv")
```

```
## Rows: 2 Columns: 2
## ── Column specification ────────────────────────────────────────────────────────
## Delimiter: ","
## chr (2): fname, lname
## 
## ℹ Use `spec()` to retrieve the full column specification for this data.
## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
```

```
## # A tibble: 2 × 2
##   fname  lname
##   <chr>  <chr>
## 1 daniel chen 
## 2 andy   tai
```
