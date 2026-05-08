# IPL Data Analysis Pipeline

## Overview
This project builds an end-to-end data analysis pipeline on IPL datasets using Pandas.

Pipeline:
Ingest → Clean → Transform → Analyze → Visualize → Export

## Dataset
- deliveries.csv → ball-by-ball data  
- matches.csv → match-level data  

## Steps

### 1. Data Ingestion
- Loaded datasets using Pandas

### 2. Data Cleaning
- Handled missing values  
- Validated match IDs  
- Fixed data types  

### 3. Data Transformation
- Created new features  
- Merged datasets into a single DataFrame  

### 4. Analysis
Performed multiple analyses including:
- Runs per match & team  
- Top batters & bowlers  
- Strike rate & economy  
- Powerplay & death overs  
- Venue, city, and season trends  

### 5. Visualization
- Used Seaborn & Matplotlib  
- Created plots for all major insights  

### 6. Export
- Saved outputs as CSV files  
- Generated Excel summary  
