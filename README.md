# Drivers-of-CO2-Reduction-Renewable-Energy-and-Government-Spending
Empirical analysis of CO₂ emissions in LMICs using panel data (2002–2022), examining the role of renewable energy and government spending through FE, IV (2SLS), and dynamic GMM models

## Overview
This project investigates the determinants of CO₂ emissions in Low- and Middle-Income Countries (LMICs), with a particular focus on the role of renewable energy consumption and government spending. Using a strongly balanced panel dataset covering 26 countries from 2002 to 2022, the study applies advanced panel econometric techniques to address endogeneity, heteroskedasticity, and serial correlation.

## Motivation
LMICs face a dual challenge of reducing carbon emissions while sustaining economic growth amid fiscal and structural constraints. This study examines whether renewable energy adoption and government consumption can jointly contribute to emission reduction in such contexts.

## Data Description
- **Countries:** 26 LMICs  
- **Time Period:** 2002–2022  
- **Observations:** 546 (strongly balanced panel)  

### Key Variables
- **Dependent Variable:** CO₂ emissions per capita  
- **Independent Variables:** Renewable energy consumption, government consumption expenditure  
- **Controls:** GDP per capita, energy use, urbanization, education  
- **Interaction Term:** Renewable energy × government spending (mean-centered)

## Methodology
- Pooled OLS, Fixed Effects, and Random Effects models  
- Hausman test to select Fixed Effects  
- Instrumental Variable (2SLS) approach using lagged renewable energy  
- Dynamic panel estimation using One-step and Two-step Difference GMM  
- Diagnostic tests for heteroskedasticity, serial correlation, and instrument validity

## Key Findings
- Government consumption has a strong and statistically significant negative effect on CO₂ emissions.
- Renewable energy reduces emissions once endogeneity is addressed through GMM.
- Energy use consistently increases emissions across specifications.
- Dynamic persistence of CO₂ emissions is significant, justifying the use of GMM estimators.
- Diagnostic tests confirm correct model specification and instrument validity.

## Tools & Skills Used
- Panel data econometrics (FE, IV, GMM)
- Stata / R (econometric estimation and diagnostics)
- Data analysis and interpretation
- Academic research writing and presentation

## Output
- Econometric regression results with diagnostics
- Final presentation and analytical interpretation
- Policy-relevant insights for climate and fiscal governance

## Authors
Bandana Mallick  
**Suchana Dey**  
Sreyashi Datta  
Shaily Barman  

## Keywords
Panel Data, CO₂ Emissions, Renewable Energy, Government Spending, GMM, Climate Economics
