# if (!requireNamespace("renv", quietly = TRUE)) {
#   install.packages("renv")
# }

source("renv/activate.R")


# Install pak from CRAN
renv::install("pak")

# Set renv to use pak for package installation
options(renv.config.pak.enabled = TRUE)

# VSCode packages
pak::pkg_install(c("jsonlite", "rlang", "languageserver"))

# Environment vars
pak::pkg_install(c("dotenv"))

# Targets packages
pak::pkg_install(c("targets", "dplyr", "tarchetypes", "cpp11"))

# targets::use_targets()

# Testing layer
pak::pkg_install("checkmate")

renv::snapshot()
