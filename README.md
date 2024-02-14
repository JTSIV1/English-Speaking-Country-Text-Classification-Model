# English Speaking Country Text Classification Model

### Data
Data used to train the model was Twitter_by_Country data provided by professor Jonathan Dunn. It was too large to include in this repo. Tripadvisor review data is from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews) and is included in the repo in addition to the newly country-labeled datasets.  

### Usage
The process of creating and using the model is split up into two files ``Project1_createModel.ipynb`` and ``Project1_useModel.ipynb``. Each Jupyter notebook walks through the process of training a model and then using the pretrained model on new data. The pretrained models have been python pickled and are in ``unigram_tweet_classification_model.p``, ``bigram_tweet_classification_model.p``, and ``trigram_tweet_classification_model.p``. To use them, see the code in the ``Project1_useModel.ipynb`` notebook.  

### Results
Results from testing data on the N-gram models are provided in ``unigram_tweet_classification_results.txt``, ``bigram_tweet_classification_results.txt``, and ``trigram_tweet_classification_results.txt``.
