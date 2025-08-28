# NBA Performance Analytics

## Unraveling Basketball Greatness: Analyzing Scoring Dynamics and Player Performance Through the Decades

### Project Overview
This comprehensive econometric analysis examines how NBA scoring patterns have evolved from 1950 to 2017, focusing on the interplay between player efficiency, positional roles, and broader league-level trends.

### Key Features
- **Panel Data Analysis**: Utilizes unbalanced panel data spanning 67 years of NBA history
- **Fixed Effects Regression**: Controls for individual player heterogeneity
- **Player Efficiency Rating (PER)**: Analyzes correlation with scoring outputs
- **Historical Context**: Incorporates major rule changes and their impact on scoring

### Methodology
- **Data Source**: Basketball Reference (1950-2017)
- **Statistical Approach**: Fixed effects regression with robust standard errors
- **Key Variables**: Points per game, PER, position dummies, minutes played
- **Sample Size**: Comprehensive dataset covering all NBA players

### Key Findings
1. **Efficiency Matters**: Higher PER consistently correlates with greater scoring outputs
2. **Positional Evolution**: Small forwards show evolving offensive responsibilities
3. **Historical Trends**: Dramatic scoring increases reflect league's shift toward offense-friendly environments
4. **Rule Impact**: Three-point line introduction and hand-check rule changes significantly affected scoring patterns

### Historical Context Analyzed
- **1979**: Introduction of the three-point line
- **1994-1997**: Shortened three-point line period
- **2004-2005**: Hand-check rule changes

### Files
- `MRN_731_SUB.rmarkdown`: Source R Markdown file with complete analysis
- `MRN_731_SUB.html`: Rendered HTML report with visualizations

### Technical Details
- **Course**: Economics 731 - Econometric Methods and Applications
- **Professor**: Venoo Kakar
- **Institution**: San Francisco State University
- **Date**: December 2024

### Usage
```r
# Required packages
library(readxl)
library(kableExtra)
library(tidyr)
library(dplyr)
library(ggplot2)

# Load and run the analysis
rmarkdown::render("MRN_731_SUB.rmarkdown")
```

### Insights for Stakeholders
- **Coaches**: Understanding positional scoring evolution for strategic planning
- **Analysts**: Data-driven insights into player efficiency and performance
- **Decision-makers**: Historical context for rule changes and their impacts

This analysis provides a nuanced understanding of NBA scoring dynamics, combining rigorous econometric methods with practical insights for basketball professionals.