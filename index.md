---
title: "ANYL 580 - NLP for Data Analytics"
layout: home
menuItem: "Basic info"
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
| 3-Sep-19 | Overview | How do data science and NLP relate? NLP tasks, What is a word? | [What is a word, what is a sentence?](https://pdfs.semanticscholar.org/e727/c7fd2bf3460a36934eae64c8c5716bc28980.pdf), [Contextual word representations: A contextual introduction](https://arxiv.org/pdf/1902.06006.pdf) | Survey in Canvas |
| 10-Sep-19 | Tools and environments | Linux, programming environments, GitHub, crawlers, regex, text extraction, NLP libraries, Elastic / Kibana, IDE's vs notebooks. | [J&M 2](https://web.stanford.edu/~jurafsky/slp3/2.pdf) | Q1 |
| 17-Sep-19 | What if documents are not in English? Multilingual computing. Guest Lecturer: Linda Moreau | Unicode, multilingual text processing, transliteration, language ID | [Spolsky](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/) | Q2 |
| 24-Sep-19 | How can we characterize documents using words? | Tokenization, stemming/lemmatization, normalization, string matching, regular expressions, information retrieval, spam filtering | [J&M 3](https://web.stanford.edu/~jurafsky/slp3/3.pdf) | Q3 |
| 1-Oct-19 | How can we classify documents? | Polarity, sentiment, framing, affect, illocutionary force, authorship, register, genre, style, profiling | [J&M 4](https://web.stanford.edu/~jurafsky/slp3/4.pdf), [J&M 5](https://web.stanford.edu/~jurafsky/slp3/5.pdf) | Q4 |
| 8-Oct-19 | How can we use neural networks to solve more complex NLP tasks? Guest Lecturer: Guido Zarrella | Distributed representations, Embeddings, Transfer learning, RNN, LSTM | [Visual Guide to the Basics of Neural Networks](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks/), [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/), [Deep Learning, NLP, and Representations](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/), [Understanding CNNs for NLP](http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/) | Q5, Project #1 Due |
| 15-Oct-19 | <No class> | Mid-Semester Break | | |
| 22-Oct-19 | How can we find similar documents or measure differences in text? | Vector semantics, word embeddings, lexical semantics, frames, distributional hypothesis | [J&M 6](https://web.stanford.edu/~jurafsky/slp3/6.pdf) | Q6 |
| 29-Oct-19 | How can we discover what documents are about? | Topic modeling, summarization | [Gensim tutorials](https://radimrehurek.com/gensim/tutorial.html), [xplore notebooks here](https://markroxor.github.io/gensim/tutorials/index.html), [Moody](https://multithreaded.stitchfix.com/blog/2017/10/18/stop-using-word2vec/) | Q7, Project #2 proposals due |
| 5-Nov-19 | How does Machine Translation work? | Statistical MT and neural MT - subtasks and challenges | [Visualizing a Neural MT Model](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/), [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) | Mid-Term |
| 12-Nov-19 | How can we extract information from text? | Part-of-speech tagging, ambiguity and context, information extraction, keywords, multi-word expressions | [J&M 8-8.3, 8.7](https://web.stanford.edu/~jurafsky/slp3/8.pdf), [J&M 17](https://web.stanford.edu/~jurafsky/slp3/17.pdf) [Spacy 101](https://spacy.io/usage/spacy-101) | Q8 |
| 29-Nov-19 | Can we use NLU to answer questions or populate knowledge bases? | Q&A, entity disambiguation, semantic relations, coherence/cohesion, graph/dependency relations, pragmatics, entity resolution | [The Illustrated BERT, ELMo, and co.](http://jalammar.github.io/illustrated-bert/), [Illustrated BERT](http://jalammar.github.io/illustrated-bert/), [Allen NLP Models](https://allennlp.org/models) | Q9 |
| 26-Nov-19 | How do chatbots work and why is dialogue so hard? | Grounding, dialog systems, text generation, inference | [J&M 24](https://web.stanford.edu/~jurafsky/slp3/24.pdf), Optional: [J&M 25](https://web.stanford.edu/~jurafsky/slp3/25.pdf) | Q10 |
| 3-Dec-19 | Science, Bias, and Ethics in NLP | Data and society, culture and bias,  Scientific method, representativeness, benchmarking and evaluation, debiasing| [Hovy & Spruit](http://www.dirkhovy.com/portfolio/papers/download/ethics.pdf) | Q11 |
| 10-Dec-19 | Student poster presentations | | | Project #2 Due |

## Grading Rubric

The emphasis for grading is on practical exercises and communicating results. There are two larger assignments that involve Python/R programming. These may be done in groups of 1-4 and assignments will be submitted via GitHub Classroom. Open book quizzes in class are focused on concepts from the reading, but may also be used to drive discussion.

## Readings

Primary readings are from chapters from Jurafsky & Martin (J&M), Speech and Language Processing v. 3, [https://web.stanford.edu/~jurafsky/slp3/](https://web.stanford.edu/~jurafsky/slp3/)

### Articles
- Hovy & Spruit, [The Social Impact of Natural Language Processing](http://www.dirkhovy.com/portfolio/papers/download/ethics.pdf)
- Chris Moody, [Stop Using word2vec](https://multithreaded.stitchfix.com/blog/2017/10/18/stop-using-word2vec/)
- Joel Spolsky, [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
- Jay Alammar, [Visual Guide to the Basics of Neural Networks](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks/)
- Christopher Olah, [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- WildML.com, [Understanding CNNs for NLP](http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/)
- Christopher Olah, [Deep Learning, NLP, and Representations](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/)
- Christopher Olah, [Visualizing a Neural MT Model](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/)
- Jay Alammar, [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- Jay Alammar, [The Illustrated BERT, ELMo, and co.](http://jalammar.github.io/illustrated-bert/) (http://jalammar.github.io/illustrated-bert/)

### API Guides / Documentation
- [Gensim website tutorials](https://radimrehurek.com/gensim/tutorial.html)
- [Gensim Tutorial notebooks](https://markroxor.github.io/gensim/tutorials/index.html)
- [Spacy 101](https://spacy.io/usage/spacy-101)
- [AllenNLP Models](https://allennlp.org/models)

## Attendance and Participation
Students are responsible for attending course meetings and actively participating in course discussions. Students who arrive after class has begun, or who miss class entirely may miss quizzes and only the lowest grade may be dropped.

## Instructors

Marck Vaisman, Marck.Vaisman@georgetown.edu
Section 01, Walsh 390, Tues 6:30-9:00

Lisa Harper, Lisa.Harper@georgetown.edu
Section 02, Maguire 101, Tues 6:30-9:00
