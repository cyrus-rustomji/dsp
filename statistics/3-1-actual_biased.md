[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> The biased data was missing, so I had to create a function called 'biased' and create a graph and the mean off of that.

>> Used the NUMKDHH function to construct the actual distribution for the number of children under 18 in the household.
>> pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')

>> Createa a plot from the pmf
>> thinkplot.Pmf(pmf)
>> thinkplot.Config(xlabel='Number of children', ylabel='PMF')

>> biased = BiasPmf(pmf, label='biased')
>> thinkplot.PrePlot(2)

>> Create a plot for the pmf and biased functions
>> thinkplot.Pmfs([pmf, biased])
>> thinkplot.Config(xlabel='Number of children', ylabel='PMF')

>> pmf.Mean()
>> Answer: 1.024205155043831
>> biased.Mean()
>> Answer: 2.403679100664282
>> This shows children under 18 think there are more children in their household then their actually are.
