# NLP Tutorial
A list of NLP(Natural Language Processing) tutorials built on PyTorch and Keras.
<br><br>
<p align="center">
<img width="400" src="https://raw.githubusercontent.com/pytorch/pytorch/master/docs/source/_static/img/pytorch-logo-dark.png"  align="middle">
<img width="320" src="https://s3.amazonaws.com/keras.io/img/keras-logo-2018-large-1200.png" align="middle">
</p>

## Table of Contents
A step-by-step tutorial on how to implement and adapt to the simple real-word NLP task.

- [Neural Machine Translation](https://github.com/lyeoni/nlp-tutorial/tree/master/neural-machine-translation): This repo provides a simple PyTorch implementation of Neural Machine Translation, along with an intrinsic/extrinsic comparison of various sequence-to-sequence (seq2seq) models in translation.
<br>**_Keyword_:** sequence to seqeunce network(seq2seq), Attention, Auto-regressive, Teacher-forcing

- [Question-Answer Matching](https://github.com/lyeoni/nlp-tutorial/tree/master/question-answer-matching): This repo provides a simple PyTorch implementation of Question-Answer matching. Here we use the corpus from _Stack Exchange_ in English to build embeddings for entire questions. Using those embeddings, we find similar questions for a given question, and show the corresponding answers to those I found.
<br>**_Keyword_:** TF-IDF, LSTM with variable-length seqeucnes, CBoW, Text classification

- [News Category Classification](https://github.com/lyeoni/nlp-tutorial/tree/master/news-category-classifcation): This repo contains a simple source code for text-classification based on TextCNN. Corpus is _Huffpost_ news category dataset in English. Most open sources are a bit difficult to study & make text-classification model for beginners. So, I hope that this repo can be a good solution for people who want to have their own text-classification model.
<br>**_Keyword_:** TextCNN, Text classification, Text cateogrization

- [Movie Rating Classification (Korean NLP)](https://github.com/lyeoni/nlp-tutorial/tree/master/movie-rating-classification): This repo contains a simple source code for text-classification based on TextCNN. Corpus is _movie review_ dataset in the Korean language. Most open sources are a bit difficult to study & make text-classification model for beginners. So, I hope that this repo can be a good solution for people who want to have their own text-classification model.
<br>**_Keyword_:** TextCNN, Text classification, Sentiment analysis

- [Question Answering for SQuAD](https://github.com/lyeoni/nlp-tutorial/tree/master/question-answering-SQuAD) (working)

##一份覆盖全面的基于 PyTorch 和 keras 的 NLP 学习教程
这是一份基于 PyTorch 和 keras 的 NLP 学习教程。这份教程内容相当丰富，内容涵盖神经网络机器翻译、问答匹配、电影评价分类、新闻分类等多个领域。
项目里面有 4 个资源：神经机器翻译、问答匹配、新闻分类和电影分级。这些资源都提供了源码，对初学者来说，极为友好。初学者可以学会建立自己的模型。

废话就不多说了，让我们一起来具体看看这些资源吧~

神经机器翻译：这个 repo 提供了神经机器翻译的简单 PyTorch 实现，以及机器翻译过程中各种序列到序列（seq2seq）模型的比较。

关键词：序列到序列网络（seq2seq），注意机制，自回归，Teacher-forcing

问答匹配：这个 repo 提供了简单的 PyTorch 问答匹配实现。在这里，我们使用来自 Stack Exchange 的英语语料库来构建整个问题的嵌入。使用这些嵌入，我们找到给定问题的类似问题，并找到相应的答案。

关键词： 长度可变的 LSTM 序列，TF-IDF，文本分类

新闻分类：此报告包含一个简单的源代码，用于基于 textcn 的文本分类。语料库是英文的赫夫波斯特新闻分类数据集。大多数开放源代码对于初学者来说有点难以学习和建立文本分类模型。所以，我希望这个 repo 对于那些想要拥有自己的文本分类模型的人来说是一个很好的解决方案。

关键词：textcn，文本分类，文本分类

电影分级（韩国 NLP）：此 repo 包含一个简单的源代码，用于基于 TextCNN 的文本分类任务中。其语料库是 Huffpost 的新闻分类数据集。对初学者来说，学习大多数开放源代码、建立文本分类模型是有难度的。所以，我希望这个 repo 可以帮助他们拥有自己的文本分类模型。

关键词：TextCNN、文本分类、情感分析

