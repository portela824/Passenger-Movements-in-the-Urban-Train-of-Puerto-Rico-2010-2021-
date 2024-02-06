# Decoding Transit Trends: Analyzing Passenger Movements in the Urban Train of Puerto Rico (2010-2021)

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
    - Encoding Date and Time
    - Handling Time Series Data
2. Data Processing:
    - Data Validation
    - Data mining
    - Data Filtering
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
The assessment involves scrutinizing fluctuations and patterns of passenger movement at various stations over time, with a specific focus on their impact on public transportation, particularly trains, throughout the specified time frame. The objective is to evaluate the overarching effect, if any, on public transportation systems, giving special attention to the train infrastructure. This comprehensive analysis aims to identify trends, anticipate challenges, and inform strategic decision-making for optimizing the efficiency and adaptability of the public transportation network, with a specific emphasis on the train services.

# Conclusion &  Insights
Both total entries and total exits exhibit similar trends, indicating a notable correlation between these two variables. The observed fluctuations in both series may suggest the presence of seasonal or periodic influences on passenger movement. Interestingly, forecasts project a decline in both total entries and total exits over the projected period. To achieve a comprehensive analysis, consideration of external factors such as economic conditions, public health situations, and transportation policies is essential. Valuable insights can be gained through stakeholder feedback, providing additional context and understanding of the factors influencing passenger movement. To enhance forecasting and decomposition analyses, a recommendation is made to explore the development of sophisticated machine learning models. These models can contribute to more accurate predictions and a nuanced understanding of underlying patterns. The implications for public transportation encompass strategic service planning and resource allocation, operational adjustments, technology integration, effective communication strategies, and the adaptation of systems to external shocks.

# References:
Autoridad de Transporte Integrado. (2021, March 17).Número de Pasajeros del Tren Urbano (Patrocinio).Indicadores.PR.https://indicadores.pr/dataset/numero-de-pasajeros-del-tren-urbano
