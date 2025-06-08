# Web and Social Networks Search and Analysis

## ⚔️ Titans of Discourse

_Attack on Titan_ (_Shingeki no Kyojin_) has cultivated a massive and global fandom, much of which congregates on online platforms such as Reddit. This project explores the social dynamics, sentiment polarity, and network structures within the many subreddit dedicated to the show. By applying data analysis, topological network exploration, community detection, sentiment analysis, and named entity recognition (NER) focused on character mentions, the study uncovers how fans interact, how discussions evolve, and how emotional tone shifts over time. Additionally, character NER offers insights into which figures dominate discourse and how they are perceived. Ultimately, this project aims to deepen our understanding of modern fan communities and their dynamic online ecosystems.

## ⚙️ Environment

To reproduce the results, create the conda environment:

```bash
conda env create -f environment.yml
conda activate reddit-topic-modeling
```

## 📚 Table of Contents

Each notebook handles a specific step in the pipeline:

1. **Data Gathering and Analysis**
   - Data Gathering
   - Basic Data Analysis
2. **Topologycal Analysis**
   - Build the graph
   - Graph Statistics
   - Centrality measure:
     1. Degree c.
     2. Betweenness c.
     3. Closeness c.
   - Graph by subreddit
3. **Community Detection**
   - Community detection
     1. Greedy modularity
     2. Louvain
     3. FluidC
     4. Infomap
   - Community detection in separated time windows
4. **Sentiment Analysis**
   - Text Preprocessing
   - Sentiment Analysis
     1. Affin
     2. NLTK Opinion Lexicon
     3. Vader
     4. Transformer based
   - Sentiment Analysis: By Communities
5. **Topic Modeling**
   - Topic Modeling per community:
     - WordCloud
     - BERTopic
   - Topic modeling per time window
6. **Named entity recognition**
   - NER:
     - en_core_web_sm
     - en_core_web_trf
   - Characters co-occurence graph:
     - Home-made vocabulary of character
     - NEL
   - Bridge with Sentiment Analysis and Community detection
     - Characters Sentiment
     - Characters per Community
     - Characters Sentiment per Community
