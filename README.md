# Tech_optimum
![image](https://user-images.githubusercontent.com/92415264/179381684-1eaa96ef-b451-437f-ba85-bd87bacbe4bb.png)


### inspiration

our inspiration for this was to maximize yeild.
We wanted to predict stocks so we wouldn't make the worst decisions when it came to investing.

### how it works/runs
We made a deep-learning model.
Of course you can never fully predict the market, so our model runs on past data and predicts past prices.
As you will see, its average accuracy is 96% to even 99.97% on some runs.
Fitting the data will take a good 4 - 5 mins because although we are working with 1 column, it is a lot of data
Here we predicted the Tesla stocks from 2012 to 2019.
Our model uses an algorithm called Long short-term memory or LSTM for short.
It caputres historic trends and makes predictions off of that.

### challenge
We wanted to make a web app using streamlit (flask alternative) but it wasn't compatible with jupyter notebook.
