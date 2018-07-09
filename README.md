# Insight_NLPBasics_Workshop
A repo with files used for a workshop on the basics of NLP for the 18B Insight Data Science Fellowship in NYC. You will need the following packages:

* pandas
* numpy
* re
* spacy
* sklearn
* gensim # if you want to try out word2vec
* pickle # if you want to save things

In addition to these files you will need the following:
* [GoogleNews-vectors-negative300-SLIM.bin](https://github.com/eyaler/word2vec-slim) - this is a slim version of the pre-trained word2vec trained on Google News

## Documents for workshop:
* Workshop_Notebook.ipynb 
  * This is a notebook where I show some examples of how to do various things using NLP (tokenize, stemming, lemmatizing, removing stop words, vectorizing, finding sentiment, finding named entities)
  * In the data folder there is a .csv file of wine reviews that is hosted on [Kaggle](https://www.kaggle.com/zynicide/wine-reviews#winemag-data_first150k.csv). It includes 150K reviews of different kinds of wine, their scores, prices, and some other data.
* Workshop_TryMe.ipynb
  * This is a notebook that is relatively empty, where you can try out some of the things from my workshop. You can follow along with the tutorial notebook, and try a different wine. 