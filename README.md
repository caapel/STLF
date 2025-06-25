# Short-Term Load Forecasting Based on XGBoost Model

This repository contains the source materials and calculation results used in the study [***Short-Term Forecasting of Regional Electrical Load Based on XGBoost Model***](https://doi.org/)

### validation result (01/01/2025 - 01/06/2025)
| Month / <br> MAPE |  br3_pred | br3_act | br3_act_LC<br> (y:6, md:6) | br2_act_LC<br> (y:10, md:5) |
| --- | --- | --- | --- | --- |
| January | 1.725% | **1.63%** | 1.640% | 1.636% |
| February |  1.204% | 1.224% | **1.196%** | 1.242% |
| March | 1.058% | 1.138% | **1.104%** | 1.122% |
| April | 1.523% | 1.638% | 1.570% | **1.490%** |
| May | 1.675% | 1.687% | 1.618% | **1.548%** |
| **total** | 1.441% | 1.467% | 1.429% | **1.411%** |
| MAE, MW | 39.268 | 39.932 | 38.992 | **38.487** |
| Loss, RUR | 16.661.050 | 17.211.265 | **16.409.258** | 16.726.061 |
| Mean Loss, RUR | 4597.42 | 4749.25 | **4527.94** | 4615.36 |
| Median Loss, RUR | 283.1 | **198.97** | 282.37 | 319.47 |
| τ, s/it | 14.67 | 14.77 | **1.97** | 2.01 |