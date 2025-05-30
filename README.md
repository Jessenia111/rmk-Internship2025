# RMK Internship 2025 - Rita Bus Simulation

## Problem
Rita takes bus number 8 every weekday from Zoo to Toompark and must be at her meeting by 09:05.  
She walks 5 minutes to the bus stop and 4 minutes from the destination stop to her office.  
The goal is to calculate the **probability of her being late** depending on when she leaves home.

## Assumptions
- Bus departs every 10 minutes
- Trip duration is exactly 13 minutes (confirmed by real timetable)
- No randomness in bus schedule or walking speed

## What This Notebook Does
- Simulates 1000 trips for each departure time (08:00–08:50)
- Calculates how often Rita would be late
- Plots a graph: departure time vs. probability of being late

## How to Run
- Open `rita_simulation.ipynb` in Jupyter
- Run all cells
- See the resulting graph at the bottom

## Result
The graph shows a sharp transition: leaving home after ~08:34 leads to 100% chance of being late.
