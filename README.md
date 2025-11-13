# The Impact of Renewable Energy on Total Factor Productivity (TFP)

This repository contains the full work for our **Data Analysis 4 term project**, completed by  
**Aria Mousavi and Shirin Dehghannezad**.  
The project examines whether increasing the share of renewable energy in total energy consumption
affects **Total Factor Productivity (TFP)** across countries.

---

## 📄 Project Description
We conduct an econometric analysis using panel data from 2000–2020 to study the relationship
between renewable energy adoption and productivity.  
Our methods include:

- Fixed Effects (FE) panel regression  
- First Differences (FD) model  
- Event study with staggered renewable-energy policy adoption  
- Multiple robustness checks across income groups, interaction models, and pre/post event windows  

All the results, figures, and methodological details are available in the **final report**.

---

## 📁 Repository Structure
- Code/               # Jupyter notebooks and scripts used for the analysis
- Data/               # Raw and processed datasets
- Final-report/       # Final PDF report and supporting documents
- README.md           # Project overview (this file)


---

## Data Sources
We use openly available macroeconomic datasets from:

- **Our World in Data** (TFP, renewable share, GDP per capita)  
- **World Bank** (oil price, trade openness, energy intensity, FDI, inflation)

---

## Research Question
Does increasing the share of renewable energy in total energy consumption  
**improve or reduce Total Factor Productivity** across countries?

This question matters for understanding whether the green transition generates  
productivity gains or short-term efficiency losses.

---

## Main Findings (Short Summary)
- Higher renewable energy share is **negatively associated with TFP**.
- The negative effect is **stronger in high-income countries**.
- Event study results show **no immediate TFP gains after policy adoption**.
- Results remain consistent across all robustness checks.

Full details are in the PDF report inside the `Final-report/` folder.

---

## Tools and Methods
- Python (pandas, statsmodels, plotly, matplotlib)
- Econometric panel models (FE, FD)
- Event-study design
- Data cleaning, interpolation, winsorization
- Visualization and mapping

---

## Authors
**Aria Mousavi**  
**Shirin Dehghannezad**  
(Data Analysis 4 — CEU)
