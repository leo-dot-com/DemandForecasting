The following datasets have been used in the paper: 
"Enhancing Business Prediction Analytics with an Integrated Ensemble Approach: A Cross-domain Investigation"

The paper showcases how individual time-series, machine learning, and deep learning models have difficulties performing consistently throughout the three datasets. 
An ensemble model was develop, which overcame all these limitations, and outperformed all models across all datasets. 
The model consisted of 3 time-series models (SARIMA, ETS, Prophet), 2 machine learning models (RF, XGBoost), and 3 deep learning models (LSTM, GRU, CNN). 

Here is the dataset structure:
    --Retail.csv: Year, Month, Retail_Sales, A, B, C, D 
      # Retail_Sales is the volumne of sales. The columns A, B, C, D were not considered in the research.
      # 20 years of historical data
      # The columns Year and Month were merged together in the research
      
    --Air_Freight.csv: Year, Month, FreightTonnes
      # 22.5 years of historical data
      # The columns Year and Month were merged together in the research
      
    --HK_electricity1983_2023.csv: Year,Month,electricity_consumption
      # 40 years of historical data
      # The columns Year and Month were merged together in the research
