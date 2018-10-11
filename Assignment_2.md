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

1. (1 point) **Data.** Using appropriate python module acquire Twitter dataset about Wroclaw presidential candidates activity on Twitter. Please condider these candidates that have been discovered by teaching team 
```python
['RozeckaPL', 'GoTracz', 'martalempart', 'MichalakJerzy', 'KatarzynaObara', 'SutrykJacek']
```
This is not the full list of candidates, 3 more of them seems to be absent on Twitter.

*Expected outcome:*  good quality raw dataset, with appropriate scope (see requirements in following tasks) for all candidates

2. (3 points) **Analysis & Visualization**:

A. show number of tweets in time (x axis) for candidates using any line plot; show number of re-tweets in time (x axis) for candidates using any line plot

B. show popularity of tweets in time (number of likes, number of retweets) - likes assigned with tweets original date

C. show distribution of activity for hour of day and day of week for tweeting and retweeting activities (both)

*Expected outcome:*  set of good quality visualization, easy to interpret, with appropriate axis description 

3. (3 points) **Sentiment analysis.** Using apropriate python module show visualization of tweet sentiment (average) in time for all candidates. This is simple evaluation of sentiment, no entities (aspects) must be considered. Provide your explanation and objective interpretation.

*Expected outcome:* good quality visualization of sentiment distribution for all candidates

**Please send individual** solution (code+figures, eg. notebook) to [sma.wust@gmail.com](sma.wust@gmail.com) before next classes take place, evaluation during classes.

### Readings
[Pandas tutorial](https://github.com/jorisvandenbossche/pandas-tutorial)

[Polyglot](https://polyglot.readthedocs.io/en/latest/)

[Seaborn](https://seaborn.pydata.org/)


### Code samples 
as in examples in  readings
