# Twitter-sentiment-analysis

This is a web app integrated with twitter which takes the twitter handel as as input and does :

Web Link: https://share.streamlit.io/srivari07/twitter-sentiment-analysis/main/app.py

1.Analyze the tweets of your favourite Personalities

This tool performs the following tasks :
1. Fetches the 5 most recent tweets from the given twitter handel
2. Performs Sentiment Analysis a displays it in form of a Bar Graph

2.This tool fetches the last 100 tweets from the twitter handel & Performs the following tasks
Converts it into a DataFrame

Cleans the text
1. Analyzes Subjectivity of tweets and adds an additional column for it
2. Analyzes Polarity of tweets and adds an additional column for it
3. Analyzes Sentiments of tweets and adds an additional column for it

![image](https://user-images.githubusercontent.com/69836058/173535719-bf29d1b4-1e30-4055-a429-09b95db1b7ee.png)

![image](https://user-images.githubusercontent.com/69836058/173536105-b182c37e-30b7-4817-843f-d44ce3a9045f.png)


This respository contains all the files for end to end model building and deployment of tweet analyzer web app

Tweet_Analyzer.ipynb : Model building File

Requirements.txt: Requirement file

This app is created on a tool called Streamlit which saves you from the headache of front-end devlopment ,you can install it by:
Streamlit documentation: https://docs.streamlit.io/en/latest/

pip install streamlit

& to run it on local host : streamlit run app.py
