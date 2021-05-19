# MSFT_Stocks
Predicting MSFT Stocks

In this project i tried to predict Stocks from MSFT. \
I started gathering data from different companies to select which one i would predict using pandas-datareader.

![image](https://user-images.githubusercontent.com/70241561/118751649-0f577000-b838-11eb-8ee6-735e16c63926.png)

--------------------------------------

In the prediction i tried a lot of things. Mainly i tried different functiosn for the trend, then tried adding stationality to the functions. \
Did a Dickey-Fuller to see if i could use arima, wich i couldn't. (p-values for months were to high, they didnt influence that much). \
At the end i tried using prophet, a cool model form facebook for time series prediction, and a recurrent-neural net with a timelapse of 60 days. \
I choose the prophet model.

![image](https://user-images.githubusercontent.com/70241561/118751884-7a08ab80-b838-11eb-98e2-f9baa2428588.png)


![image](https://user-images.githubusercontent.com/70241561/118751916-88ef5e00-b838-11eb-97c7-d3bd05d1fac6.png)

My baseline.


![image](https://user-images.githubusercontent.com/70241561/118751937-9573b680-b838-11eb-9f6b-59aba0a8f347.png)
Random Walk noise



![image](https://user-images.githubusercontent.com/70241561/118751964-a1f80f00-b838-11eb-9afe-343d211e2579.png)

Using a cuadratic function for the trend 

![image](https://user-images.githubusercontent.com/70241561/118752019-bdfbb080-b838-11eb-87ce-fbb7b7e60aa0.png)

Combining the quadratic with months. P-values of months were to high


![image](https://user-images.githubusercontent.com/70241561/118752063-d23fad80-b838-11eb-897f-74ed2de9a75a.png)


![image](https://user-images.githubusercontent.com/70241561/118752096-e1bef680-b838-11eb-8b4c-95284ae9c60c.png)

Prophet prediction

![image](https://user-images.githubusercontent.com/70241561/118752114-ea173180-b838-11eb-8089-429583806540.png)

Prophet components



![image](https://user-images.githubusercontent.com/70241561/118752185-01561f00-b839-11eb-8954-8230228cf4d6.png)

The RNN architecture



![image](https://user-images.githubusercontent.com/70241561/118752222-10d56800-b839-11eb-8f80-03a710928653.png)

The final scores















