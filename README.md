Getting Started
================

> Prepare for the course by installing and configuring several necessary tools and setting yourself up with `GitHub`. Just follow the steps below, and you'll be ready to go on day 1.

## 1. Install R
`R` is a workhorse of modern data analysis. It is freely available from the [CRAN website](https://mirrors.nics.utk.edu/cran/). You can find further instructions on installation there.


## 2. Install RStudio IDE
RStudio IDE (integrative development environment) is a front-end interface. RStudio Desktop is free. [Download and install](https://www.rstudio.com/products/rstudio/download/). *Note that you must install `R` before installing RStudio.


## 3. Install core R packages
The R community is constantly evolving with the creation of user-written packages (similar to how 'apps' add functionality to your phone). To install a package, simply open RStudio and use the `install.packages` function to download and unpack the relevant libraries. 

Open a new session of RStudio, and install the core packages that we will rely on in this course. Install them all at once by entering and executing the code chunk below (either in the console or in a script file). Note that the download and installation will take several minutes to complete.

``` r
# Install core packages
  install.packages(c(
    'tidyverse',
    'rmarkdown',
    'tinytex',
    'knitr',
    'patchwork',
    'scales'
  ))

# Install tinytex  
  library(rmarkdown)
  tinytex::install_tinytex()
```

Pay attention to notices and prompts that appear in the R console as you complete this task.


## 4. Create a GitHub account
`GitHub` is a cloud-based `Git` repository for code sharing and collaboration in the world of data analytics, programming, and software development. I host the course and course materials through GitHub, and you will need an account to access all of our course materials. Create your free account at <https://github.com/>. Note that you are not required to use your full (or even true) name for your account, though I encourage you to at least use your first name and last name initial (e.g., 'Austin H'). Either way, I need to be able to link the account to you. So email me if you go with something more anonymous ('rainbow kitten surprise').


## 5. Configure Git
Link RStudio to your GitHub account. This allows you to use GitHub almost like a `Dropbox` designed specifically for data analytic projects. Installing and configuring `Git` can be a bit of a challenge. Your feelings about the challenge might serve as a useful gauge for how much you'll enjoy the other coding and programming challenges we'll encounter throughout the semester. I suggest you follow [Prof. Lendway's video tutorial](https://www.youtube.com/watch?v=QLFc9gw_Hfs) and [accompanying installation guide](https://github.com/llendway/github_for_collaboration/blob/master/github_for_collaboration.md).

*Want an early extra credit point for the term??* Complete these install and config steps, and then fork the [week 1 repository](https://github.com/sis750/01-monty-hall) to your own account. I'll see the fork and dish out the extra credit accordingly.
