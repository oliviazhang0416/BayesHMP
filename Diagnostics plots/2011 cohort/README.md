This folder includes the trace plots, ACF plots and Rhat plot for the 2011 NHATS cohort!

① Trace plot: the estimated values were plotted across each iteration for each chain. 
  What we want: a random bouncing around an average value.

② ACF plot: a plot of a series of correlations of a parameter with specific lags of itself. Autocorrelation does not bias estimates, but increased autocorrelation may suggest a more inefficient/slower exploration of the parameter space. At lag zero, the series estimates are perfectly correlated with themselves, so that’s where the plot usually starts. 
  What we want: Quick drop off, but not really that important. By the time you find it’s an issue, your model has already run.

What we want: Quick drop off, but not really that important. By the time you find it’s an issue, your model has already run.
③ Rhat plot: The R̂ (or Rhat) statistic measures the ratio of the average variance of samples within each chain to the variance of the pooled samples across chains. If all chains are at equilibrium, these will be the same and R̂ will be 1.0. If the chains have not converged to a common distribution, the R̂ statistic will be greater than one. 
  What we want: values near 1.0 and less than 1.05. 
