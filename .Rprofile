source("renv/activate.R")

build_xaringan <- function() {
  rmds <- list.files("./slides/", pattern = "*.Rmd", recursive = TRUE)
  lapply(rmds, rmarkdown::render)
}
