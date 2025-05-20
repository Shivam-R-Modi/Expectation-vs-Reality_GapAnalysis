# Hotel Guest Experience Analysis Dashboard

## Project Overview
This repository contains a data analytics project that examines the gap between guest expectations and experiences at a scenic destination hotel. By analyzing paired check-in and check-out survey responses from the same guests, this project reveals critical insights about the hotel's marketing-operations alignment.

## Business Problem
Hotels often struggle with a disconnect between what attracts guests and what ultimately impresses them. This disconnect can lead to:
    1. Disappointed guests
    2. Negative reviews
    3. Lower rebooking rates
    4. Inefficient resource allocation

This project tackles this challenge through a data-driven approach that directly compares what persuaded guests to choose the hotel versus what impressed them during their stay.

## Dataset
The analysis uses survey data from 47 unique hotel guests who answered two key questions:
    i)  Check-in survey: "What persuaded you to choose our hotel for your stay?"
    ii) Check-out survey: "What impressed you the most during your stay?"

Both surveys presented identical multiple-choice options covering 11 hotel features/amenities, with guests selecting all that applied.

## Methodology

### Data Preparation:
  1. Cleaned and structured raw survey responses
  2. Created consolidated comparison tables
  3. Calculated derived metrics including gap analysis and continuation rates


### Statistical Analysis:
  1. Calculated expectation-reality gaps for all features
  2. Developed continuation rate metrics to quantify how consistently features deliver
  3. Segmented customer experience patterns
  4. Created performance categories based on fulfillment rates


### Visualization Development:
  1. Designed interactive Power BI dashboard
  2. Created five interconnected visualizations
  3. Implemented cross-filtering and interactive elements

## Key Findings
The analysis revealed:
  1. 47.6% drop in feature mentions from check-in to check-out
  2. 83% of guests experienced fewer impressive features than expected
  3. All 11 hotel features showed negative expectation-reality gaps
  4. Only two features consistently delivered on their marketing promise
  5. Critical gaps in basic hotel services like room comfort and staff friendliness

## Visualizations
The repository includes:
  1. Expectation vs. Reality Bar Chart - Comparing what attracted guests vs. what impressed them
  2. Feature Fulfillment Rate Table - Showing how consistently each feature delivers on expectations
  3. Gap Analysis Chart - Visualizing the magnitude of expectation-reality gaps
  4. Customer Experience Patterns - Illustrating guest satisfaction segments
  5. Performance Quadrant Analysis - Strategic positioning of features by importance and performance

## Business Recommendations
Based on the data analysis, the project delivers actionable recommendations for:
  1. Marketing Realignment - Focusing promotional content on proven strengths
  2. Operational Improvements - Prioritizing enhancements based on data-driven insights
  3. Guest Experience Management - Implementing systems to better align expectations with reality

## Technologies Used
  1. Excel/Google Sheets for data preparation and preliminary analysis
  2. Power BI for interactive dashboard development
  3. DAX for advanced calculations and metrics
  4. Statistical Analysis techniques for identifying significant patterns

## Repository Contents
    --> /data - Raw and processed data files
    --> /analysis - Analytical scripts and intermediate outputs
    --> /visualizations - Dashboard files and exported images
    --> /presentation - Executive summary slides
    --> /documentation - Detailed methodology and findings

## How to Use
Clone this repository
Open the Power BI file in the /visualizations directory
Explore the interactive dashboard
Review the analytical methodology in the documentation

## Future Work
Potential extensions of this project include:
    * Time-series analysis as more data becomes available
    * Segmentation by guest demographics or visit purpose
    * Competitor benchmarking
    * Predictive modeling for guest satisfaction
