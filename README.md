# STAT 184: Reproducible Analysis with Quarto

A reproducible data analysis report built with Quarto covering post-pandemic airport 
traffic recovery, Monte Carlo integration, and GenAI prompting strategies.

## About This Project

This repo contains the work from HW 4.3 for STAT 184 at Penn State. The report demonstrates 
reproducible data analysis using Quarto and R across three sections: an analysis of 
passenger traffic recovery at six major international airports from 2020–2024, a Monte 
Carlo numerical integration of the Weibull probability density function, and a 
comparison of plan-based vs. generic GenAI prompting to produce data visualizations. 

## Data Sources

- **Airport passenger traffic**: Scraped from Wikipedia's 
  [List of busiest airports by passenger traffic](https://en.wikipedia.org/wiki/List_of_busiest_airports_by_passenger_traffic) 
  using the `rvest` package in R
- **Calcium dataset**: `calcium.csv` — a longitudinal study tracking ulnar calcium 
  levels in 31 women (15 control, 16 diet/exercise treatment) across four time points

## Current Plan

### Repository
- Development work is done on branches and merged into `main` using pull requests
- Tasks are tracked using GitHub Issues
- Each commit has a clear message describing the purpose of the change

### Practicing Data Analysis
- Scrape and wrangle airport passenger data from Wikipedia for 2020–2024
- Simulate Monte Carlo integration of the Weibull PDF at n = 10, 100, 1000, and 10,000
- Prompt a GenAI tool using both a detailed plan and a generic prompt, then compare 
  the outputs

## Repository Organization 
- HW4_3.qmd          # Quarto source file — run this to reproduce all results
- HW4_3.pdf          # Rendered PDF output
- calcium.csv        # Dataset for the GenAI prompting section
- README.md          # This file

## Contact Information
**Robert Dang**  
STAT 184, Penn State University, rkd5479@psu.edu
