# TextClassificationLSTMTensorFlow

Let us look at how we can implement text classification with Tensorflow https://www.tensorflow.org/ 

TensorFlow is an end-to-end open source platform for machine learning.

The dataset is from Amazon Review Data (2018) https://nijianmo.github.io/amazon/index.html.

I here look at Cell Phones and Accessories review dataset from "Small" subsets for experimentation. I have pre-processed this dataset. 

The script for pre-processing is present here: https://github.com/rsreetech/TextClassificationLSTMTensorFlow/blob/master/AmazonReviewsPreprocessing.ipynb


Let us perform sentiment classification by considering reviews which have rating 3(3,4,5) and above as having positive sentiment and reviews having ratings below 3(1,2) as negative sentiment. 

Let us develop a LSTM based classfication model for sentiment classification on review data.

Pre-requisites:

Python 3.6

Pandas https://pandas.pydata.org/

Matplotlib https://matplotlib.org/

wordcloud https://pypi.org/project/wordcloud/

seaborn https://seaborn.pydata.org/

Tensorflow GPU 2.1

Pydot

