Problems & Solutions
1.Install packages.
I lack a lot of packages, according to the error, I installed the packages as follows: desc, ggplot2, sessioninfo, lobstr, emo, tibble, sloop,DBI, RSQLite, dbplyr, profvis, bench, ggbeeswarm, devtools, zealot, tidyr.
Most of these can be installed through  install.packages(""),Where "sloop" and "emo" are installed by devtools: 
devtools::install_github(" Hadley/sloop")
devtools::install_github(" Hadley/emo ")
2.Failed to compile Introduction.Rmd
  Failed to compile introduction.rmd. Join encoding= "utf-8" in the Introduction. RMD file with 224 lines.
3.Error in Rscript_render(f, render_meta, add1,add2):Failed to compile Rcpp.Rmd
Add the Rtools path to the system's environment variables.
4.The dbplyr package is required to communicate with database backends.
Open the big-picture.rmd file and change "dplyr" to "dbplyr" on line 209.
5.Error:pandoc document conversion failed with error 2.
This problem hasn't been solved yet, so I haven't built yet.
