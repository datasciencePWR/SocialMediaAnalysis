# Assignment 3 (fully individual)
## User communities in Twitter controversies

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

1. (1 point) **Data.** Using appropriate python module acquire Twitter dataset pertaining to a controversy of choice, identified through a hastag (eg. covfefe, gamergate, alllivesmatter etc)

*Expected outcome:* a good quality raw dataset, with appropriate scope (see requirements in following tasks)

*Remark:* The dataset in question might be sizeable depending on the choice of a hashtag and a period of time. Consider running the scraping procedure in advance

2. (5 points) **Community Detection & Visualisation**:

  * Use the previously obtained data to construct a network of Twitter users participating in the discussion surrounding the controversy. Use user Mentions and/or Follows as the basis for creating edges within the network.

  * Perform a community detection on obtained network(s), using a selected method available ina Python module of choice.

  * Visualise the network(s) and communities obtained in the previous step. Note the size of communities and their placement within the network. What does the obtained structure tell you about controversy in question? 

*Expected outcome:* a set of readable network visualisations, interpretable with the respect to the community structure; thoughts and remarks inferred by the student based on the aforementioned visualisations 

*Remark 1:* depending on the module and its implementation of community detection and the size of your data, the process can take a lengthy amount of time. Consider that when allocating the time for your work.

*Remark 2:* while constructing two different network structures is not mandatory, reaching maximum points for tasks 2 and 3 is only possible if you do so.

3. (5 points) **Community Analysis** Prepare an analysis of the community structure(s) using previously obtained visualisation, full dataset acquired in task 1 and appropriate Python modules. Consider a scope of community traits applicable, like unique hashtags, geo-location similarity, general linguistic sentiment etc. If you've created two network structures as a part of your work on task 2, review the differences between community structures retrieved. Is one approach more intuitively realistic than another?

*Expected outcome:* a thorough analysis of the community structures and meaningful thoughts, inferences and conclusions drawn by the student 

**Please send individual** solution (code+figures, eg. notebook) to [sma.wust@gmail.com](sma.wust@gmail.com) before next classes take place, evaluation during classes.

### Readings
[Pandas tutorial](https://github.com/jorisvandenbossche/pandas-tutorial)

[NetworkX](https://networkx.github.io/documentation/stable/)

### Code samples 
as in examples in  readings
