# Summary

This repository is used for analyzing a subset of design alterations suggested in an expert review. See the corresponding paper, *Mindful Moves: Extraneous Cognitive Load Reduction and Learning Facilitation in Board Game Design*, and its related product for further detail.

## Project Organization
The organization of the project is as follows:


```
├── README.md                                                  <- The top-level README for this project
├── data                                                       <- The main folder for data
|   ├── cleaned data                                           <- Folder containing cleaned csv files for each task
|   └── raw data                                               <- Folder containing raw data 
|        ├── experimental data                                 <- Folder containing a csv file and compressed zip per participant with data from Pavlovia
|        |   └── PARTICIPANT_board_game_yyyy-mm-dd.csv         <- File in csv format containing data on a single participant 
|        |       [...]                                         <- ... continued
|        └── survey data                                       <- Folder containing survey data 
|            ├── dataset.csv                                   <- File in csv format containing survey data
|            ├── labels.csv                                    <- File in csv format to translate analysis labels into meaningful levels
|            └── variables.csv                                 <- File in csv format which lists the phrases used in the questionnaire
├── out                                                        <- Folder containing plots and outputs from the analysis
|   ├── RT_density.png                                         <- Density plots of response times
|   ├── model_summaries.txt                                    <- File in txt format containing summaries for all models
|   └── residuals.png                                          <- Residual plots
|   └── violin_plot.png                                        <- Violin plots 
└── src                                                        <- The main folder for scripts
|   ├── Data cleaning.Rmd                                      <- R Markdown for cleaning and restructuring the raw data in preparation for modelling
|   ├── Modeling.Rmd                                           <- R Markdown for modelling and statistical analysis
|   └── Summarizing stats.Rmd                                  <- R Markdown for summarizing statistics
└── Board Game Expert Reviews.pdf                              <- File in pdf format containing the associated report on design recommendations

```

## Reproducibility
You can run and reproduce the results by cloning the GitHub repository and running the Modelling.Rmd script in R.
