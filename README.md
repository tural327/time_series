# time_series

Here I made predictions time series dataset using tf

I used 90% of data for my training sec. 10% for testing

Model traing based prediction of Open parametrs

First I did Dickey-Fuller test for checking stationary

![](https://github.com/tural327/time_series/blob/main/Dickey-Fuller%20test.png)

After testing of my data I realized that data I need make data normalization for my dataset

After normalization model created using tf LSTM layer with 128 unites (FYI for loss function was mse)

model trained well as you can see: 

![](https://github.com/tural327/time_series/blob/main/loss%20vs%20val_loss.png)


and testing was good :


![](https://github.com/tural327/time_series/blob/main/Reuslt.png)

