# NLP_Summarization

##This repo consists of 2 parts, in which we apply NLP techniques to analyze articles about big data, data science, and AI.

###1. Download and parse articles (Scrapping part):
Article cache.
Extract source categorizing.The best part is that the information we want from the article is quite clean, we didn’t have to include any regex to extract the article title or text.
Extract source feed.
Extract description.

###2. NLP part:
News Article --> Download --> Parse --> Process the Natural Language of the articles (NLP) --> Summarize the Articles 


###This project demonstrates how to use ‘newspaper3k’ to download valuable information from multiple articles and how to put that data into a data frame. This maps to a functionality that we use in an android project -- EntireNews (Click to visit the organization repo)

###NLP_newspaper.ipynb file demonstrates how to use the library to download the information of an article. 
The process is quite straightforward. The best part is that the information we want from the article is quite clean, we didn’t have to include any regex to extract the article title or text.

###newspaper_to_pandas.ipynb repeats the same process on 50 links and puts that downloaded information into a pandas dataframe. These 50 articles by New York Times were downloaded, scrapped and turned into this dataframe in 39 seconds. 


