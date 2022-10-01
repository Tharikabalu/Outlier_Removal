# Outlier_Removal

An outlier is an observation that is unlike the other observations.
It is rare, or distinct, or does not fit in some way.

Outliers can have many causes, such as:

Measurement or input error.
Data corruption.
True outlier observation 

Outlier removal techniques:

1)Standard Deviation Method

The Gaussian distribution has the property that the standard deviation from the mean can be used to reliably summarize the percentage of values in the sample.
So, if the mean is 50 and the standard deviation is 5, as in the test dataset above, then all data in the sample between 45 and 55 will account for about 68% of the data sample. We can cover more of the data sample if we expand the range as follows:

1 Standard Deviation from the Mean: 68%
2 Standard Deviations from the Mean: 95%
3 Standard Deviations from the Mean: 99.7%
A value that falls outside of 3 standard deviations is part of the distribution, but it is an unlikely or rare event at approximately 1 in 370 samples.

2)Interquartile Range Method
Not all data is normal or normal enough to treat it as being drawn from a Gaussian distribution.
A good statistic for summarizing a non-Gaussian distribution sample of data is the Interquartile Range, or IQR for short.
The IQR is calculated as the difference between the 75th and the 25th percentiles of the data and defines the box in a box and whisker plot.
