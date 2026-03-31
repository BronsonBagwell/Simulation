# Monte Carlo Simulation
Pricing and inventory optimization for a TV sales promotion using Monte Carlo simulation.

## Overview
This project uses Monte Carlo simulation to determine the optimal inventory level for a 7-day TV sales promotion. By modeling variable demand and accounting for buy/sellback pricing, the simulation identifies the order quantity that maximizes expected profit.

## Dataset
- **Scenario:** 7-day promotional sale with uncertain daily demand
- **Parameters:** Purchase cost, selling price, sellback price for unsold inventory
- **Inventory levels tested:** 5 to 50 TVs

## Methods
- Monte Carlo simulation with 500 iterations per inventory level
- Random demand generation based on specified distribution
- Profit calculation accounting for sales revenue and sellback losses
- Expected profit comparison across inventory levels (5–50 units)

## Key Findings
- Expected profit varied significantly with order quantity, demonstrating the cost of over- and under-ordering
- The simulation identified a clear optimal inventory range that balanced stockout risk against excess inventory costs
- Results showed diminishing marginal returns beyond the optimal order quantity

## Tools & Libraries
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white)
![tidyverse](https://img.shields.io/badge/tidyverse-1A162D?style=flat-square&logo=r&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/Simulation.git`
2. Open the HTML file in a browser, or run the R Markdown file in RStudio
3. Required packages: `tidyverse`
