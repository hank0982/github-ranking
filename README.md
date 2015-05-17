# github-ranking

Initially, paper for Flossmetrics on the use and impact of GitHub rankings. Eventually, paper for a journal on an Open Science basis. You want to collaborate, fork & pull request 

## Paper howto

This is a "executable" paper. It includes data and script used to generate graphs via the [`knitr`](https://github.com/yihui/knitr#readme) literate programming package for R. 

You'll have to install several R packages:

	install.packages(c("knitr","ggplot2", "ineq"), dependencies = TRUE)

Then use RStudio or your favorite environment (like emacs) to generate the tex file from `.Rnw` and compile it. 
