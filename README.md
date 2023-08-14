# Bike-Sharing-Prediction
We need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. 

## Table of Contents
* General Info
* Technologies Used
* Conclusions

## General Information
* We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
* From the line otained we can see that temp has the highest positive effect on the count followed by yr and winter whereas holiday, windspeed, hum and Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist has a negative effect on the count.
* The r-squared and adj. r-squared for the train model came out to be 0.816 and 0.812 whereas in case of test dataset it comes out to be 0.8033 and 0.792
* The independent variables important for predicting the cnt comes out to be yr,holiday temp,hum,windspeed,summer,winter, 'Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist',Aug and Sep
We can see that the equation of our best fitted line is:

**𝑐𝑜𝑢𝑛𝑡=4832.95×𝑡𝑒𝑚𝑝+1995.79×𝑦𝑟+1257.62×𝑤𝑖𝑛𝑡𝑒𝑟+1043.98×𝑠𝑒𝑝+926.90×𝑠𝑢𝑚𝑚𝑒𝑟+503.21×𝐴𝑢𝑔−201.06×𝑀𝑖𝑠𝑡+𝐶𝑙𝑜𝑢𝑑𝑦,𝑀𝑖𝑠𝑡+𝐵𝑟𝑜𝑘𝑒𝑛𝑐𝑙𝑜𝑢𝑑𝑠,𝑀𝑖𝑠𝑡+𝐹𝑒𝑤𝑐𝑙𝑜𝑢𝑑𝑠,𝑀𝑖𝑠𝑡−734.95×ℎ𝑜𝑙𝑖𝑑𝑎𝑦−1983.76×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑−2657.93×ℎ𝑢𝑚**

## Technologies Used
* NumPy - 1.23.5
* Pandas - 1.5.3
* Seaborn - 0.12.2
* SkLearn - 1.2.2
* statsmodels - 0.13.2
