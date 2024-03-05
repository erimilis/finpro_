# Increasing Ecommerce Revenue Through a Customer Classification Approach

## Background
I'm interested in retailing over the Internet. Therefore, when asked to work on a final project in the "Data Science" class at the Dibimbing Bootcamp, the topic of eCommerce was chosen as an option. After taking "Data Analysis and Machine Learning" classes at the Dicoding Bootcamp, this project is my second project on the topic of ecommerce.

### Data Source
The data set used was taken from the Kaggle website titled "ECommerce Data Analysis" <a href="https://www.kaggle.com/datasets/mmohaiminulislam/ecommerce-data-analysis" target="blank">here</a>.

Dataset concists of 6 file CSV format, containing:
<li>1m fact records
<li>264 items
<li>726 stores
<li>99999 times
<li>39 trans
<li>9191 customers

### Steps Taken
<li>Step #1 - Data Preparations</li>
      + Activities:
         - Data loading
         - Data cleansing
         - Data joining
      + Main data:
         - 32 columns
         - 1m records

<li>Step #2 - EDA</li>
Activities:
  - Data understanding
  - Data visualization

<li>Step #3 - RFM modeling</li>
    Activities:
    - Data processing
    - Data modeling
    - Data visualization
<li>Step #4 - Conclusion and Recommendation</li>
<li>Step #5 - Reporting and Presentation</li>

### RFM Modeling
RFM score segmentation is grouped into 5 consumer groups with the following rules:
<li>"Hibernating" is a consumer who has not made a transaction for a very long time, namely with R = 1</li>
<li>"Need attention" is a consumer who has not made a transaction for a long time, i.e. with R = 2</li>
<li>"Loyal Customers" are consumers who usually make transactions, namely with R = 3</li>
<li>"Promising" are consumers who shop frequently with a fairly frequent shopping frequency, namely with R = 4 or 5, with F = 1 to 3</li>
<li>"Champions" are loyal consumers, who shop frequently, namely with R = 4 or 5, with F = 4 or 5.</li>

## Summary

![https://github.com/erimilis/finpro_/images/rfm1.png](https://github.com/erimilis/finpro_/blob/main/images/rfm1.png?raw=true)
This chart shows that:
1. Consumers are so active that the highest recency is only 217 days, even Q2 is at 16 days
2. Consumers are used to shopping here
3. Consumers have also been shopping in large quantities.

![https://github.com/erimilis/finpro_/images/rfm2.png](https://github.com/erimilis/finpro_/blob/main/images/rfm2.png?raw=true)
The boxplot chart strengthens the previous explanation

![https://github.com/erimilis/finpro_/images/rfm3.png](https://github.com/erimilis/finpro_/blob/main/images/rfm3.png?raw=true)
The chart above shows that consumers who have high monetary value also have high frequency. This means that they are loyal consumers, shopping at the same shopping value with a large number of transactions

![https://github.com/erimilis/finpro_/images/rfm4.png](https://github.com/erimilis/finpro_/blob/main/images/rfm4.png?raw=true)
From the chart above it appears that consumers are almost evenly divided into 5 groups. Moreover, the number of hibernating consumers is almost equivalent to the promising ones. This could mean that the number of consumers can be maintained.

![https://github.com/erimilis/finpro_/images/rfm5.png](https://github.com/erimilis/finpro_/blob/main/images/rfm5.png?raw=true)
The distribution of consumer groups is indeed stronger in the recency division, so here you can see that consumer groups are clearly divided on the recency chart.
While in the frequency and monetary charts, consumers are mixed.

## Conclusion and Recommendation

From the analysis, conclusions can be drawn including:
1. eCommerce has focused on products that customers need, and customers are loyal customers for these products
2. The dataset shows that consumers have become one complete cluster, and it is not feasible to separate them into a number of clusters anymore. Even if it is split, it appears forced with no sufficient separation space as a clear cluster boundary.
3. This e-commerce is very special with its products so that not a single customer stops shopping after just one shop. From the dataset, it was found that customers had made at least 73 transactions.
4. Customers are loyal to the point of at least making transactions within a period of 2258 calendar days (more than 6 years) from data from 2014 to 2021 (7 years).

Recommendations that can be given from this data are:
1. Continue with the pattern that has been done
2. needs to be expanded with the addition of other similar products
3. needs to be promoted more widely to add new customers
4. This e-commerce has its own characteristics so that it has many loyal customers, and this characteristic can be an attractive motto in advertising
