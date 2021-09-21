Bike sharing systems have become more and more popular because they can help solve problems
such as excess CO2 emissions and traffic congestion. The analysis work is very necessary to control
the system to obtain better performance as well as to develop appropriate strategies to meet user
needs.

In this project, we are working with the ‘Vélib’ data set, related to the bike sharing system
of Paris, which is available on R. The data are loading profiles, collected every hour, of various
bike stations over one week (from Monday 12 am to Sunday 11 pm). The loading of a station
corresponds to the number of available bikes divided by the maximum number of bikes that the
station can accommodate. A loading of 1 means that all bikes are available. A loading of 0 means
that the station is empty.

First,we are going to apply some descriptive statistics to better know and understand the
data set. Then, we will use the principal component analysis (PCA) to reduce significantly the
number of variables (Here the variables correspond to the hours, so we have initially 168 variables).
We also compare different results obtained by studying the initial full data set and by using the
PCA. Finally, we will implement various clustering methods to detect the structure of the data, in
particular, finding different groups of stations corresponding to different features. From there, it is
possible to predict in a relative way the user group corresponding to each station.


