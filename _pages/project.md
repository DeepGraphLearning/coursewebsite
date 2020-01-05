---
layout: page
title: Project
permalink: /project
nav_order: 2
---

Course Project
==============

Guidelines
----------

- Students should form groups of 2-3 people to finish their course projects. Each group should choose a specific research topic related to deep learning. Students can either choose a topic from the following reference list, or discuss possible topics with TAs.

- Once the topic is decided, students should read and summarize relevant papers, implement corresponding models and conduct experiments in various settings.

- Each group is required to submit a project report of about 4 to 8 pages. The report should be in NeurIPS / ICLR paper format, and is expected to include introduction, problem definition, related work, methodology, experiments, and conclusion. Each group is also required to give an 8-minute presentation on their project.

Schedule
----------

- **Proposal due**: TBD
- **Report due**: TBD
- **Poster presentation**:
  - **Class 1**: 4 / 9
  - **Class 2**: 4 / 14

List of References
------------------

1. **Transformers for text classification**<br>
  In class, we have learned several advanced deep learning models for NLP, such as the transformers. Recently, there are many studies trying to train transformers on large unlabeled text corpora. After that, those pre-trained models can be easily fine-tuned on specific tasks by using a small amount of labeled data. Such models (e.g., BERT, XLNet) have been proved to achieve state-of-the-art results on many NLP tasks. In this project, students are encouraged to run those models on a sentence classification task.

2. **GNNs for heterogeneous graphs**<br>	
  In class, we have learned several graph neural networks (GNNs), which can effectively learn node representations on homogeneous graphs, where there is only a single type of edge. However, in many real-world graphs, multiple types of edges exist, and most existing GNNs cannot apply to such graphs. In this project, students are encouraged to design a GNN model which can deal with heterogeneous graphs.

3. **Deep learning for recommender systems**<br>
  In class, we have learned several deep learning models for recommender systems. In this project, students will focus on the simplest setting, i.e., implicit feedback, and they are encouraged to design and implement a deep learning model for implicit feedback. The movielens dataset will be used for evaluating their models.

4. **Image generation**<br>	
  In class, we have learned several deep generative models, which can be used for image generation. In this project, students are encouraged to implement one of these models, and run the model on an image dataset, such as MNIST and CIFAR-100.
