---
week: 8
day: Oct 29
title: Topic Modeling
tags: [classification]
---

## Access the Notebooks
- [Overview and VSM part2](https://mybinder.org/v2/gh/anyl580/lectures/master?urlpath=notebooks/8-topic-modeling/vsm-part2.ipynb)
- [Topic model lecture (Zukas)](ANLY580_Fall2019_TopicModels.pptx)
- [Topic Model accompanying notebook](https://mybinder.org/v2/gh/anyl580/lectures/master?urlpath=notebooks/8-topic-modeling/ANLY580_Fall2019_TopicModeling.ipynb)
- [NMF Notebook](https://mybinder.org/v2/gh/anyl580/lectures/master?urlpath=notebooks/8-topic-modeling/ANLY580_Fall2019_NMF.ipynb)

## Referenced Readings

- Blei - [Probabilistic Topic Models](http://www.cs.columbia.edu/~blei/papers/Blei2012.pdf)
- [Overview of Topic Modeling](https://www.kdnuggets.com/2016/07/text-mining-101-topic-modeling.html) and key references:
  - D. Blei, A. Ng, M. Jordan. Latent Dirichlet Allocation. Journal of Machine Learning Research, 3: 993-1022, 2003
  - R. Mihalcea, P. Tarau. TextRank – bringing order into texts. In Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP 2004). 2004
  - L. Page, S. Brin, R. Motwani, T. Winograd. The PageRank Citation Ranking: Bringing Order to the web. technical report, Stanford University. 1998
  - G.Erkan and D.R. Radev, LexRank: Graph-Based Lexical Centrality As Salience in Text Summarization, J. Artificial Intelligence Research, vol. 22, pp. 457-479, 2004
- Chris Moody article on ["Stop using word2vec"](https://multithreaded.stitchfix.com/blog/2017/10/18/stop-using-word2vec/)

### Evaluating LDA (topic coherence and perplexity)
 - [Evaluating LDA - step-by-step guide](https://towardsdatascience.com/evaluate-topic-model-in-python-latent-dirichlet-allocation-lda-7d57484bb5d0)
 - Roder, Both, and Hinneburg [Exploring the Space of Topic Coherence Measures](http://svn.aksw.org/papers/2015/WSDM_Topic_Evaluation/public.pdf)
 - Newman, Lau, Grieser & Baldwin [Automatic Evaluation of Topic Coherence](https://www.aclweb.org/anthology/N10-1012.pdf)
 - [Evaluating topic models in R](https://cfss.uchicago.edu/notes/topic-modeling)
 - [Advanced Modeling in Python: Evaluation of Topic Modeling: Topic Coherence](https://datascienceplus.com/evaluation-of-topic-modeling-topic-coherence/)

### Non-Negative Matrix Factorization
- Gillis [Introduction to NNMF](https://arxiv.org/abs/1703.00663)
  - [Notes on Gillis](https://singsoftnext.com/introduction-to-nonnegative-matrix-factorization/)
- [CSAIL Video on New Algorithms for NNMF and Beyond](https://www.youtube.com/watch?v=kSfwY68gQ9I&feature=youtu.be&list=PLtelmYjrNBARmdTzrqUGQcoGCHdg5l8MO)
- [Matrix Factorization for Topic Models](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.702.4867&rep=rep1&type=pdf)
- [Overview of Matrix Factorization Techniques](https://towardsdatascience.com/overview-of-matrix-factorisation-techniques-using-python-8e3d118a9b39)
- [Non-negative matrix factorization for recommendation systems](https://medium.com/logicai/non-negative-matrix-factorization-for-recommendation-systems-985ca8d5c16c)
- [Winning the Netflix Prize: A Summary](https://blog.echen.me/2011/10/24/winning-the-netflix-prize-a-summary/)
- Kumar and Sridhar [Unsupervised Topic Modeling for Short Texts Using Distributed Representations of Words](https://www.aclweb.org/anthology/W15-1526.pdf)
- David Mimno presentation [The details: training and valida1ng big models on big data](https://mimno.infosci.cornell.edu/slides/details.pdf)
- David Mimno course on [topic models and other unsupervised matrix factorization methods](https://mimno.infosci.cornell.edu/info6150/)

### Topic Modeling Visualization
- [Topic Database of NIH-funded grants](http://www.nihmaps.org)
- [Database of NIH grants using machine-learned categories and graphical clustering](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5361216/pdf/nihms430007.pdf)
- [Topic Explorer](https://www.hypershelf.org)

### Number of topics
- [Greene, O'Callaghan, and Cunningham - How many Topics? Stability Analysis for Topic Models](http://derekgreene.com/papers/greene14topics.pdf)
- [Wray Buntine response on Quora](https://www.quora.com/Latent-Dirichlet-Allocation-LDA-What-is-the-best-way-to-determine-k-number-of-topics-in-topic-modeling)

## Gensim

- [Gensim complete beginner's guide](https://radimrehurek.com/gensim/auto_examples/index.html#core-tutorials)
- [Gensim tutorials](https://radimrehurek.com/gensim/auto_examples/index.html#core-tutorials)
- [Example Gensim Notebooks](https://markroxor.github.io/gensim/tutorials/index.html)

## Notebooks and Code

- Chris Pott's [Dimensionality reduction and vector space models](https://nbviewer.jupyter.org/github/cgpotts/cs224u/blob/spring-2019/vsm_02_dimreduce.ipynb)
- Sklearn [Fightin words implementation](https://github.com/kenlimmj/fightin-words)
- [LDA and T-SNE Interactive Visualization](https://www.kaggle.com/ykhorramz/lda-and-t-sne-interactive-visualization)
- - [R - Select number of topics for LDA model](https://cran.r-project.org/web/packages/ldatuning/vignettes/topics.html)
- Jacob Eisenstein [NAACL-2019 Tutorial on Modeling Language Change](https://github.com/jacobeisenstein/language-change-tutorial)
