# Climbing Performance Analysis

Sport climbing performance analysis using R, Quarto and data visualization.

## Project description

This project explores factors associated with sport climbing performance. The analysis focuses on body measurements, climbing experience, elite climber profiles, geographical differences and gender-based differences among climbers.

The report was created in Quarto using R.

## Research questions

1. How are height and weight related to the maximum climbing grade achieved by a climber?
2. Does the anthropometric profile of elite climbers differ from lower-level climbers?
3. Which countries have the highest concentration of elite climbers relative to the number of climbers in the dataset?
4. How do physical characteristics differ between male and female professional climbers?

## Dataset

The analysis uses the `climber_df.csv` dataset.

The data comes from the 8a.nu climbing logbook dataset originally published on Kaggle by David Cohen:

https://www.kaggle.com/datasets/dcohen21/8anu-climbing-logbook

Important note: the dataset represents users of the 8a.nu platform, so the results should be interpreted as trends within this climbing community, not as conclusions about all climbers worldwide.

## Tools and technologies

- R
- Quarto
- tidyverse
- ggplot2
- plotly
- DT
- kableExtra
- patchwork

## Repository structure

```text
climbing-performance-analysis/
│
├── README.md
├── index.qmd
├── index.html
├── references.bib
├── .gitignore
│
├── data/
│   ├── climber_df.csv
│   └── README.md
│
└── assets/
    └── images/
        └── climbing-cover.jpg