# Comparing Open-Access Database and Traditional Intensive Care Studies: A Literature Mapping Analysis Using Machine Learning 


## Table of Contents

* [Contributors](#contributors)
* [Contents](#contents)
* [Data](#data)
* [Notebooks](#folders)
* [Dependencies](#dependencies)


## Contributors
Yuhe Ke, Rui Yang, Nan Liu

<!-- Contents -->
## Contents
The volume of research literature on critical care has experienced exponential growth over the past two decades, rendering traditional bibliometric methods inadequate for analyzing such vast datasets. This necessitates the employment of machine learning (ML) and natural language processing (NLP) techniques to investigate research trends and uncover knowledge gaps. In this study, we utilized uniform manifold approximation and projection (UMAP) and the BERTopic algorithm to explore the differences and similarities between open-access database studies and traditional intensive care studies. Our objective is to identify existing knowledge gaps and explore ways in which they can complement each other.<br />

<!-- Data -->
## Data
Publication abstracts were obtained from Web of Science. The search result was on January 18, 2023. <br />

<!-- Notebooks -->
## Notebooks
* [UMAP](UMAP.ipynb): jupyter notebook with UMAP algorithm
* [BERTopic]: jupyter notebook with BERTopic algorithm

<!-- Dependencies -->
## Dependencies
Key packages used in the model:<br />
* bertopic <br />
* gensim <br />
* nltk <br />
* sklearn <br />
* umap <br />

