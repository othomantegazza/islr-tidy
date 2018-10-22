# The exercises in ISLR solved and demostrated with tidyverse packages

## Material

The reference book by **Introduction to Statistical Learning with Applications in R** by *Gareth James*, *Daniela Witten*, *Trevor Hastie* and *Robert Tibshirani* is available [here](https://www-bcf.usc.edu/~gareth/ISL/)

The tidyverse packages are shown in [R for Data Science](http://r4ds.had.co.nz/) by *Garrett Grolemund* and *Hadley Wickham*, and in their [reference websites](https://www.tidyverse.org/).

## Compile the Booklet

To compile the booklet you can use [Bookdown](https://bookdown.org/yihui/bookdown/), soon a draft of this booklet will be avilable on [the bookdown website](https://bookdown.org/).

To compile the book you can use:

```{r}
library(bookdown)

render_book("index.Rmd",
            output_format = gitbook())
```

## Work in progress

Work in progress, if you have pull requests or comments, do not esitate.