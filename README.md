# Predict Stock Price with News. How Effective is News Headlines in Stock Price Predictions?
News headlines are often regarded as an indispensible part of stock price predictions. However, it's questionable whether this practice is effective. This repository seek anwsers to 2 questions


## 1. By adding news in stock price prediction, will the stock price prediction accuracy increase :

- [X] The following [Toward Data Science](https://towardsdatascience.com/making-a-continual-ml-pipeline-to-predict-apple-stock-with-global-news-python-90e5d6610b21) tutorial is modified. By removing news to train the ML and compare against the original model, the following accuracy is obtained,

Prediction with News | Prediction without News
 ------------ | -------------
 73% | 70%

Removing news from the original ML caused miniscule difference in terms of perdiction accuracy. The loss of accuracy by removing news in the prediction, can also be explained as for a high bias low variance ML problems (I chopped off the vector size by more than half), reducing feature size caused reduction in accuracy. This does not make news more important in stock price predciiton. 


- [ ] Examine whther the original tutorial model is indeed a high bias low variance model.


## 2. If news is indeed useful (must anwser the first question first!), how useful it is and what's the most efficient way to use news for stock price predictions?

- [ ] How to select news to blend with stock price prediction model? E.g., most clicked headlines, the number of a headline in a day, or compound sentiments in headlines???
- [ ] If the idea that news is useful for stock price prediction, what about social media? E.g., twitter trending topics?   
