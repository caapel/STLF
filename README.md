# Short-Term Load Forecasting Based on XGBoost Model

This repository contains the source materials and calculation results used in the study [***Short-Term Forecasting of Regional Electrical Load Based on XGBoost Model***](https://doi.org/)

### validation result (01/01/2025 - 01/06/2025)
| Month / <br> MAPE |  XGBoost<br> br3_pred | XGBoost<br> br3_act | XGBoost<br> br3_act_LC<br> (y:6, md:6) | XGBoost<br> br2_act_LC<br> (y:10, md:5) | CatBoost<br> br3_pred | CatBoost<br> br2_act_LC(y:10, md:5) | ARIMA<br> default |
| --- | --- | --- | --- | --- | --- | --- | --- |
| January | 1.605% | **1.576%** | 1.640% | 1.636% | 1.616% | 1.827% | 11.248% |
| February |  1.233% | 1.246% | **1.196%** | 1.242% | 1.154% | 1.194% | 11.446% |
| March | 1.169% | 1.181% | **1.104%** | 1.122% | 1.190% | 1.221% | 10.091% |
| April | 1.689% | 1.619% | 1.570% | **1.490%** | 1.710% | 1.596% | 11.567% |
| May | 1.610% | 1.609% | 1.618% | **1.548%** | 1.744% | 1.770% | 11.023% |
| **total** | 1.464% | 1.449% | 1.429% | **1.411%** | 1.488% | 1.527% | 11.062%|
| MAE, MW | 39.912 | 39.346 | 38.992 | **38.487** | 40.341 | 41.396 | 277.585|
| Loss, RUR | 15.961.596 | 17.237.366 | **16.409.258** | 16.726.061 | 16.557.290 | 17.005.792 | 138.535.705 |
| Mean Loss, RUR/h | 4404.41 | 4756.45 | **4527.94** | 4615.36 | 4568.79 | 4692.55 | 38.227 |
| Median Loss, RUR/h | 262.78 | **223.77** | 282.37 | 319.47 | 259.47 |315.83 | 7271.8 |
| τ, s/it | 28.99 | 31.07 | 1.97 | 2.01 | 45.8 | **1.28** | 4.29 |