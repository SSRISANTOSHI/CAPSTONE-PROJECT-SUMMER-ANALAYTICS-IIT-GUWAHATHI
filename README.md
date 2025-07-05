# CAPSTONE-PROJECT-SUMMER-ANALAYTICS-IIT-GUWAHATHI

## Dynamic Pricing for Urban Parking Lots  
**Capstone Project – Summer Analytics 2025**  
By: S SRISANTOSHI  
Hosted by: Consulting & Analytics Club × Pathway  

---

## Overview

This project develops a real-time, intelligent **dynamic pricing system** for 14 urban parking lots. The goal is to maximize utilization and fairness using live data including:

- Occupancy
- Queue length
- Traffic congestion
- Special day/event indicators
- Vehicle type
- Nearby lot competition

We built three pricing models of increasing complexity and realism. This project combines economic reasoning, data analytics, and simulation to create an adaptive pricing engine.

---

## Tech Stack

| Tool/Library       | Purpose                           |
|--------------------|-----------------------------------|
|   Python           | Core programming language         |
|   Pandas           | Data preprocessing                |
|   NumPy            | Numerical calculations            |
|   Pathway          | Real-time stream simulation       |
|   Bokeh            | Interactive data visualization    |
|   Google Colab     | Development & execution           |
|                    |  environment                      |
|   GitHub           | Version control & documentation   |


## Project Workflow & Architecture

- Data Preprocessing

- Extracted timestamps

- Computed occupancy rate, traffic levels, and vehicle type weights

- Engineered demand score inputs

Model 1: Linear Pricing

- Price increases linearly with occupancy

- Acts as a control model for comparison

Model 2: Demand-Based Pricing

- A demand function combining multiple real-time inputs

- Normalized score used to scale price smoothly

Model 3: Competitive Pricing with Rerouting

- Identifies nearby lots using Haversine distance

- Adjusts price or suggests rerouting if better options are found nearby

Visualization

- Plots Model 1, 2, 3 prices in real time using Bokeh

- Allows visual comparison of pricing behavior

- Real-Time Simulation (Optional)

- Placeholder to stream the data via Pathway’s real-time ingestion API


## Folder Structure

.
├── dataset.csv
├── CAPSTONE.ipynb
├── README.md



