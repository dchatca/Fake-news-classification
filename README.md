# Fake news classification with LSTM (Long Short-term memory) model 

About this project, this project is a hands-on project which I had found on Coursera. I think this hands-on project is very reasonable project for those who already have a little knowledge of `Neutral Network` and want to learn deeper about `Recurrent Neural Networks`, `Long Short-Term Memories`. This project will give you an overview of the basic steps to build a DL model in general and a NLP model in particular; from basic steps such as: `import library`, `load dataset`, `EDA`, `data cleaning`, `build and train model`, `access performance` to specific steps of a NLP project like `plot word-cloud`, `removing punctuation and stop words`, `tokenizing and padding on text corpus`. 


Me, after completed some DL courses on Coursera, I want to dig deeper more about NN, especially RNN and LSTM so that I choose this course. This course helps me consolidate my knowledge and gain new knowledge about natural language processing; understand the intuition behind RNN, LSTMs, how to prepare data by performing tokenization and padding. 

## Dataset

The dataset include `True.csv` with the shape is `((21417, 4))` and `Fake.csv`  with the shape is `(23481, 4)`. Cause the size of this dataset is two large to upload on Github so I zipped it. 


## EDA - Feature Engineering - Modeling 

The detail process can be found in my notebook.

You can access full here: https://github.com/dchatca/Fake-news-classification/blob/main/fake-news-classification/fake_news_classification.ipynb

## Experimental result

Bi-Directional RNN and LSTM with model accuracy : `0.9982` 


