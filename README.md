# CodeAlpha_Unemployment_Analysis

**CodeAlpha Data Science Internship – Task 2: Unemployment Analysis with Python**

Analysis of monthly unemployment in Indian states (May 2019 – Jun 2020), with a focus on the impact of Covid-19.

## What is inside
| File | Purpose |
|---|---|
| `Unemployment_Analysis.ipynb` | Full analysis: cleaning, EDA, visualisation, Covid impact, insights |
| `data/Unemployment_in_India.csv` | Dataset |
| `images/` | Charts exported from the notebook |
| `requirements.txt` | Python dependencies |

## Approach
1. **Cleaning:** removed 28 empty rows, stripped whitespace in column names and values, parsed dates, renamed columns.
2. **Feature engineering:** derived labour force and number of unemployed so the national rate is **labour-force weighted** (more reliable than a simple average of states).
3. **Analysis:** national trend, Covid phases (pre / transition / lockdown / recovery), rural vs urban, state-level impact, heatmap, pre-Covid patterns, correlations.

## Key findings
- Pre-Covid national rate ≈ **7.6%** (weighted); peaked at **24.2% in April 2020** (3.2x); fell to **11.0% in June 2020**.
- Employment in matched region-areas fell ~**31%** from Feb to Apr 2020; labour participation dropped from ~43.7% to ~35.1%.
- **Urban** areas were hit harder than rural (≈25–26% vs ≈23% in Apr–May 2020).
- Largest jumps: **Puducherry, Jharkhand, Tamil Nadu, Bihar**. Structurally high even before Covid: **Tripura, Haryana, Himachal Pradesh**.
- Seasonality cannot be established with only 14 months of data.


