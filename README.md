# Required-price-spread-for-different-BESS-CAPEX-s

## Overview
This repository contains a Jupyter Notebook developed to explore the required price spread between charge and discharge for a Battery Energy Storage System (BESS) to meet specific financial return targets (IRR) under varying capital cost (Capex) assumptions. The model aims to support project developers, investors, and energy analysts in assessing the financial viability of wholesale arbitrage strategies in the NEM (National Electricity Market).

## What the Model Does
- Calculates the required $/MWh profit for discharged energy to achieve target IRRs (e.g., 12%, 15%, 18%)
- Models Capex-dependent outcomes and degradation across a 15-year project life
- Accounts for round-trip efficiency and realistic operational assumptions
- Converts required profit into charge and discharge price pairs

## Key Assumptions
- Parameter | Value
- IRR Targets | 12%, 15%, 18%
- Round Trip Efficiency (RTE) | 85%
- Annual Degradation | 3%
- Depth of Discharge (DoD) | 90%
- Cycles per Day | 1.5
- Project Duration | 15 years
- Interest Rate | 0% (self-funded)

## How to Use This Repo
1. Clone the repo
3. Open Daily spread-V2.ipynb in Jupyter or VSCode
4. Modify parameters or run as-is to replicate the base scenario
5. Explore how different assumptions impact feasibility across markets

## Articles & Context
Read the artile I wrote based on this analysis:
https://www.linkedin.com/pulse/optimising-bess-returns-key-financial-metrics-strategies-mgjtc/?trackingId=wBmZ%2FnRDGQARSKGScdmgGg%3D%3D 
