# Coral Bleaching Analysis

### Overview
This project investigates global patterns in coral bleaching using environmental data from BCO-DMO, with the aim of identifying which factors are most strongly associated with bleaching severity. Particular attention is given to indicators of thermal stress, which are widely recognised as key drivers of bleaching.

Coral reef bleaching is increasing in frequency, severity, and geographic extent due to climate change, posing a major threat to marine ecosystems. Given the ecological, economic, and cultural importance of coral reefs, improving our understanding of bleaching dynamics is critical. By analysing global observational data alongside environmental variables, this project seeks to better identify the conditions under which bleaching occurs and support more effective prediction, conservation, and management strategies.

### Research Question
Which environmental factors are most strongly associated with coral bleaching severity?

### Data
Source: https://www.bco-dmo.org/dataset/773466  

A local copy of the dataset is included in the `/data` folder for reproducibility.

The dataset contains:
- Bleaching observations (%)
- Temperature metrics (SST, SSTA, DHW)
- Geographic variables (latitude, longitude)
- Environmental variables (depth, windspeed, exposure)

## Key Findings
- Bleaching frequency and severity are increasing over time, indicating escalating coral stress under climate change.
- Bleaching is spatially uneven, with clear regional differences suggesting that local environmental conditions and ecosystem resilience strongly influence outcomes.
- Thermal stress is the dominant driver: Degree Heating Weeks (DHW) shows the strongest association with bleaching, and more frequent heat stress events lead to greater severity.
- Linear models explain a modest proportion of variation (~12%), while tree-based models perform better, indicating that non-linear relationships and interactions are important in explaining bleaching dynamics.

## Presentation

A full project presentation (methodology and results) is available here:

[Download presentation](presentation/coral_bleaching_analysis.pptx)


