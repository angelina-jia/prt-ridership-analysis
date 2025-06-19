# Pittsburgh Regional Transit Ridership & Timeliness Analysis

This project explores whether bus timeliness has a measurable impact on ridership for the Pittsburgh Regional Transit (PRT) system. It was created for the Pittsburgh Data Jam in Fall 2023 by Angelina Jia, Yewon Kim, Neha Dutt, and Mahitha Ramachandran.

## 📌 Research Question

**Does bus timeliness affect ridership?**  
We hypothesized that better on-time performance would correlate with higher ridership on a given bus route.

## 📊 Data

- **Source**: [Western Pennsylvania Regional Data Center](https://data.wprdc.org/)  
- **Datasets Used**:
  - Monthly On-Time Performance by Route
  - Monthly Average Ridership by Route (Weekdays only)
- Focused on **bus routes** and **weekday data for 2022**

## 🔧 Methods

- Filtered data in Excel to isolate weekday/monthly values
- Randomly selected two sets of 5 bus routes
- Conducted simple linear regression in Excel
- Scatter plots and regressions (originally generated in R; not included here)

## 🔍 Key Findings

- Initial analysis showed a **negative relationship** between timeliness and ridership, contrary to our hypothesis
- Further inspection revealed this was largely influenced by **high-volume routes** (61C and 71C)
- Once those were removed, correlation weakened significantly
- Suggested an alternate hypothesis: **high ridership might cause lower timeliness** (e.g., more boarding time)

## ⚠️ Limitations

- Small sample of routes analyzed
- Cannot establish causation from correlation
- No multivariate controls (e.g., weather, time of day, special events)

## 📁 Files

- `PRT_Ridership_Analysis.xlsx`: Cleaned data and regression output
- `PRT_Ridership_Project.pdf`: Project poster with visualizations and summary

## 🧠 Next Steps

- Rebuild the analysis in R or Python for reproducibility
- Run multivariate regression to control for other factors
- Expand to full dataset beyond sampled routes
