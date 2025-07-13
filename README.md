# Linear Regression Analysis: Factors Influencing New Business Registrations in Polish Counties

## Author
Izabela Guła  
AGH University of Science and Technology, Kraków  
Informatics and Econometrics  

## Overview
This project analyzes socio-economic factors influencing the number of new businesses registered in Polish counties (excluding cities with county rights) using linear regression. The study leverages data from the Polish Central Statistical Office (GUS) for 2022, examining variables such as unemployment, housing, urbanization, workplace accidents, divorces, and population density.

## Key Features
- **Data**: 314 observations (counties) with 7 variables, including:
  - `Unemployment rate`, `Housing units completed`, `Urbanization rate`, `Workplace accidents`, `Divorces`, `Population density`, and `New businesses` (dependent variable).
- **Methodology**:
  - **Initial Models**: Linear regression with stepwise backward elimination and Hellwig’s method for variable selection.
  - **Transformations**: Log-transformed variables to address heteroskedasticity.
  - **Final Model**: Log-linear regression with `Housing`, `Urbanization`, and `Workplace accidents` as predictors (adjusted R² = 0.64).
- **Validation**:
  - Tests for normality (Doornik-Hansen), heteroskedasticity (White’s, Breusch-Pagan), multicollinearity (VIF), and model stability (Chow, RESET).
  - Confirmed hypotheses: Housing positively impacts new businesses; Urbanization shows a negative effect.
- **Results**:
  - **Key Findings**: A 1% increase in housing units correlates with a 0.255-unit rise in new businesses (log scale). Urbanization reduces new businesses by 0.198 units per 1% increase.
  - **Limitations**: Instability in model parameters (per Chow/RESET tests) suggests potential misspecification.

---
*Note: The report is available only in Polish.*
