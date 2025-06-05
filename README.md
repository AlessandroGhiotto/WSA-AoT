# Web and Social Networks Search and Analysis

Project on AOT

TODO - notes

- ~~data gathering~~  
  didn't do a base preprocessing (stopwords, stemming...) since we are going to use different models and the preprocessing may be different. Do it when necessary
- ~~graph of replies (comments) + topology analysis~~
- ~~community detection~~
  - ~~look also at the different subreddits (graph colored based on where we took submissions)~~
  - wordcloud per community
- sentiment analysis:
  - global vs over time
  - analysis per cluster (based on community detection)
  - start with lexicon based (done in class) and maybe try transformers based (huggingface)
  - things like sentiment distribution per cluster
- topic modeling (conent analysis): could be done, but also maybe not...  
  [same points of sentiment analysis]
- NER:
  - extract characters names, places...
  - look at sentiment for analyzing most lover/hated characters
  - character co-occurence graph
