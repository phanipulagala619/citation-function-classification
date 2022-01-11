
# Deep Learning for Citation Function Analysis

This repository explains how to implement Citation function Analysis using deep learning. The deep learning models used are Bi-LSTM and Bi-LSTM + Attention



## Objective
The purpose of the research is to create an automatic citation function classifier. Our model should be able to categorise citation context into one of the citation functions given a citation context or citation sentence


## Motivation

When dealing with citation function analysis, previous authors have sent the entire citation sentence output of a deep learning algorithm such as CNN or Bi-LSTM to the final Softmax layer to predict, but I believe and object that this is the wrong way to perform citation function classification because one citation sentence can contain many citations, so we need to classify each citation into a specific function. To overcome this problem, we need to send the CITSEG vector (Citation string) to categorise instead of the whole citation sentence generated by algorithms like CNN or BI-LSTM. This is how citation function categorization should be done correctly. To correct the previous research authors' mistake of sending the entire citation sentence to the Softmax layer, as well as the disadvantages of machine learning algorithms such as the time spent creating manual features and the results of previous deep learning algorithms that are not promising and standard, these drawbacks motivated me to conduct this research using a large-scale benchmark dataset and advanced deep learning algorithm.
## Bi-LSTM Architecture

![Bi-LSTM](https://github.com/phanipulagala619/citation-function-classification/blob/main/bilstm%20architecture.PNG)

  
## Bi-lSTM Architectute of our problem

## Acknowledgements

 - [Automatic classification of citation function](https://dl.acm.org/doi/10.5555/1610075.1610091)
 - [Citation Analysis using Neural Attention Models](https://aclanthology.org/W16-6109/)
 - [Investigating Convolutional Networks and Domain Specific Embeddings for Semantic Classification of Citations](http://madoc.bib.uni-mannheim.de/42818/1/WOSP_2017_paper_7%20%289%29.pdf)
 - [Multi-task learning model based on recurrent convolutional neural networks for citation sentiment and purpose classification](https://www.semanticscholar.org/paper/Multi-task-learning-model-based-on-recurrent-neural-Yousif-Niu/79ce56d98921073f2310cd57d1c6a4126b79f7a7)
  
