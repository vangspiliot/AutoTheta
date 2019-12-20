# AutoTheta
Generalizing the Theta method for automatic forecasting

The Theta method, as originally proposed by Assimakopoulos and Nikolopoulos (2000), is generalized for automatic forecasting by introducing three extensions on its framework to boost its performance. This includes (i) considering both linear and non-linear trends, (ii) allowing to adjust the slope of such trends, and (iii) introducing a multiplicative expression of the underlying forecasting model along with the existing, additive one. 

More specifically, AutoTheta if capable of the following:
* To include models of both linear and non-linear trends, including exponential ones.
* To allow the slope of the trend to be adjusted so that forecasts are either damped or expanded when needed.
* To permit a multiplicative expression of the underlying forecasting model, along with the additive one, allowing the components of level, trend, and seasonality to be connected in either a multiplicative or an additive way.
* To use simple validation criteria to select the most appropriate model, out of all possible ones, and use such a model to predict each time series.
* To use a formula for estimating the corresponding prediction intervals, based on the residuals of the selected model and the frequency (number of the periods within a seasonal cycle) of the series to be predicted.

References
Assimakopoulos, V., & Nikolopoulos, K. (2000). The theta model: a decomposition approach to forecasting.International Journal of Forecasting, 16, 521–530
Spiliotis, E., Assimakopoulos, V., & Nikolopoulos, K. (2019).  Forecasting with a hybrid method utilizingdata smoothing, a variation of the theta method and shrinkage of seasonal factors. International Journal of Production Economics, 209, 92–102
