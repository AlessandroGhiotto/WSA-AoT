# Web and Social Networks Search and Analysis

Project on AOT

TODO - notes

- ~~data gathering~~  
  didn't do a base preprocessing (stopwords, stemming...) since we are going to use different models and the preprocessing may be different. Do it when necessary
- ~~graph of replies (comments) + topology analysis~~
  - ~~look also at the different subreddits (graph colored based on where we took submissions)~~
  - ~~community detection on separated time windows~~ t
- ~~community detection~~
  - wordcloud per community (spostare dove si fa content analysis)
- sentiment analysis:
  - ~~global vs over time~~
  - analysis per cluster (based on community detection - things like sentiment distribution per cluster)
  - ~~start with lexicon based (done in class) and maybe try transformers based (huggingface)~~
- topic modeling (content analysis):
  - worldcloud per community / per time window (o per grafi splittati)
  - idem per subreddit diversi
- ~~NER:~~
  - ~~extract characters names, places...~~
  - ~~look at sentiment for analyzing most lover/hated characters~~
  - ~~character co-occurence graph~~
