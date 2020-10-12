# Assessing-State-of-the-Art-Sentiment-Models-on-State-of-the-Art-Sentiment-Datasets

----------
# Abstract

> It is hard to understand how well a certain model generalizes across different tasks and datasets. 
In this paper, we contribute to this situation by comparing several models on six different benchmarks, which belong to different domains and additionally have different levels of granularity (binary, 3-class, 4-class and 5-class). 
We show that Bi- LSTMs perform well across datasets and that both LSTMs and Bi-LSTMs are particularly good at fine-grained sentiment tasks (i. e., with more than two classes). 
Incorporating sentiment information into word embeddings during training gives good results for datasets that are lexically similar to the training data. 
With our experiments, we contribute to a better understanding of the performance of different model architectures on different data sets. 
Consequently, we detect novel state-of-the-art results on the SenTube datasets.

----------

# Datasets
![Figure 1](https://github.com/subasish/PaperNotes/tree/main/paper_notes/images/001.png)


 - The Stanford Sentiment Treebank (SST-fine) is a dataset of movie reviews.

> In order to compare with [[Faruqui et al. (2015)]](http://www.aclweb.org/anthology/N15-1184), we also adapt the dataset to the task of binary sentiment analysis, where strong negative and negative are mapped to one label, and strong positive and positive are mapped to another label, and the neutral examples are dropped. This leads to a slightly different split of 6920/872/1821 (we refer to this dataset as SST- binary).

 - The OpeNER dataset is a dataset of hotel reviews in which each review is annotated for opinions. 
 - The SenTube datasets are texts that are taken from YouTube comments regarding automobiles (SenTube-A) and tablets (SenTube-T).
 - The SemEval 2013 Twitter dataset (SemEval) is a dataset that contains tweets collected for the 2013 SemEval shared task B.

![Figure 2](https://github.com/Eurus-Holmes/Research_Papers/raw/master/paper_notes/Assessing-State-of-the-Art-Sentiment-Models-on-State-of-the-Art-Sentiment-Datasets/images/2.png)

