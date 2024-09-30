# Ranking of Best Performing Midfielders in Copa de la Liga 2024 Argentina

## Introduction
This project aims to create a ranking of the best-performing midfielders in the Copa de la Liga 2024 Argentina using R. The goal is to provide an objective analysis of players based on their on-field performance and help scouts, coaches, and analysts evaluate players effectively.

The program reads player data from a CSV file, processes and cleans the data to select the key performance metrics suitable for a defending midfielder, and then apply a scoring algorithm to each player. Each KPI has a weight assigned to it to balance the importance of each metric appropriately in the final ranking. 

## Requirements
The following R libraries are used in this project:

- **tidyverse**: For data manipulation, cleaning, and visualization.
- **fmsb**: For radar charts to visualize multiple metrics of top performers.
- **lsa**: For similarity analysis and data normalization.
- **knitr**: To create HTML reports or summaries of the rankings.

To install these libraries, run the following command in R:
```r
install.packages(c("tidyverse", "fmsb", "lsa", "knitr"))
