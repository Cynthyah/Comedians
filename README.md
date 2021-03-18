# Comedians
An example of using NLP(Natural Language Processing) to analyze some common words used by some american comedians.

Natural language processing (NLP) is a branch of artificial intelligence that helps us to understand the language of man through software.

I used a youtube tutorial https://www.youtube.com/watch?v=xvqsFTUsOmc to practice the step-by-step how to use NLP techniques to analyze data (texts).

Pre-processing techniques such as tokenization, text normalization and data cleaning will be used.

NLP in Python:

- Data NLP: pandas, sklearn, re, nltk, TextBlob, gensim
- Clean/Stats: corpus, document-term matrix, word counts, sentiment analysis, topic modeling, text generation
- Design: scope, visualisation, extract insights

## Libraries

import requests

import pickle

import pandas as pd

import re

import string

import matplotlib.pyplot as plt

import scipy.sparse

from sklearn.feature_extraction.text import CountVectorizer

from collections import Counter

from sklearn.feature_extraction import text

from wordcloud import WordCloud

from bs4 import BeautifulSoup as bs

from IPython.display import set_matplotlib_formats

from textblob import TextBlob

from gensim import matutils, models

from nltk import word_tokenize, pos_tag



## Steps

- What it will be analysed ? Question 
- Where are we going to get this data ? How much data do I need ?
- Do I need to clean my data ?
- Let´s explore the data !
- Let´s apply some techniques
- Time to share insights
---
