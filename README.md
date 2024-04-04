# Summary

This repository is used for analyzing a subset of design alterations suggested in an expert review. See the corresponding paper, *Mindful Moves: Extraneous Cognitive Load Reduction and Learning Facilitation in Board Game Design*, and its related product for further detail.

## Project Organization
The organization of the project is as follows:


```
├── README.md                      <- The top-level README for this project
├── data                           <- The main folder for data
|   ├── cleaned data               <- Folder containing cleaned csv files for each task
|   └── raw data                   <- Folder containing raw data 
|        ├── experimental data     <- Folder containing a csv file and compressed zip per participant with data from Pavlovia 
|        └── survey data           <- Folder containing survey data 
|            ├── dataset.csv       <- File in csv format containing survey data
|            ├── labels.csv        <- File in csv format to translate analysis labels into meaningful levels
|            └── variables.csv     <- File in csv format which lists the phrases used in the questionnaire
└── src                            <- The main folder for scripts
    ├── Data cleaning.Rmd          <- R Markdown for cleaning and restructuring the raw data in preparation for modelling
    └── Modelling.Rmd              <- R Markdown for modelling and statistical analysis

```

## Reproducibility
You can run and reproduce the results by cloning the GitHub repository and running the Modelling.Rmd script in R.
