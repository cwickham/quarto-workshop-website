#### 1. Software

Download and install the latest versions of R, RStudio, and Quarto:

-   R 4.2.3 or above: <https://cran.r-project.org>
-   RStudio 2024.04.0 or above: <https://posit.co/download/rstudio-desktop>
-   Quarto 1.4 or above: <https://quarto.org/docs/download> 

#### 2. R Packages

Install the following packages:

```{r}
#| eval: false

pkg_list <- c("tidyverse", "gt", "ggthemes", "palmerpenguins", 
              "quarto", "usethis")

install.packages(pkg_list)
```

#### 3. Exercises

Download and open the exercises for this session. The easiest way is to run this line of R code at the console in RStudio.

```{r}
#| eval: false

usethis::use_course("https://bit.ly/cscd-exercises")
```

If that doesn't work, you can download a zip file of the exercises [here](https://github.com/cwickham/quarto-workshop-exercises), then open the directory. The qmd files can be opened in RStudio.