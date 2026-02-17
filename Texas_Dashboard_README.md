# Texas School District Performance Dashboard

## Overview
An interactive Tableau dashboard analyzing performance data across 50 Texas school districts to identify how funding, poverty, and district type impact student outcomes. Built from the perspective of a Texas math teacher exploring the data behind educational disparities.

**Author:** Javier Villegas  
**Tools:** Tableau Public  
**Live Dashboard:** [View on Tableau Public] https://public.tableau.com/views/TexasSchoolDistrictPerformanceDashboard/TexasSchoolDistrictPerformanceDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Key Findings

### 1. Poverty is the Strongest Predictor of Performance
Districts with higher free/reduced lunch rates consistently score lower in math and reading proficiency. This was the clearest pattern in the entire dataset.

### 2. Suburban Districts Outperform Urban Districts by 20+ Points
Suburban districts average around 60% math proficiency while urban districts average closer to 36%. The gap is significant and consistent across all regions.

### 3. DFW Has the Widest Performance Gap in Texas
Within the DFW region alone, math proficiency ranges from 78% (Carroll ISD) to 35% (Grand Prairie ISD) — a 43-point spread that is larger than the gap between any two regions.

### 4. Spending Alone Doesn't Drive Outcomes
There is a positive correlation between per-pupil spending and performance, but several districts spend above average and still underperform. How money is spent appears to matter more than how much.

### 5. Teacher Salary Correlates with Performance
Higher-paying districts tend to have better outcomes, but this likely reflects community wealth rather than salary directly causing better teaching.

## Dashboard Contents
| Chart | What It Shows |
|-------|---------------|
| **Math Proficiency by District** | Bar chart ranking all 50 districts, colored by urban vs suburban |
| **Spending vs Performance** | Scatter plot showing per-pupil spending against math proficiency |
| **Poverty vs Performance** | Scatter plot with trend line showing free/reduced lunch % vs math scores |
| **Regional Comparison** | Dot plot comparing DFW, Houston, San Antonio, Austin, and other regions |
| **Teacher Salary vs Performance** | Scatter plot exploring the salary-performance relationship |

## Data
- **Source:** Texas Education Agency (TEA) 2025 district-level data
- **Size:** 50 districts, 13 variables
- **File:** `Texas_School_District_Data.csv`

## How to Use
1. Visit the live dashboard link above
2. Click on any district in the bar chart to filter all other charts to that district
3. Hover over data points to see district details
4. Use the region and district type filters to compare subgroups
