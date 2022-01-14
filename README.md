# NLP for sentiment analysis of tweets: demo of using the most popular libraries

In this notebook I will use three of the most popular libraries for sentiment analysis on text data.

I'll be using a <a href='https://www.kaggle.com/manchunhui/us-election-2020-tweets/code'>dataset of tweets</a>, collected for a period of three weeks around the 2020 US presidential elections.

I downloaded the dataset directly from the link above, but if you want to tackle another topic, you can open a <a href="https://developer.twitter.com/en/apply-for-access">Twitter developer account</a> and start collecting your own tweets using <a href="https://developer.twitter.com/en/docs/twitter-api/tweets/lookup/introduction">Tweet lookup</a> or <a href="https://github.com/JustAnotherArchivist/snscrape">snscrape</a>.<br/>

I start with some classic exploratory data analysis (to answer questions like how many tweets we have or what is the date range ?), I proceed to text pre-processing (text data has a lot of extra material like stop words and many words are not in the most useful form (e.g. plurals will be converted to singular etc), then I do sentiment analysis using three libraries (TextBlob, VADEDR and Flair) and compare the results to see which is the most suited for our dataset.

And because I am using data related to a political campaign, I want to see what actionable insights we can draw based on the sentiment analysis results. After all, the purpose of any Data Science analysis is to find out how to solve a problem. In this case, I'm part of the campaign management for one of the candidates and we use Twitter sentiment analysis to see how to increase our voter base. #This is a hypothetical problem; I am not actually involved in Politics and hope to never be.

<b>How to use it:</b><br/>
Open the Jupyter Notebook in this folder. You can clone it, download it or just read it here. There is also a link at the top of the Notebook which takes you to the same Notebook on Kaggle.

Contents of this Notebook:

    Exploratory Data Analysis
    Text pre-processing
    Intro to sentiment analysis
    Sentiment analysis with TextBlob
    Sentiment analysis with VADER
    Sentiment analysis with Flair
    Which is the best sentiment analysis library ?
    Actionable insights from sentiment analysis of tweets

