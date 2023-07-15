# NLP_Sentiment_Analyzer_Model

To find out what makes a video game worth buying according to gamers, you need to get deeper insights into the linguistic features.The following tasks are evaluated -

1) Download the dataset of Amazon reviews - https://nijianmo.github.io/amazon/index.html
2) Create your own smaller dataset corpora from the Amazon reviews.
3) Decide whether people like or dislike the video game they bought and abel each game review with a sentiment score between -1 and 1.
4) Check the performance of your sentiment analyzer by comparing the sentiment scores with the review ratings.
5) Evaluate the performance of your sentiment analyzer and find out if you managed to correctly label the reviews.
6) Try out other methods of sentiment analysis. Explore how people evaluate the video game they purchased by classifying the reviews as positive, negative, and neutral.

Techniques and methods used -

* Sampling from imbalanced datasets using the imbalanced-learn package.
* Enquiring about the sentiment value of the reviews with the dictionary-based sentiment analysis tools, which are part of NLTK, a natural language processing toolkit, used in Python.
* Finding out if your algorithm did a good job. Data evaluation with scikit-learn in Python.
* Analyzing the reviews with a state-of-the-art deep learning technique, namely with the DistilBERT model. To build this model, you will need to run Pytorch, transformers, and the simpletransformers packages.
* Evaluating your model and creating descriptive statistics in Python with scikit-learn library before reporting your results to your boss.
* Visualizing findings about preferable and non-preferable words related to video games.

* The project is made up of five steps, which are built on each other:

1) Creating your dataset.
2) Creating a dictionary-based sentiment analyzer.
3) Evaluating your dictionary-based sentiment analyzer.
4) Creating neural network-based sentiment analyzers.
5) Reporting your results.
