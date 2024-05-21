# targets-project-template

This is a template repo for getting a targets project started with as much reproducibility in place as possible.

## TLDR

A reproducible pipeline template that can be cloned and set you up into an analytical workflow within minutes.

## What's set up for you

1. The project comes with the following packages in place

- {renv} for dependency management
- {pak} for package loading
- {targets} which manages to the project structure
- {dotenv} which is used to set up environment variables for the project
- {checkmate} for writing concise testing checks to your functions

2. Alongside the packages that are shipped as part of the project directory; you will have some files to assist with environment and project management. This workspace setting have been set up for `RStudio` users as well as `VSCode`({jsonlite}, {rlang}) for other IDEs your millage may vary.

- `.Rprofile` file which is used by renv to activate the project at the start of the project. Configuration for R environment
- `.env` file which is used b renv to store your environment examples. and example file is included.
- `.gitignore` set up your ignore patterns for the project.
- `renv.lock` snapshot of the renv environment
- `_targets.R` targets pipeline configuration
- 

## What's in it for you?

- Saves you hours of setting up your project workspace.
- If you are not familiar with some of these packages like `renv` your can be sure that they will run out the box
- You will be building a reproducible pipeline that other will be able to understand and contribute to.

## Project structure
