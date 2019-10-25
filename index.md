---
title: "ANYL 580 - NLP for Data Analytics"
layout: home
menuItem: "Syllabus"
menuPosition: 1
---
<h1>{{ site.courseName }}</h1>
<!--
<img src="{{ site.baseurl }}/style/header.jpg" width="100%">
-->

## Course Description

How do data scientists use tools and methods from Natural Language Processing (NLP) to process language data in order to derive insights? This course examines practical problems in content analysis using state-of-the-art NLP tools emphasizing when and how such tools are used. Topics include keyword extraction, computing similarity, topic modeling, sentiment analysis, named entity recognition, and dialogue. Tools and methods span from simple tools students build themselves to recent neural toolkits. Students will apply and extend existing software tools to text-processing tasks. Throughout, the course focuses on empirical thinking and analytical processes. A guiding principle in this class is that NLP as an applied practice does not end at deriving results, but in communicating findings to end users.


## Schedule

The official syllabus for this course is posted on [Canvas](https://georgetown.instructure.com). The syllabus is also posted here for convenience. Because this is a copy, it's possible it may be out of date. **THE VERSION ON CANVAS IS THE ONE YOU SHOULD FOLLOW.** To avert the potential for error, quizzes and assignment dates are omitted here.

| Date | Topic | Notes | Readings | Due Dates |
| --- | --- | --- | --- | --- |
| 3-Sep-19 | [Overview](syllabus/1-overview.html) | How do data science and NLP relate? NLP tasks, What is a word? | [What is a word, what is a sentence?](https://pdfs.semanticscholar.org/e727/c7fd2bf3460a36934eae64c8c5716bc28980.pdf), [Contextual word representations: A contextual introduction](https://arxiv.org/pdf/1902.06006.pdf) | Survey in Canvas |
| 10-Sep-19 | [Tools, Tokenization](syllabus/2-Tools.html) | Linux, programming environments, GitHub, crawlers, regex, text extraction, NLP libraries, Elastic / Kibana, IDE's vs notebooks, regex, text extraction, Tokenization, stemming/lemmatization, normalization | [J&M 2](https://web.stanford.edu/~jurafsky/slp3/2.pdf) | Q1 |
| 17-Sep-19 | [What if documents are not in English? Multilingual computing](syllabus/3-multilingual.html) Guest Lecturer: Linda Moreau | Unicode, multilingual text processing, transliteration, language ID | [Spolsky](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/), [Garfinkel](https://www.usenix.org/system/files/login/articles/garfinkel12-04.pdf) | Q2 |
| 24-Sep-19 | [How can we characterize documents using words?](syllabus/4-ngrams.html) | Language models, ngrams, perplexity | [J&M 3](https://web.stanford.edu/~jurafsky/slp3/3.pdf) | Q3 |
| 1-Oct-19 | [How can we classify documents (Naive Bayes)?](syllabus/5-bayes-sentiment.html) | Polarity, sentiment, framing, affect, illocutionary force, authorship, register, genre, style, profiling | [J&M 4](https://web.stanford.edu/~jurafsky/slp3/4.pdf), [Scikit-learn tutorial](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html) | Q4 |
| 8-Oct-19 | [How can we classify documents (Logistic Regression)?](syllabus/6-logistic-regression.html) | NO CLASS. WORK IN GROUPS. Continuation: compare performance with Naive Bayes | [J&M 5](https://web.stanford.edu/~jurafsky/slp3/5.pdf) | Q5, [Project #1 Due - NEW DATE 11 Oct 2019](project1.html) |
| 15-Oct-19 | <No class> | Mid-Semester Break | | |
| 22-Oct-19 | [How can we find similar documents or measure differences in text?](syllabus/7-vector-semantics.html) | Vector semantics, word embeddings, lexical semantics, frames, distributional hypothesis | [J&M 6](https://web.stanford.edu/~jurafsky/slp3/6.pdf) | Q6 |
| 29-Oct-19 | How can we discover what documents are about? Guest Lecturer: Tony Zukas | Topic modeling, summarization | [Gensim tutorials](https://radimrehurek.com/gensim/tutorial.html), [Explore notebooks here](https://markroxor.github.io/gensim/tutorials/index.html), [Moody](https://multithreaded.stitchfix.com/blog/2017/10/18/stop-using-word2vec/) | Q7, [Project #2 proposals due](proposal.html) |
| 5-Nov-19 | How does Machine Translation work? | Statistical MT and neural MT - subtasks and challenges | [Deep Learning, NLP and Representations](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/) [Visualizing a Neural MT Model](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/), [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) | Mid-Term |
| 12-Nov-19 | How can we extract information from text? | Part-of-speech tagging, ambiguity and context, information extraction, keywords, multi-word expressions | [Spacy 101](https://spacy.io/usage/spacy-101) | Q8 |
| 29-Nov-19 | Can we use NLU to answer questions or populate knowledge bases? | Q&A, entity disambiguation, semantic relations, coherence/cohesion, graph/dependency relations, pragmatics, entity resolution | [The Illustrated BERT, ELMo, and co.](http://jalammar.github.io/illustrated-bert/), [Allen NLP Models](https://allennlp.org/models) | Q9 |
| 26-Nov-19 | How do chatbots work and why is dialogue so hard?; Science, Bias, and Ethics in NLP | Grounding, dialog systems, text generation, inference; Data and society, culture and bias,  Scientific method, representativeness, benchmarking and evaluation, debiasing | [Hovy & Spruit](http://www.dirkhovy.com/portfolio/papers/download/ethics.pdf) [Inside the Alexa Prize](https://www.wired.com/story/inside-amazon-alexa-prize/) | Q10 |
| 3-Dec-19 | Project #2 Poster Presentations |  |  |
| 9-Dec-19 | No class | | | [Project #2 Due](project2.html) |

## Grading Rubric

The emphasis for grading is on practical exercises and communicating results. There are two larger assignments that involve Python/R programming. These may be done in groups of 1-4 and assignments will be submitted via GitHub Classroom. Open book quizzes in class are focused on concepts from the reading, but may also be used to drive discussion.

## Readings

Primary readings are from chapters from Jurafsky & Martin (J&M), Speech and Language Processing v. 3, [https://web.stanford.edu/~jurafsky/slp3/](https://web.stanford.edu/~jurafsky/slp3/)

### Articles
- Hovy & Spruit, [The Social Impact of Natural Language Processing](http://www.dirkhovy.com/portfolio/papers/download/ethics.pdf)
- Chris Moody, [Stop Using word2vec](https://multithreaded.stitchfix.com/blog/2017/10/18/stop-using-word2vec/)
- Joel Spolsky, [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
- Simson Garfinkel, [Programming Unicode](https://www.usenix.org/system/files/login/articles/garfinkel12-04.pdf)
- Jay Alammar, [Visual Guide to the Basics of Neural Networks](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks/)
- Christopher Olah, [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- WildML.com, [Understanding CNNs for NLP](http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/)
- Christopher Olah, [Deep Learning, NLP, and Representations](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/)
- Christopher Olah, [Visualizing a Neural MT Model](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/)
- Jay Alammar, [The Illustrated BERT, ELMo, and co.](http://jalammar.github.io/illustrated-bert/) (http://jalammar.github.io/illustrated-bert/)
- [Inside the Alexa Prize](https://www.wired.com/story/inside-amazon-alexa-prize/)

### API Guides / Documentation
- [NLTK](https://www.nltk.org)
- [Polyglot](https://polyglot.readthedocs.io)
- [Scikit-learn](http://scikit-learn.github.io/stable)
- [Gensim website tutorials](https://radimrehurek.com/gensim/tutorial.html) and [ Tutorial notebooks](https://markroxor.github.io/gensim/tutorials/index.html)
- [Spacy 101](https://spacy.io/usage/spacy-101)
- [AllenNLP Models](https://allennlp.org/models)

## Attendance and Participation
Students are responsible for attending course meetings and actively participating in course discussions. Students who arrive after class has begun, or who miss class entirely may miss quizzes and only the lowest grade may be dropped.

## Instructors

Marck Vaisman, Marck.Vaisman@georgetown.edu
Section 01, Walsh 390, Tues 6:30-9:00

Lisa Harper, Lisa.Harper@georgetown.edu
Section 02, Maguire 101, Tues 6:30-9:00
