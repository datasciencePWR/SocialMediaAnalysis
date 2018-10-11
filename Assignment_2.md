# Assignment 2 (fully individual)
## Participation of Wroclaw presidential candidates on Twitter

### Scope: knowledge and skils
* understanding Twitter data
* Twitter data acquisition
* basic textual analysis
* time series visualization 
* Jupiter ipython notebooks (or Jupiter Lab)
* python:  
	* data organization: pandas
	* graphs: networkx, igpraph
	* visualization: matplotlib, seaborn, bokeh, ggplot, wordcloud, folium
	* machine learning: sckikit-learn, xgboost
	* NLP: gensim, spaCy, tweet2vec, polyglot 
	* statistics, algebra: numpy, scipy
	* scrapping: newspaper, portia, pyspider, scrapy, twint
	* summarization: sumy
	* awesome-2vec
* teamwork

### Tasks

1. (1 point) **Data.** Using appropriate python module acquire Twitter dataset about Wroclaw presidential candidate activity on Twitter. Please consider the following candidates that have been discovered by teaching team: 
```python
['RozeckaPL', 'GoTracz', 'martalempart', 'MichalakJerzy', 'KatarzynaObara', 'SutrykJacek']
```
This is not the full list of candidates, 3 more of them seem to be absent from Twitter.

*Expected outcome:* a good quality raw dataset, with appropriate scope (see requirements in following tasks) for all candidates

2. (3 points) **Analysis & Visualization**:

A. Show the number of tweets in time (x axis) for candidates using any line plot; show the number of re-tweets in time (x axis) for candidates using any line plot

B. Show the popularity of tweets in time (number of likes, number of retweets) - likes assigned to tweet's publication date

C. Show the distribution of activity in the scope of a day (on an hourly basis) and week (on a daily basis) for tweeting and retweeting activities (both)

*Expected outcome:* a set of good quality visualization, easy to interpret, with appropriate axis description 

3. (3 points) **Sentiment analysis.** Using appropriate python module show visualization of tweet sentiment (average) in time for all candidates. This is a simple evaluation of sentiment, no need to consider entities (aspects). Provide your explanation and objective interpretation.

*Expected outcome:* a good quality visualization of sentiment distribution for all candidates

**Please send individual** solution (code+figures, eg. notebook) to [sma.wust@gmail.com](sma.wust@gmail.com) before next classes take place, evaluation during classes.

### Readings
[Pandas tutorial](https://github.com/jorisvandenbossche/pandas-tutorial)

[Polyglot](https://polyglot.readthedocs.io/en/latest/)

[Seaborn](https://seaborn.pydata.org/)


### Code samples 
as in examples in  readings
