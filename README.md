# Connecticut Traffic Flow Analysis with Markov Chains

This project applies Markov chains and steady-state analysis to Connecticut traffic flow data. The goal is to identify routes where cars are most likely to be in the long run and to estimate likely destinations after several transitions from a given starting location.

This project was completed by Kyle Levesque, Eashan Hatti, and Wyatt Lake for a linear algebra course at Yale University.

## Overview

Using Connecticut traffic flow data, this project constructs a transition matrix where each state represents a road location or node. Transition probabilities are based on observed average daily traffic flow between locations. The project then explains and applies Markov chain methods to analyze long-run traffic behavior and short-run route outcomes.

## Methods

- Markov chains
- Transition matrices
- Steady-state vectors
- Eigenvectors and eigenvalues
- Traffic flow aggregation
- Geographic visualization in R

## Main Findings

The steady-state analysis identifies the road locations most likely to be occupied in the long run. A separate path analysis shows the possible destinations after three transitions from a selected starting node, including the probability of reaching a dead end.

## Files

- `traffic_markov_chain_report.pdf`: Final written report
- `traffic_markov_chain_analysis.Rmd`: R Markdown source file
- `data/ct_traffic_data_2023.csv`: Traffic flow dataset used in the analysis
- `figures/`: Maps generated from the analysis

## Data Source

The road and traffic data were collected from CTDOT Open Data.
