[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> Generated 1000 numbers from numpy.random.random below
>> t = np.random.random(1000)

>> Plotted the numbers in t to a proability mass function
>> pmf = thinkstats2.Pmf(t)
>> thinkplot.Pmf(pmf, linewidth=0.1)
>> thinkplot.Config(xlabel='Random variate', ylabel='PMF')
>> The pmf shows that the 1000 numbers all have a probability adding up to 1, so the whole graph is full.

>> Plotted the numbers in t to a cumulative mass function because the pmf did not depict the numbers properly
>> cdf = thinkstats2.Cdf(t)
>> thinkplot.Cdf(cdf)
>> thinkplot.Config(xlabel='Random variate', ylabel='CDF')
