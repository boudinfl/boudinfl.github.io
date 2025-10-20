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

# Models
{: .underline}

 - [`bart-large-kp20k`](https://huggingface.co/taln-ls2n/bart-base-kp20k)
    is a [bart-large](https://huggingface.co/facebook/bart-large) model for scientific keyphrase generation fine-tuned on the [KP20k dataset](https://huggingface.co/datasets/taln-ls2n/kp20k).

 - [`bart-base-kp20k`](https://huggingface.co/taln-ls2n/bart-base-kp20k)
    is a [bart-base](https://huggingface.co/facebook/bart-base) model for scientific keyphrase generation fine-tuned on the [KP20k dataset](https://huggingface.co/datasets/taln-ls2n/kp20k).

# Datasets
{: .underline}

 - [`pararev`: A dataset of revised scientific paragraphs with revision instructions](https://huggingface.co/datasets/taln-ls2n/pararev)
   A dataset of revised scientific paragraphs, providing pairs of original and revised versions enriched with detailed revision instructions and a manually annotated evaluation subset, enabling research on context-aware and instruction-guided scientific text revision.

 - [`CASIMIR`: A Corpus of Scientific Articles enhanced with Multiple Author-Integrated Revisions](https://huggingface.co/datasets/taln-ls2n/CASIMIR)
   A dataset of 15,646 scientific articles from OpenReview, providing sentence-aligned revisions across multiple versions along with peer reviews, automatically extracted edits, revision intentions, and paragraph-level metadata to support studies on scientific writing and revision.

 - [`silk`: <u>Si</u>lver-standard <u>ke</u>yphrases from citation contexts for domain adaptation](https://huggingface.co/datasets/taln-ls2n/silk)  
   A dataset of synthetic samples for adapting keyphrase generation models to new domains. It contains synthetic samples for three specific domains: Natural Language Processing, Astrophysics and Paleontology, along with human-labeled test sets to evaluate keyphrase generation performance across these domains.

 - [`kp-biomed`: A Large-Scale Dataset for Biomedical Keyphrase Generation](https://huggingface.co/datasets/taln-ls2n/kpbiomed)  
   A large-scale dataset of 5.6 million PubMed abstracts with author assigned keyphrases for training and evaluating neural keyphrase generation models on the biomedical domain.

 - [`KPNews`: A Large-Scale Dataset for Keyphrase Generation on News Documents](https://github.com/ygorg/KPTimes)  
   A large-scale dataset of 279,923 news texts paired with editor-curated keyphrases for training and evaluating neural keyphrase generation models on the news domain.

 - [`semeval-2010-pre`: Preprocessed SemEval-2010 benchmark dataset](https://github.com/boudinfl/semeval-2010-pre)  
   The SemEval-2010 benchmark dataset for automatic keyphrase extraction already preprocessed at four increasingly sophisticated levels of linguistic preprocessing.

 - [`wikinews-fr-100`: A Dataset of French Wikinews articles for keyphrase generation](https://huggingface.co/datasets/taln-ls2n/wikinews-fr-100)  
   A dataset of 100 French Wikinews articles published between May and December 2012, annotated with a combination of three types of reader annotations.

 - [`TALN Archives`: Digital archive of French research articles in Natural Language Processing](https://github.com/boudinfl/taln-archives)  
   TALN Archives is a digital archive of French research articles in Natural
   Language Processing. It contains the articles published at the TALN and
   RECITAL conferences from 1997 to 2015.

 - [`LINA-msc`: LINA Multi-sentence Compression dataset](https://github.com/boudinfl/lina-msc)  
   LINA-msc is a dataset for evaluating Multi-sentence Compression in French. It
   is made of 40 sets of related sentences along with reference compressions
   composed by human assessors.

 - [`CLIREC`: CLinical Information Retrieval Evaluation Collection](https://github.com/boudinfl/CLIREC)  
   CLIREC is a a test collection for clinical IR. From a set of systematic
   reviews, we have generated 423 queries with relevance data. Relevance
   judgments were manually collected from the References section containing the
   citations from which the synthetized results of the review were extracted.