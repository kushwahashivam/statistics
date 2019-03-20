# Topics 
* Interpolation
* Scatter Plot
* Bar Plot
* Histogram
* Pie Chart
* Simpson's Paradox
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


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3OTYyOTU2NzksLTE0MDc4NTEyODksLT
EzNjI5MTQ5OTBdfQ==
-->