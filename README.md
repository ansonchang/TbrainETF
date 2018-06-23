# TbrainETF

## Design Document

ETF_DesginDoc.doc

## Data

Download from [T-Brain](https://tbrain.trendmicro.com.tw/Competitions/Details/2) and put in root folder. 

## Jupyter Notebook
```
* TBrian- ETF Prediction Final.ipynb: fb prophet model
* TBrian- ETF Prediction-SVR.ipynb: SVM Regression model
* TBrian- ETF Prediction-Weighting.ipynb: Generate Weighting prediction with 3 weeks prediction data
```

## Output
```
* ETF_predict_weight.csv: Submit prediction data in 4th week, using 3 weeks weighting prediction 
* actual_price.csv: The actual ETF price bwtween 6/11-6/15, data source is dwonlaoded from T-Brain.
* predict_pre0.csv: Calculated prediction data for 4th week.
* predict_pre1.csv: Submit prediction data in 3rd week.
* predict_pre2.csv: Submit prediction data in 2nd week.
* predict_pre3.csv: Submit prediction data in 1st week.
```
