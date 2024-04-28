The project is done as a mini project as part of the "Data Analytics" course at Redi School of Digital Integration in Berlin, presented on 24 April 2024.

New Delhi in India was selected is study area with dataset ranging from 01 January 2013 to 24 April 2017. This is a daily time series dataset with 4 variables: temperature, pressure, humidity and wind velocity. 
Dataset link: https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data

Python is used as tool with pachkages such as pandas, numpy, matplotlib and seaborn. There were no null value in the dataset, but there were few unnatural values which needed to be dropped. 

According to theory, we know that there is a correlation between temperature, pressure and humidity. We were interested to see how it works in the nature. 

So, we plotted seasonal mean of the variables to get an intuition of the correlation between the varables. Later, we got Pearson and Spearman correlation between variables. We found a good Pearson and Spearman inverse correlation between temperature and relative humidity. 
On the other hand, we found a better inverse Spearman correlation than Pearson correlation between variables. It means, the correlation between temperature and humidity is linearly related with similar amount, whereas there is a very good monotonic inverse relationship 
betwee temperature and pressure, but the relationship is not so linear.


