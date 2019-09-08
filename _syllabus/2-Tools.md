---
week: 2
day: September 10
title: Tools
tags: [environments, tokenization]
---

## Access the Lecture

- [2-Tools (view only)](https://github.com/anyl580/lectures/blob/master/2-tools/2-tools.md)

- [2-Tools (interactive)](https://mybinder.org/v2/gh/anyl580/lectures/master?urlpath=notebooks/2-tools/2-tools.ipynb)

## Readings

- [Jurafsky & Martin 3rd ed. Chapter 2](https://web.stanford.edu/~jurafsky/slp3/2.pdf)

- [J&M 2nd ed. Video Playlist](https://www.youtube.com/playlist?list=PLQiyVNMpDLKnZYBTUOlSI9mi9wAErFtFm)

## Sidebar Notes

For the first couple of weeks, we're trying to move relatively slowly by focusing on  string processing tasks such as tokenization while you are learning to use other tools. The primary tools that you need for this class are Python or R and various libraries/packages plus GitHub.

## Other References

- Natural Language Tool Kit (NLTK) [Chapter 2 and the Brown Corpus (1.3)](https://www.nltk.org/book/ch02.html)

- Natural Language Tool Kit (NLTK) [Chapter 3 and the Brown Corpus (1.3)](https://www.nltk.org/book/ch03.html)

- [ANYL580 Linux tutorials](https://georgetown.instructure.com/files/2884569/download?download_frd=1)

- [ANYL580 Regular Expressions Tutorial](https://georgetown.instructure.com/files/2884565/download?download_frd=1)

- [The First Notebook War](https://yihui.name/en/2018/09/notebook-war/) - Great article by Yihui Xie, 2018-09-10

- ["State-of-the-art" Multilingual Lemmatization ](https://towardsdatascience.com/state-of-the-art-multilingual-lemmatization-f303e8ff1a8) - Good overview article and also referencing benchmark evaluations in [CoNLL 2017](http://universaldependencies.org/conll17/) and [CoNLL 2018](http://universaldependencies.org/conll18/) shared tasks. There is now some annotated data for over 50 languages. There are concepts mentioned that we have not yet talked about in this class -- but we will get there.
-
- Article on ["Toward Tokenization Evaluation"](https://perso.limsi.fr/madda/publications/PDF/habert-et-al98b.pdf). We mentioned that there is no standard for tokenization given that there are no linguistic grounds for this task. This article discusses comparative assessment and also the consequences of divergent tokenization choices.

## Exercises

- If you are relatively new to Python and GitHub, use the links below to download and install Anaconda and GitHub Desktop. We'll walk through cloning the repository to your laptop.
- If you are a second year student, you should be able to do the same thing in the cloud.
- If you prefer to use R, we'll have an option for you as well!

1. If you are unfamiliar with **Linux**, walk through the [Linux Exercises from the PDF in Canvas]().
2. In particular, try out the Linux commands from Jurafsky section 2.4 on [ca11.txt](https://github.com/anyl580/lectures/tree/master/2-tools/ca11.txt). These manual pages should help you to better understand use of the commands exemplified.
	- [tr](https://www.geeksforgeeks.org/tr-command-in-unix-linux-with-examples/)
	- [grep](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)
	- [SORT](https://www.geeksforgeeks.org/sort-command-linuxunix-examples/)
	- [uniq](https://www.geeksforgeeks.org/uniq-command-in-linux-with-examples/)
4. Use [RegExr: Learn, Build, & Test RegEx](https://regexr.com/) to practice regular expressions by **removing tags** from [ca11.txt](https://github.com/anyl580/lectures/tree/master/2-tools/ca11.txt) (one of the texts from the Brown Corpus). The Brown corpus manual [Brown Corpus Manual](http://clu.uni.no/icame/manuals/BROWN/INDEX.HTM#bc6) should be of help.
5. Consider the statistics below required for [Project #1](https://anyl580.github.io/project1.html). Try to do these for either [ca11.txt](https://github.com/anyl580/lectures/tree/master/2-tools/ca11.txt) or the Brown Corpus within NLTK. If you are using NLTK, you can use the [course lecture for this](https://github.com/anyl580/lectures/tree/master/2-tools).
     - Statistics you should gather:
         - The total number of tokens
         - The total number of characters
         - The total number of distinct words (vocabulary)
         - The total number of tokens corresponding to the top 10 most frequent words in the vocabulary
         - The total number of tokens corresponding to the bottom 10 most infrequent words in the vocabulary
         - The token/type ratio in the dataset
         - Make a plot of the Brown Corpus. [Heaps' law - Wikipedia](https://en.wikipedia.org/wiki/Heaps'_law)). We'll be talking more about Zipf's law next week.

### Tools

* **[GitHub](https://github.com)** - GitHub also has excellent tutorials: [GitHub Guides](https://guides.github.com), [video tutorials](https://www.youtube.com/playlist?list=PL0lo9MOBetEHhfG9vJzVCTiDYcbhAiEqL), [hands-on learning lab](https://lab.github.com).
* **[Markdown](https://markdown-it.github.io)** - A great editor is [GitHub's Atom](https://atom.io). I use this for editing lecture materials.
* **[GitHub Desktop](https://desktop.github.com) - is a really straightforward git **
* **[Anaconda](https://www.anaconda.com/distribution/)** - hands-down the easiest environment to get started with and use. That said, if you prefer R, go straight to RStudio.
* **[Jupyter](https://jupyter.org)** - You will get this with Anaconda, but read a bit more about it here. I use a couple of extensions that are useful: [Jupytext](https://jupytext.readthedocs.io/en/latest/) can be used for live synchronization of a Jupyter file with a Python file, and [RISE](https://rise.readthedocs.io) is nice for slides, and [nbextensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/) for a few small niceties.
* **[PyCharm](https://www.jetbrains.com/pycharm/)** - free education license and a seriously great environment many use in the workplace.
* **[KITE](https://kite.com)** - Slick code-completion tool that runs alongside several different Python IDEs.
* **[RStudio](https://www.rstudio.com/products/rstudio/)** - One can only hope that Jupyter will catch up some day. This is just a great data environment, period.
* **[Elastic (ELK) Stack](https://www.elastic.co/products/elastic-stack)** - Many data scientists use Elastic to quickly index data for further exploration and for quick-and-dirty dashboards.
* **[Docker](https://www.docker.com/products/docker-hub)** - use this platform-as-a-service to create a re-usable environment that you can spin up in minutes.
* **[Google Colaboratory](https://colab.research.google.com)** - free Jupyter notebooks with free GPU use and linked to your Google Drive, **[GCP](https://cloud.google.com)** - Google gives you a $300 credit when you sign up for its Google Cloud Platform, **[Azure](https://azure.microsoft.com/)** - Microsoft will give you a $200 credit for Azure, **[AWS](https://aws.amazon.com)** - Amazon will give you access to a free (lightweight) tier of virtual machines for a year. I have accounts on all three and wouldn't go so far to say that one was much easier than another.
* **[Digital Ocean](https://www.digitalocean.com)** (great alternative to cloud but no GPUs) - At $5 per month for a virtual machine you never have to turn off, this is an environment that is hard to beat. I use Docker on Digital Ocean for every day use.
* Other easy **[options for Jupyter notebooks with GPUs](https://course.fast.ai)** - fastai points to some 1-click installations of Jupyter that are super easy to setup and use. If you really don't want to bother with cloud yet, there are some great options here.
* **[Scrapy](https://scrapy.org)** - Scrapy is a super easy to learn and use webscraping library. I haven't tried Scrapy cloud yet but it looks intriguing. Check out []"Scraping Amazon Reviews using Scrapy in Python."](https://blog.datahut.co/scraping-amazon-reviews-python-scrapy/) We didn't have time to do this as an exercise, but you could scrape your own data for project #2.

## Language Tools

* **[https://regexr.com](https://regexr.com
)** - Use regexpr to test your regular expressions before inserting them into your code! It's also a great tool for building your skills since it has detailed online documentation alongside the code environment.
* **Arabic Morphological Analyzer** - [This paper](https://www.aclweb.org/anthology/W18-5816) compares the performance of several Arabic analyzers. The GitHub repo can be found [here](https://github.com/CAMeL-Lab/camel_tools) and a [demo (Calima-Star) is linked here](https://nyuad.nyu.edu/en/research/centers-labs-and-projects/computational-approaches-to-modeling-language-lab/resources.html).
* **[Chinese segmentation](https://paperswithcode.com/task/chinese-word-segmentation)** - Current State-of-the-Art for Chinese segmentation is a neural model with pre-trained bigram embeddings. I didn't locate the code repo, so if you spot it, please do a GitHub pull request so we can edit this page.
* **[StanfordNLP](https://stanfordnlp.github.io/)** - In his chapter, Jurafsky mentions the Stanford CoreNLP. More recently, Stanford has a Python NLP package that supports [tokenization and other pipeline processing](https://stanfordnlp.github.io/stanfordnlp/processors.html).
* **[SpaCy Tokenizer](https://spacy.io/api/tokenizer/)** - While we've been exploring [NLTK's tokenizer package](https://www.nltk.org/api/nltk.tokenize.html) and [source code](https://www.nltk.org/_modules/nltk/tokenize/treebank.html#TreebankWordTokenizer), spaCy also has flexible capabilities in this area.
