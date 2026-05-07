# Coral Bleaching Analysis

### Overview
This project analyses global coral bleaching patterns using integrated survey and environmental data from BCO‑DMO, with the aim of predicting coral bleaching severity and identifying its key environmental drivers. The analysis combines descriptive regional assessment with statistical and machine‑learning models to capture both spatial variation and complex, non‑linear bleaching dynamics.

Coral reef bleaching is increasing in frequency, severity, and geographic extent due to climate change, posing a major threat to marine ecosystems worldwide. Given the ecological, economic, and cultural importance of coral reefs, improving the ability to predict bleaching risk is critical. By linking global observational data with environmental variables, this project seeks to better understand when and where bleaching is most severe, and which conditions are most strongly associated with elevated risk.

### Research Question
How effectively can environmental data predict regional variation in coral bleaching severity, and which factors are most influential?

### Data
Source: https://www.bco-dmo.org/dataset/773466  

A local copy of the dataset is included in the `/data` folder for reproducibility.

The dataset contains:
- Coral bleaching observations (percentage bleaching)
- Thermal stress metrics (e.g. SST, SSTA, DHW)
- Geographic variables (latitude, longitude)
- Environmental variables (e.g. depth, windspeed, exposure)

## Key Findings
- Bleaching is spatially uneven, with clear regional differences suggesting that local environmental conditions and ecosystem resilience strongly influence outcomes.
- Thermal stress is the dominant driver: Degree Heating Weeks (DHW) shows the strongest association with bleaching, and more frequent heat stress events lead to greater severity.
- Non‑linear models substantially outperform linear regression. OLS explains a modest proportion of variation (~12%), while tree‑based models (Random Forest and XGBoost) capture a much larger share of the signal, indicating important non‑linear relationships and interactions between environmental drivers.
- Extreme bleaching events remain difficult to predict, suggesting the influence of local or unmeasured factors and highlighting uncertainty around rare, high‑impact events.

## Presentation

A full project presentation detailing the methodology, results, and recommendations is available here:

[View presentation (PDF)](presentation/coral_bleaching_analysis.pdf)
