# Topics 
* Interpolation
* Scatter Plot
* Bar Plot
* Histogram
* Pie Chart
* Simpson's Paradox
* Probability
* Conditional Probability
* Bayes Rule
## Interpolation 
Use neighboring values to find the missing value in a distribution.
## Scatter Plot 
Plotting each data point uniquely.
Draw a scatter plot with possibility of several semantic groupings.
`sns.scatterplot(x, y)`
## Bar Plot 
Show point estimates and confidence intervals as rectangular bars.
Generally used when data is too big to understand from scatter plot.
`sns.barplot(x, y)`
## Histogram 
Flexibly plot a univariate distribution of observations.
Used for frequency measurement of data points ( mainly 1D data ).
`sns.distplot(x)`
## Pie Chart 
To visualize relative data ( data that are interrelated to each other ).

    import matplotlib.pyplot as plt
    #Data to plot
    labels = 'Python', 'C++', 'Ruby', 'Java'
    sizes = [215, 130, 245, 210]
    colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
    explode = (0.1, 0, 0, 0)  # explode 1st slice
    #Plot
    plt.pie(sizes, explode=explode, labels=labels, colors=colors,
    autopct='%1.1f%%', shadow=True, startangle=140)
    plt.axis('equal')
    plt.show()

## Probability
Probability tells us how often some event will happen after many repeated trials.
## Conditional Probability
A conditional probability is the probability of an event, given some other event has already occurred. Probability that a certain event will occur given some knowledge about the outcome or some other event.

    P(X, Y) = P(X|Y) * P(Y)
    P(X) = P(X|Y) * P(Y) + P(X|⌐Y) * P(⌐Y)
## Bayes Rule

    P(X|Y) = P(X, Y)/P(Y)
    P(Y|X) = P(Y, X)/P(X)
    

<!--stackedit_data:
eyJoaXN0b3J5IjpbOTY3NDE2NzAsLTU2NjIzNzU5MCw4ODMyNT
c2NTUsLTE0MDc4NTEyODksLTEzNjI5MTQ5OTBdfQ==
-->