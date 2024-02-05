# Transportacion-FinalProject-IronHack

# Project objective
**Contex:** 
This project delves into a dataset from the Intermodal Office of the Integrated Transportation Alternative (In Spanish, Oficina de Intermodal de la Alternativa de Transporte Integrado or ATI), focusing on the Urban Train of Puerto Rico spanning the years 2010 to 2021. The primary objective is to assess the fluctuations or patterns of passenger movement—both entries and exits at various stations—to ascertain whether there has been a substantial impact on public transportation, specifically trains, over the specified time frame. The ultimate aim is to gauge the impact, or lack thereof, on public transportation, particularly the train system. By dissecting the data, we aspire to unravel nuanced insights into the trends shaping the Urban Train's journey and its broader implications for the state of public transportation in Puerto Rico.

**Origin of the dataset:**
The following has been written in both Spanish and English:

1)- Fuente: Oficina de Intermodal de la Alternativa de Transporte Integrado (ATI)
    Indicadores de frecuencia mensual que presentan el número de pasajeros entrando (entradas o "entries") y el número de pasajeros saliendo (salidas o "exits") para cada una de las estaciones del Tren Urbano.

2)- Source: Intermodal Office of the Integrated Transportation Alternative (ATI)
    Monthly frequency indicators that present the number of passengers entering (entries) and the number of passengers leaving (exits) for each of the Urban Train stations.

 
# Methods
1. Data Preprocessing:
    - Handling Missing Data
    - Data Cleaning
    - Handling Categorical Data
    - Data Transformation
    - Outlier Detection
    - Removing Duplicates
    - Encoding Date and Time
    - Handling Time Series Data
2. Data Processing:
    - Data Validation
    - Data mining
    - Data Filtering
    - Hypothesis Testing
    - Forecasting
    - Data Visualization
 
# Technologies 
  - Python 3.9.18 
  - Jupyter Notebook 6.4.12
  - Tableau 2023.3

  - Python libraries:
    1. import pandas as pd
    2. import os
    3. import matplotlib.pyplot as plt
    4. import seaborn as sns
    5. import numpy as np
    6. import chardet
    7. from scipy import stats
    8. from statsmodels.graphics.tsaplots import plot_acf
    9. from statsmodels.tsa.seasonal import STL
    10. from matplotlib.ticker import ScalarFormatter
    11. from statsmodels.tsa.seasonal import seasonal_decompose
    12. from statsmodels.tsa.api import STLForecast
    13. from statsmodels.tsa.arima.model import ARIMA


# Project Description



# Insights
  - Dataset inconsistency.
  - Difficulties with adressing the code for the Forecasting.
  - Analysis Results:
     1.Test results indicated differences between the variations.
     2.Upon visual inspection, no noticeable difference was observed.

# Conclusion
  To optimize the user experience, it is recommended to leverage the insights gained from the A/B test results. Given the slightly higher completion rate in the 'Test' variation, a detailed analysis of the design elements contributing to this improvement is crucial. Exploring the reasons behind the increased average time spent in the 'Test' variation can uncover a greater engagement and potential usability enhancements. Addressing NaN error rates is essential, to confirm the absence of critical issues or, conversely, understand why errors may not have been recorded. Additionally, a thorough evaluation of the cost-effectiveness of the redesign is necessary, considering the observed completion rate increase did not meet the 5% threshold. Tailoring marketing strategies based on the significant difference in average age between variations can enhance communication effectiveness. Continuous monitoring, iterative improvements, user segmentation, and a long-term impact assessment will collectively contribute to a comprehensive and effective strategy for sustained success.

# References
  data-bootcamp-v4. (2023). Lessons - 5_6_eda_inf_stats_tableau project. GitHub Repository. https://github.com/data-bootcamp-v4/lessons/tree/main/5_6_eda_inf_stats_tableau/project/files_for_project









# References:
Autoridad de Transporte Integrado. (2021, March 17).Número de Pasajeros del Tren Urbano (Patrocinio).Indicadores.PR.https://indicadores.pr/dataset/numero-de-pasajeros-del-tren-urbano
