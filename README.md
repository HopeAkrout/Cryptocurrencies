# Cryptocurrencies

The senior manager for the Advisory Services Team at Accountability Accounting would like to propose offering a new cryptocurrency investment portfolio for its customers.  This repository is an aid to a report on what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.


## Summary

As it was unknown at the onset what the dataset would provide with regards to answers or if it would be beneficial to the senior manager's agenda to persuade the firm of this new investment, Supervised machine Learning was not possible as a tool.  We turned to Unsupervised Machine Learning to best learn what the data could tell us.

After cleaning and trimming the original file, the dataset was standardized, and dimensions were reduced to three principal components to find the best value for k using the Elbow Curve.  The results showed the most noticeable horizontal straightening at four clusters, which was used to create a 3D-Scatterplot.

Finally, the data was rescaled by the total coins supplied and mined and a new scatterplot was created to support or contradict the first results. Unfortunately, it appears that the only strong correlation is to see that BitTorrent is an outlier by a wide margin on both plots.
