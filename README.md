# Transform nonstationary time series into stationary time series adopting first difference transformation
Real GDP at levels is nonstationary (Rapach, 2002)⁠. In statistics, nonstationary time series refers to one whose statistical properties such as mean, variances, and covariances change over time (Iordanova, 2022)⁠. Trend, seasonality, random walks, or their combination are most associated as non-stationary behaviors. Figure 1 illustrates quarterly Finland’s GDP at levels from 1990 to 2020, which shows a certain trend that acts like nonstationary behavior. In contrast to nonstationary time series, stationary time series are the one for which the probabilistic behavior of every collection of values in that time series does not change when shifted in time (Casella et al., 2010, p. 22)⁠. The problem with time series forecasting in case of nonstationarity is that it is difficult to measure the dependence between the values if there is no regularity in the dependence structure. In other words, to achieve reliable statistical analysis, the mean and the autocovariance functions need to satisfy the conditions of stationarity (Casella et al., 2010, p. 57)⁠.  In that sense, nonstationary data needs to be transformed into stationary data.

Turning back to the case of GDP time series, research in the topic of GDP forecasting generally transforms data of GDP to stationary characteristics by adopting GDP growth. GDP growth here refers to an increase or a decrease of GDP at year t compared to GDP at year t-1, if we are considering the difference in one-year period. The mathematical expression of GDP growth rate is the subtraction of the natural logarithm of GDP at year t-1 from the natural logarithm of GDP at year t. Figure 2 presents quarterly GDP growth of Finland from 1990-2020. As can be seen, the line in Figure 2 does not show any specific trend or cycle and the mean and variance is constant,  making it a relevant object for forecasting model. To further confirm quarterly GDP growth rate of Finland is stationary, Augmented Dickey-Fuller (ADF) test is employed to decide whether we can reject the null hypothesis of the test that the series is nonstationary. The ADF P-value is 4.3%, less than 5% of significance level, meaning that we can reject the null hypothesis.

## Reference

[1] Casella, G., Fienberg, S., & Olkin, I. (2010). Time Series Analysis and Its Applications. In Springer Texts in Statistics. Springer New York Dordrecht Heidelberg London. https://doi.org/10.1007/978-1-4419-7865-3 <br>
[2] Iordanova, T. (2022). An Introduction to Non-Stationary Processes. Fundamential Analysis. https://www.investopedia.com/articles/trading/07/stationary.asp <br>
[3] Rapach, D. E. (2002). Are Real GDP Levels Nonstationary? Evidence from Panel Data Tests. Southern Economic Journal, 68(3), 473. https://doi.org/10.2307/1061713
