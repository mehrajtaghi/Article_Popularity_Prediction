# Article_Popularity_Prediction
predicting how many times a wikipedia article will be read in next 30 days with Facebook Prophet and Neural Prophet.


Dataset: wiki_machine_learning.csv
Description: Data represents how many times Wikipedia page of Machine Learning was read during
some period of time. The data is presented in csv format as follows: date, count, lang, page, rank,
month, title. Null values of count column are identified with 0, please remove them while
preprocessing.
Task: You are asked to create a model using Facebook Prophet and Neural Prophet algorithms to
predict how many times the article will read for the future 30 days (count column).
