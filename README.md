# UK Equity Seasonality and Regime Analysis

This project builds a Python-based financial econometrics framework to examine whether UK equity returns exhibit month-of-the-year seasonality. It uses FTSE All-Share Index data to test whether calendar anomalies, such as the January effect or December effect, persist across different macro-financial regimes.

The objective is to replicate and extend classic market seasonality research in a modern UK equity market setting using time-series analysis, non-parametric tests, variance tests, rolling-window analysis, and regime-based comparisons.

## Project Objectives

- Examine whether UK equity returns show month-of-the-year seasonality
- Test whether the classic January effect appears in the FTSE All-Share Index
- Identify alternative seasonal anomalies such as December or April effects
- Analyse whether seasonal premia are stable across macro-financial regimes
- Evaluate whether seasonal patterns arise from autocorrelation or differences in monthly return distributions
- Assess the persistence of the strongest anomaly using rolling-window analysis

## Methods

- Daily price cleaning and monthly log-return construction
- Descriptive statistics by calendar month
- Autocorrelation function analysis
- Kruskal–Wallis non-parametric distribution tests
- Bartlett tests for variance homogeneity
- One-way ANOVA and month-effect comparisons
- Rolling-window analysis of the December effect
- Regime-based comparison across different macro-financial periods
- Ljung–Box test for time-series dependence

## Key Findings

- The UK equity market does not show a strong January effect over the sample period.
- December exhibits the strongest positive seasonal premium, with April also showing a secondary positive effect.
- June and September show weaker or negative average return patterns.
- The December premium remains positive across multiple macro-financial regimes.
- Autocorrelation analysis suggests that seasonality is not mainly driven by simple monthly return dependence.
- Rolling-window results indicate that the December effect has been persistent but time-varying.

## Key Measures

- Monthly log returns
- Mean and truncated mean returns
- Standard deviation
- Skewness and kurtosis
- Sharpe ratio by regime
- Kruskal–Wallis test statistic
- Bartlett test statistic
- ANOVA statistics
- Rolling-window seasonal premium
- Ljung–Box test statistics

## Tools

- Python
- pandas
- NumPy
- scipy
- statsmodels
- matplotlib
- Jupyter Notebook
├── data_sample/
├── figures/
└── requirements.txt
