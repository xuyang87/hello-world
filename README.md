# set repos, for R version 3.6.0, Bioconductor version 3.9
local({
  r <- getOption("repos")
  r["CRAN"] <- "https://cran.rstudio.com/"
  r["BioCsoft"] <- "https://bioconductor.org/packages/3.9/bioc"
  r["BioCann"] <- "https://bioconductor.org/packages/3.9/data/annotation"
  r["BioCexp"] <- "https://bioconductor.org/packages/3.9/data/experiment"
  options(repos = r)
})
