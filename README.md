# DataSampling
# Data Sampling in Python

Is a technique of working with a subset of the whole population is called sampling.

## Population and Sample

The population is the complete set of data that we are interested in. This in statistics, doesn't have to refer to people. In reality, there is usually no equivalent of the census. The sample is the subset of data that we are working with.

- The pandas **.sample(n=?)** method returns a random subset of rows. Setting n to 10 means 10 random rows are returned.`data[col].sample()`

## Population parameters and point estimates

A **population parameter** is a calculation made on the population dataset e.g. mean using NumPy `np.mean(data)` or Pandas `data.mean()`. A point estimate, or **sample statistic**, is a calculation based on the sample dataset. The two means maybe very similar but not identical.
 
