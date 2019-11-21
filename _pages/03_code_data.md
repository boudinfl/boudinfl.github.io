---
layout: default
title: Code & Data
permalink: /code/
---

# Code
{: .underline}

- [`pke`](https://github.com/boudinfl/pke)
  is an open source python-based keyphrase extraction toolkit. It provides
  an end-to-end keyphrase extraction pipeline in which each component can be
  easily modified or extented to develop new approaches. This toolkit also allows for
  easy benchmarking of state-of-the-art keyphrase extraction approaches, and
  ships with supervised models trained on the
  [SemEval-2010 dataset](https://github.com/boudinfl/semeval-2010-pre).

- [`takahe`](https://github.com/boudinfl/takahe)
  is a multi-sentence compression module. Given a set of redundant
  sentences, a word-graph is constructed by iteratively adding sentences to it.
  The best compression is obtained by finding the shortest path in the word
  graph. A keyphrase-based reranking method can be applied to generate more
  informative compressions.

# Datasets
{: .underline}

 - [A Large-Scale Dataset for Keyphrase Generation on News Documents (KPNews)](https://github.com/ygorg/KPTimes)  
   A large-scale dataset of 279,923 news texts paired with editor-curated keyphrases for training and evaluating neural keyphrase generation models on the news domain.

 - [Preprocessed SemEval-2010 benchmark dataset](https://github.com/boudinfl/semeval-2010-pre)  
   The SemEval-2010 benchmark dataset for automatic keyphrase extraction already preprocessed at four increasingly sophisticated levels of linguistic preprocessing.

 - [Digital archive of French research articles in Natural Language Processing (TALN Archives)](https://github.com/boudinfl/taln-archives)  
   TALN Archives is a digital archive of French research articles in Natural
   Language Processing. It contains the articles published at the TALN and
   RECITAL conferences from 1997 to 2015.

 - [LINA Multi-sentence Compression dataset (LINA-msc)](https://github.com/boudinfl/lina-msc)  
   LINA-msc is a dataset for evaluating Multi-sentence Compression in French. It
   is made of 40 sets of related sentences along with reference compressions
   composed by human assessors.

 - [CLinical Information Retrieval Evaluation Collection (CLIREC)](https://github.com/boudinfl/CLIREC)  
   CLIREC is a a test collection for clinical IR. From a set of systematic
   reviews, we have generated 423 queries with relevance data. Relevance
   judgments were manually collected from the References section containing the
   citations from which the synthetized results of the review were extracted.