data import
================

``` r
library (tidyverse)
```

    ## -- Attaching packages ---------- tidyverse 1.3.0 --

    ## v ggplot2 3.3.2     v purrr   0.3.4
    ## v tibble  3.0.3     v dplyr   1.0.2
    ## v tidyr   1.1.2     v stringr 1.4.0
    ## v readr   1.3.1     v forcats 0.5.0

    ## -- Conflicts ------------- tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

## read in data

Read in the litters data set

\`\`\` { r}

litters\_df = read\_csv(“./data/FAS\_litters.csv”) litters\_df =
janitor::clean\_names(litters\_df)
