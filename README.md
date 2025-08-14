# Demographic Data Analysis

## Overview
An analysis of adult census-style demographic data to understand distributions and group-level trends across education, work hours, income brackets, and geography.

## Dataset
# - **Location**: data/demographic_data.csv (e.g., adult census format)
# - **Sensitive attributes**: handled carefully with aggregated reporting

## Implementation
# 1. Load and clean categorical fields; standardize string categories and handle missing values.
# 2. Derive features such as is_advanced_education, long_hours, and income brackets.
# 3. Groupby aggregations (means, medians, proportions) across relevant categories.
# 4. Visualizations: bar charts for category proportions, box plots for hours by education, and geographic summaries if available.
# 5. Export summary tables to eports/tables/ and figures to eports/figures/.

## Tech Stack
# Python, Pandas, NumPy, Matplotlib, Seaborn

## Results
# - Clear comparisons across education levels and work hour distributions.
# - Proportion of high-income by country or education shown with confidence intervals where applicable.

## How to Run
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
   python src/analyze.py

## Project Structure
# - data/demographic_data.csv
# - src/analyze.py
# - reports/figures/
# - reports/tables/
# - requirements.txt
# - README.md

## Reproducibility
# - Python 3.9+ recommended
# - Install exact package versions via equirements.txt
# - Set a global random seed where applicable for deterministic splits

## Future Improvements
# - Add interactive dashboards (Streamlit) for filtering and drill-down.
# - Integrate geospatial visualizations if country/egion is present.
# - Bundle common transforms as reusable functions.

# ---
Author: Hardik Raut • GitHub: https://github.com/hardikkkraut

