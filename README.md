# Tech_optimum
![image](https://user-images.githubusercontent.com/92415264/179381684-1eaa96ef-b451-437f-ba85-bd87bacbe4bb.png)

## Inspiration
Our inspiration for this project was the recent dip in tech stalks across America. We wanted to predict the value of stocks ahead of time so we wouldn't make the worst decisions when it came to investing. Machine learning could also be better at predicting future values and changes of stocks than an educated human.

## What it does
Our model predicts the stock prize fir a specific company based on past behavior which it is trained on

## How we built it
We used deep learning. We used the Sequential Keras model with the LSTM (Long short-term memory) algorithm. The LSTM algorithm captures historical trends and makes predictions based on the data it collects.

## Challenges we ran into
Our original plan was to make a web app that users could interact with to predict stocks. Unfortunately, Streamlit (flask alternative) wasn't compatible with Jupyter Notebook.

## Accomplishments that we're proud of
Our model accuracy is 96% (worst case on average) to even 99.97% (best case). The LSTM algorithm is powerful, which is why we used it.

## What we learned
We learned a new implementation of deep learning in algorithmic trading, and we learned a bunch about the stock market.

## What's next for Bear or Bull
In the future, we hope to make a flask web app so users could use it. We also would like to train it on way more data of longer periods of stock market data for companies. We would also like it to be converted into other formats like an app.
