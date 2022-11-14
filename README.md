# Wind-Energy-Forecasting
This project aims to provide a better understanding of Data Science methodologies for renewables energies to lawer carbon. We used Machine Learning ML algorithms to forecast wind electricity generation in Ireland.
The main goal is to forecast wind electricity generation to improve efficiency and reduce environment impact by using storage energy when the demand is lower than the generation capacity maintaining an optimized flow in the energy system to reduce carbon footprint. 
Outcomes:
- Forecast Wind Electricity hourly generation for the next 24h
- Compare results with predicted demand obtained by Eirgrid Smartgriddashboard.eirgrid.com 
- Highligh hours where Wind generations is higher than 70% demand 

| File | Purpose |
|------|--------|
| 1_weather_dataprep.ipynb | Load Hourly Met.ie data for 5 weather stations for the last 4 years and merge into 1 file|
| 2_IrelandElectricityData.ipynb | Load smartgriddashboard.eirgrid.com electricity generation data from Ireland for 2017-2022 and compared to SEAI monthly summary and Eirgrid data for the Republic of Ireland to check data quality | 
| 3_EDA_IrelandRenewableProject.ipynb | EDA |
| 4_MLSUP_REG_IrelandRenewableProject.ipynb | Reg prediction model | 
| 4_AR_IrelandRenewableProject.ipynb | AutoReg prediction model | 
| 4_MLSUP_KNN_IrelandRenewableProject.ipynb | KNN prediction model |
| 4_MLSUP_LOGREG_IrelandRenewableProject.ipynb | Log Reg prediction model |

This methodology was perfomed as a part of WWC mentoring program commited to empowering diverse women to excel in technology careers

Presentation
https://docs.google.com/presentation/d/1KFOSqYsmuRPp2QBOatDph09kubRqP4Zf/edit?usp=share_link&ouid=100328939236745660230&rtpof=true&sd=true

License
- Met Éirean data: Copyright Met Éireann, Source www.met.ie , Licence Statement: This data is published under a Creative Commons Attribution 4.0 International (CC BY 4.0).
- EirGrid Group Data: Supported by EirGrid Group Data, Source: www.smartgriddashboard.com , Open Data Licence.
- The notebooks, and other documents are released under a CC BY-NC-SA 4.0 license. 

Source
https://towardsdatascience.com/predicting-excess-wind-electricity-in-ireland-machine-learning-against-climate-change-part-1-d042894026a6 
https://github.com/CA683-Group99/Wind-Energy-Prediction
