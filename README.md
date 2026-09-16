# Air Quality Program Evaluation

This repository contains a program evaluation exercise using a synthetic panel dataset of city-level PM2.5 pollution in India from 1990–2005. The project simulates staggered adoption of a hypothetical environmental regulation, the Preventing Pollution for a Healthy Atmosphere (PPHA), and demonstrates empirical methods commonly used in applied microeconomics and policy evaluation. The code is provided for demonstration purposes; the underlying dataset is omitted.

## Research Question

What is the effect of PPHA adoption on air pollution levels, and how do estimated effects vary across alternative identification strategies?

## Methods

The analysis compares several increasingly rigorous approaches:

- Difference in mean outcomes
- Pre/post time-series analysis
- Two-way fixed effects difference-in-differences
- Event-study estimation
- Staggered difference-in-differences
- Distributed lag models
- Sensitivity analysis using alternative control groups

The project also discusses identification assumptions, including parallel trends, treatment-effect heterogeneity, and concerns associated with staggered treatment adoption.

## Software

- R
- tidyverse
- fixest
- knitr
- kableExtra

## Repository Structure

- code/ contains all analysis scripts
- data/ contains the synthetic dataset and documentation
- output/ contains figures and exported results

## Note

The dataset is synthetic and was created for instructional purposes. Results are illustrative and intended to demonstrate reproducible workflows and applied econometric methods rather than provide substantive policy conclusions.
