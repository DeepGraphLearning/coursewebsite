---
layout: page
title: Schedule
permalink: /schedule
nav_order: 1
schedule:
  - date: 1 / 9, 10
    topics:
    - name: Introduction
      url: https://www.dropbox.com/s/wrx8k00rxz2txr2/Week1-Intro.pdf?dl=0
    - name: Mathematics
      url: https://www.dropbox.com/s/qnl3wqws3hehf5l/Week1-Maths.pdf?dl=0
    - name: Machine Learning Basics
      url: https://www.dropbox.com/s/3l5nqiwzcanzlqq/Week1-ML.pdf?dl=0
    readings:
      - name: Deep Learning Book
      - name: Chap. 2
        url: http://www.deeplearningbook.org/contents/linear_algebra.html
      - name: Chap. 3
        url: http://www.deeplearningbook.org/contents/prob.html
      - name: Chap. 5
        url: http://www.deeplearningbook.org/contents/ml.html
  - date: 1 / 16, 17
    topics:
    - name: Feedforward Neural Networks & Optimization Tricks
      url: https://www.dropbox.com/s/jg9o0edpu29jgc8/Week2-FFN%26Regularization.pdf?dl=0
    readings:
      - name: Deep Learning Book
      - name: Chap. 6
        url: http://www.deeplearningbook.org/contents/mlp.html
      - name: Chap. 7
        url: http://www.deeplearningbook.org/contents/regularization.html
      - name: Chap. 8
        url: http://www.deeplearningbook.org/contents/optimization.html
  - date: 1 / 23, 24
    topics: PyTorch
    readings:
      - name: Python Numpy Tutorial
        url: http://cs231n.github.io/python-numpy-tutorial/
      - name: Neural Network from Scratch
        url: https://medium.com/dair-ai/a-simple-neural-network-from-scratch-with-pytorch-and-google-colab-c7f3830618e0
      - name: Dive into Deep Learning
        url: https://github.com/dsgiitr/d2l-pytorch
  - date: 1 / 30, 31
    topics: Convolutional Neural Networks & Recurrent Neural Networks
    readings:
      - name: Deep Learning Book
      - name: Chap. 9
        url: http://www.deeplearningbook.org/contents/convnets.html
      - name: Chap. 10
        url: http://www.deeplearningbook.org/contents/rnn.html
    homework:
      name: Homework 1
      url:
    presentations:
      - name: ResNet
        url: http://arxiv.org/abs/1512.03385
      - name: GRU
        url: https://arxiv.org/abs/1412.3555
      - name: DenseNet
        url: https://arxiv.org/abs/1608.06993
  - date: 2 / 6, 7
    topics: Natural Language Processing I
    readings:
      - name: Word2Vec
        url: https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf
      - name: CNN for sentence classification
        url: https://arxiv.org/abs/1408.5882
      - name: Seq2Seq
        url: https://arxiv.org/abs/1409.3215
    presentations:
      - name: GloVe
        url: https://www.aclweb.org/anthology/D14-1162.pdf
      - name: Tree LSTM
        url: https://arxiv.org/abs/1503.00075
      - name: CNN Multi-task Learning
        url: https://ronan.collobert.com/pub/matos/2008_nlp_icml.pdf
  - date: 2 / 13, 14
    topics: Natural Language Processing II
    readings:
      - name: Attention Seq2Seq
        url: https://arxiv.org/abs/1409.0473
      - name: Transformer
        url: https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf
      - name: BERT
        url: https://arxiv.org/abs/1810.04805
    presentations:
      - name: Memory Networks
        url: https://arxiv.org/abs/1503.08895
      - name: SQuAD Dataset
        url: https://arxiv.org/abs/1606.05250
      - name: GLUE Benchmark
        url: https://arxiv.org/abs/1804.07461
    homework:
      name: Homework 2
      url:
  - date: 2 / 20, 21
    topics: Q & A for Projects
  - date: 2 / 27, 28
    topics: <b><i>No class</i></b>
  - date: 3 / 5, 6
    topics: Graph Representation Learning I
    readings:
      - name: DeepWalk
        url: https://arxiv.org/abs/1403.6652
      - name: LINE
        url: https://arxiv.org/abs/1503.03578
    presentations:
      - name: Node2Vec
        url: https://arxiv.org/abs/1607.00653
      - name: Metapath2Vec
        url: https://ericdongyx.github.io/papers/KDD17-dong-chawla-swami-metapath2vec.pdf
      - name: LargeVis
        url: https://arxiv.org/abs/1602.00370
  - date: 3 / 12, 13
    topics: Graph Representation Learning II
    readings:
      - name: RESCAL
        url: http://www.cip.ifi.lmu.de/~nickel/data/slides-icml2011.pdf
      - name: TransE
        url: http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data.pdf
      - name: DistMult
        url: https://arxiv.org/abs/1412.6575
    presentations:
      - name: ComplEx
        url: https://arxiv.org/abs/1606.06357
      - name: ConvE
        url: https://arxiv.org/abs/1707.01476
      - name: RotatE
        url: https://arxiv.org/abs/1902.10197
  - date: 3 / 19, 20
    topics: Graph Representation Learning III
    readings:
      - name: Graph Convolutional Networks
        url: https://arxiv.org/abs/1609.02907
      - name: Graph Attention Networks
        url: https://arxiv.org/abs/1710.10903
      - name: Neural Message Passing
        url: https://arxiv.org/abs/1704.01212
    presentations:
      - name: GraphSAGE
        url: https://arxiv.org/abs/1706.02216
      - name: PinSAGE
        url: https://arxiv.org/abs/1806.01973
      - name: HAN
        url: https://arxiv.org/abs/1903.07293
    homework:
      name: Homework 3
      url: 
  - date: 3 / 26, 27
    topics: Recommender Systems
    readings:
      - name: Bayesian Personalized Ranking
        url: https://arxiv.org/abs/1205.2618
      - name: Factorization Machines
        url: https://www.csie.ntu.edu.tw/~b97053/paper/Rendle2010FM.pdf
      - name: RNN-based recommendations
        url: https://arxiv.org/abs/1511.06939
    presentations:
      - name: NCF
        url: https://arxiv.org/abs/1708.05031
      - name: AutoInt
        url: https://arxiv.org/abs/1810.11921
      - name: DGRec
        url: https://arxiv.org/abs/1902.09362
  - date: 4 / 2, 3
    topics: Deep Generative Models
    readings:
      - name: VAE
        url: https://arxiv.org/abs/1312.6114
      - name: GAN
        url: https://arxiv.org/abs/1406.2661
      - name: CycleGAN
        url: https://arxiv.org/abs/1703.10593
  - date: 4 / 9, 14
    topics: Poster Sessions
  - date: 4 / 18
    topics: <b><i>Final Exam</i></b>
---

Schedule
========

Important Dates
---------------
- **Class 1**:
  - **Poster**: 4 / 9
  - **Final Exam**: 4 / 18
- **Class 2**:
  - **Poster**: 4 / 14
  - **Final Exam**: 4 / 18

<table>
  <tr>
    <th>Date</th>
    <th>Topic</th>
    <th>Suggested Readings</th>
    <th>Reference for Presentations</th>
    <th>Homework</th>
  </tr>
  {% for week in page.schedule %}
    <tr>
      <td>{{ week.date }}</td>
      <td>
      {% for topic in week.topics %}
        {% include href item=topic %}<br>
      {% endfor %}
      </td>
      <td>
      {% for reading in week.readings %}
        {% include href item=reading %}<br>
      {% endfor %}
      </td>
      <td>
      {% for presentation in week.presentations %}
        {% include href item=presentation %}<br>
      {% endfor %}
      </td>
      <td>{% include href item=week.homework %}</td>
    </tr>
  {% endfor %}
</table>
