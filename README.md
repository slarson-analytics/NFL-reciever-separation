# NFL Data Bowl Analysis

 **[Read the full analysis report](REPORT.md)**  
 **Code:** `analysis.Rmd`

## Overview
This project was developed for the NFL Data Bowl competition and analyzes player tracking data to evaluate receiver separation and its relationship to completion probability. The goal was to move beyond traditional separation metrics and isolate receiver skill during the catch window.

## Data
- NFL player tracking data
- Play-by-play and route-level information
- Supplementary processed datasets used for modeling and visualization

## Methods
- Computed pre-throw and post-throw separation metrics
- Developed In-Air Separation Gain (IASG) to capture late-window receiver movement
- Linked separation metrics to completion probability
- Analyzed differences across route types and player roles
- Created visualizations to communicate spatial and probabilistic patterns

## Key Findings
- Late-window separation provides stronger insight into receiver skill than pre-throw separation
- Certain routes consistently allow receivers to gain separation after the ball is thrown
- IASG adds context beyond traditional separation statistics used in evaluation

## Files
- `analysis.Rmd` – Full analysis and methodology
- `report.html` – Rendered report with visualizations

## Tools Used
- R (tidyverse, ggplot2)
- Statistical modeling
- Data visualization
