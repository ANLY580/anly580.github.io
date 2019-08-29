# Project #1: Sentiment Analysis

For this project, you will focus on the task of sentiment analysis of English Twitter data.

### Task Description

You have three basic tasks:
1. Exploratory data analysis
2. Message polarity classification - given a message, classify whether it is positive, negative, or neutral sentiment
3. Performance evaluation of your classifier

One of the more difficult challenges for NLP in practice is evaluating performance. Fortunately, the larger research community puts significant effort into the development of data for training, development, and testing.

You will be provided three data sets (train, dev, test) for development and testing.

### Competition

To make this project more interesting and challenging, you will compete with one another in a leaderboard for highest score. We'll also award teams for best report and have you all vote on most innovative or interesting.

### Data

For this project, you will use provided training, development, and test data from GitHub Classroom and also located in Canvas.

### Task 1: Exploratory Data analysis (5 points)

You will do exploratory data analysis to first summarize statistical and other characteristics of your data.

The most basic statistics on corpora are simply **observed absolute frequencies** (Gries, 2010).

Combine your training and development set for calculating statistics below.

- The total number of tokens
- The total number of characters
- The total number of distinct words (vocabulary)
- The total number of tokens corresponding to the top 10 most frequent words in the vocabulary
- The token/type ratio in the dataset
- The number of types that appear in the dev data but not the training data (if you are using Python, use sets)
- The average number and standard deviation of characters per token
- The total number of distinct n-grams (of words) that appear in the dataset for n=2,3,4,5.
- The total number of distinct n-grams of characters that appear for n=2,3,4,5,6,7
- Plot a log frequency. Describe what this plot means and how to interpret it. Describe out it might help you understand coverage when training a model?
- What words are particularly characteristic of your training set and dev set?
- Are they the same?

### Task 2: Message Polarity (10 points)

Sentiment analysis is another tool useful in exploratory data analysis for quantifying the emotional valence of messages. In combination with other methods such as topic analysis and social network analysis, it may provide emotional context around topics of discussion.Build and compare three or more classifiers that predict a tweet is positive, negative, or neutral in sentiment. This is a single label, multi-class classification task where each tweet is classified as belonging to exactly one of these three classes.

Use only methods described in J&M chapters 2, 3, 4, and 5 (for example, using sklearn and to include lexicon-based classifiers such as Vader). Effectively, this means you should not yet do topic analysis or other methods yet to be discussed in the syllabus such as neural networks. If in doubt, please ask. We'll have a later exercise with this same dataset where you will do topic analysis.

- You are encouraged to experiment with different approaches for cleaning and pre-processing your data (e.g., stemming/lemmatization, cleaning with regexes, etc.).
- Feel free to use any sentiment lexicons you use or create.
- You may add additional data sets to those provided (except for the test data set).
- Describe your implementation decisions in commented code.
- If you extracted any features, list these.

### Task 3: Performance evaluation (5 points)

The primary metric for evaluating algorithm performance for this task is AvgRec, or average recall; this is recall averaged across the POSITIVE (P), NEGATIVE (N), and NEUTRAL (U) classes. Your starter script will include a function for evaluating performance.
- Create a results table that compares performance of the algorithms you chose for analysis.
- Look at your results and find examples where your classifiers have mis-performed. What sorts of phenomena do you see and speculate on why you see these errors.
- Are there distinct differences between classifiers or are differences difficult to see from your results?
- If you had more time, what might you do differently?
- What questions do you know have about your analysis that you didn't have before starting?
