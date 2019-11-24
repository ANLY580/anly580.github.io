---
week: 11
day: Nov 19
title: Natural Language Understanding
tags: [nlu, context]
---

## Access the Notebook

- [https://github.com/anyl580/lectures/tree/master/11-natural-language-understanding](https://github.com/anyl580/lectures/tree/master/11-natural-language-understanding)

## What is Natural Language understanding

From [https://ruder.io/4-biggest-open-problems-in-nlp/](https://ruder.io/4-biggest-open-problems-in-nlp/)

> "I think the biggest open problems are all related to natural language understanding. [...] we should develop systems that read and understand text the way a person does, by forming a representation of the world of the text, with the agents, objects, settings, and the relationships, goals, desires, and beliefs of the agents, and everything else that humans create to understand a piece of text. Until we can do that, all of our progress is in improving our systems' ability to do pattern matching." - Kevin Gimpel

## NLP Tasks related to NLP

- Check out [http://nlpprogress.com/](http://nlpprogress.com/)
- And don't forget to subscribe to the newsletter here!  [http://newsletter.ruder.io/](http://newsletter.ruder.io/)

## Re-cap on the intersection of data science and NLP

**Perspective #1**

- **Answering questions from text data sets to generate actionable intelligence.** For example, 
    - Do people largely agree/disagree, like/dislike our product/brand?
    - Who was the author of this piece?
    - Which documents are about politics?
- **Business analytics** - building tools to help users generate insights from textual data
- **Building predictive models to generate understanding of textual data as it becomes available**

**Perspective #2**

- **Data Science** - text analytics around clustering, classification, and basic extraction tasks
- **NLP Research** - Development of new algorithms and multi-task systems; HLT & NLU fall in this space and are topic of this week!
- **Computational Linguistics** - Using data and algorithms to examine language from a scientific perspective

All three tracks require the basic knowledge you are learning. How far you decided to go with NLP as a data scientists depends on you!

## Readings

- J&M contains [whole chapters](https://web.stanford.edu/~jurafsky/slp3/) on the topical material touched upon this week.

## References from the Lecture

- Google AI Blog -  [https://www.blog.google/products/search/search-language-understanding-bert/](https://www.blog.google/products/search/search-language-understanding-bert/)
- Google Knowledge Graph - [https://developers.google.com/knowledge-graph](https://developers.google.com/knowledge-graph)
- DBpedia structured KB derived from wikimedia data - [https://wiki.dbpedia.org/about](https://wiki.dbpedia.org/about)
- Relation Extraction tutorial - [Knowledge Graphs in Theory and Practice 2017 (Aggarwal, Bhatia from IBM Research](http://sumitbhatia.net/papers/KG_Tutorial_CIKM17_part1.pdf)
- [CSAIL annotation guide for Referring Expressions and Co-Reference](http://projects.csail.mit.edu/workbench/update/guides/02%20-%20Referring%20Expressions%20and%20Co-reference_v2.1.2.pdf)
- Peldszus and Stede 2016 - [Rhetorical structure and argumentation structure in monologue text](https://pdfs.semanticscholar.org/6eae/4638ce558188803580a791aceb29602c00c5.pdf)
-  Grosz and Sidner 1980 - [Attention, Intentions, and the Structure of Discourse](https://www.aclweb.org/anthology/J86-3001.pdf)
-  Clark et al. 2018 - [Think you have Solved Question Answering? Try ARC, the AI2 Reasoning Challenge?](https://arxiv.org/pdf/1803.05457.pdf)
-  Zellers et al. 2018 - [Swag: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference](https://arxiv.org/pdf/1808.05326.pdf)
-  Dale and Reiter (2000) [Building Natural Language Generation Systems](https://arxiv.org/pdf/cmp-lg/9605002.pdf)
- Primer.ai - https://primer.ai/blog/quicksilver/
- Xu et al. (2015) - [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/pdf/1502.03044.pdf)
- Pennington, Socher, Manning (2014) - [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/pubs/glove.pdf)
- Peters et al. (2018) - [Deep contextualized word representations](https://arxiv.org/pdf/1802.05365.pdf)
- NAACL 2018 presentation from Peters et al. (2018) - [Deep contextualized word representations](https://www.slideshare.net/shuntaroy/a-review-of-deep-contextualized-word-representations-peters-2018)
- Sanh, Wolf, and Ruder (2018) - [A hierarchical multi-task approach for learning embeddings from semantic tasks](https://arxiv.org/pdf/1811.06031) (HMTL)

## Code & Demos

- There are a number of demos on the AllenNLP site. For example, [https://demo.allennlp.org/reading-comprehension](https://demo.allennlp.org/reading-comprehension)
- Demo of GPT-2 - [https://talktotransformer.com/](https://talktotransformer.com/)
- And another demo from [OpenAI](https://openai.com/blog/better-language-models/)
- But also read... [https://srconstantin.wordpress.com/2019/02/25/humans-who-are-not-concentrating-are-not-general-intelligences](https://srconstantin.wordpress.com/2019/02/25/humans-who-are-not-concentrating-are-not-general-intelligences)
- HuggingFace website - [https://huggingface.co/](https://huggingface.co/)
- HuggingFace HMTL - [https://huggingface.co/hmtl/](https://huggingface.co/hmtl/)
- Inspect word2vec - [https://github.com/chrisjmccormick/inspect_word2vec](https://github.com/chrisjmccormick/inspect_word2vec)
- Tokenizing when using pre-built embeddings - [https://www.kaggle.com/alhalimi/tokenization-and-word-embedding-compatibility](https://www.kaggle.com/alhalimi/tokenization-and-word-embedding-compatibility)
- Creating your own custom embeddings - [https://rare-technologies.com/word2vec-tutorial/](https://rare-technologies.com/word2vec-tutorial/)
- Yet another blogger on the same topic...you should be able to find many examples online -  [https://www.shanelynn.ie/word-embeddings-in-python-with-spacy-and-gensim/](https://www.shanelynn.ie/word-embeddings-in-python-with-spacy-and-gensim/)
