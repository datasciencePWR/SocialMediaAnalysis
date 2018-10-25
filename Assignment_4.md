# Assignment 4 
## Analysis of users emotions in texts

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

1. (4 points) **Data Representation**

A. Download following dataset: [Download Link](https://github.com/bfelbo/DeepMoji/raw/master/data/PsychExp/raw.pickle) and use 80%/20% train/test split.   
Labels are arranged in the following way: [joy, fear, anger, sadness, disgust, shame, guilt]  

B. Build a representation of words using pre-trained word vectors, e.g. Word2Vec, GloVe or learn randomly initialised embeddings using an appropriate layer in a deep learning framework  

C. Build a sentence representation: Average word-vectors in a sentence or use flattened sequence representation (requires padding as sentences have a varying length)
*Expected outcome:* Representation of sentences that can be used to feed the neural network 

*Remark*: Learning embedding, even as a layer in a network, may be time-consuming

2. (4 points) **Classifier building**. Build an MLP network using any deep learning framework, eg. Keras, Tensorflow, PyTorch to classify sentences

*Expected outcome:* Neural Network Model that can predict Emotions based on the text. 

*Remark:* You can use the architecture that you prepared for Assignment 1 of Deep Learning Course. 

3. (3 points) **Validation**. Validate the trained model using data acquired from social media, e.g. Twitter and analyse obtained predictions

*Expected outcome:* Comprehensive analysis of predictions for acquired data

**Please send individual** solution (code+figures, eg. notebook) to [sma.wust@gmail.com](sma.wust@gmail.com) before next classes take place, evaluation during classes.

### Readings
[Embeddings](https://www.tensorflow.org/guide/embedding)  
[Keras Examples](https://github.com/keras-team/keras/tree/master/examples)  
[TensorFlow Examples](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples)  
[PyTorch Examples](https://github.com/pytorch/examples)

### Sources
[Glove Vectors](https://nlp.stanford.edu/projects/glove/)  
[Word2Vec](https://code.google.com/archive/p/word2vec/)  
