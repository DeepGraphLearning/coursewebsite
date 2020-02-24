---
layout: page
title: Project
permalink: /project
nav_order: 2
---

Course Project
==============

The goal of the course project is to apply deep learning techniques learned in class (it is fine if you use the techniques not introduced in class) to solve real-world problems or develop new deep learning techniques. You are expected to work in teams and learn to collaborate with your teammates. Each group should make a poster in the final class and participate in the poster session to present your results and communicate with other teams. A report should also be submitted at the end of the course.

[Full instructions] can be downloaded here. [GCP tutorial] can be found here.

[Full instructions]: assets/files/Instructions on Course Projects.pdf
[GCP tutorial]: assets/files/GCP tutorial.pdf

Guidelines
----------

- The project proposal is a summary of your proposed research topic and study plan. It should include the background of the problem (context and motivation), problem definition, and a plan on how you want to study it. The project proposal should be at most 2 pages.

- The suggested poster size will be updated later. Some [examples of posters] in conferences are available here.

- The final report should give a comprehensive description of your projects. It should contain a section about the motivation and definition of your selected topics, a section summarizing the related work, a section on the techniques you used for solving the problem, an empirical section presenting your data sets and results with detailed analysis, and a conclusion section. The report should be at most 8 pages (not including references) using [the NeurIPS format]. The final report should be submitted in pdf format.

[examples of posters]: https://postersession.ai/
[the NeurIPS format]: https://nips.cc/Conferences/2015/PaperInformation/StyleFiles

schedule
----------

- **Group formation due**: 1 / 30
- **Proposal due**: 3 / 1
- **Poster presentation**:
  - **Class 1**: 4 / 9
  - **Class 2**: 4 / 14
- **Final report due**: 4 / 25

Groups for Course Projects
----------

The groups for course projects can be found at [the Google sheet].

[the Google sheet]: https://docs.google.com/spreadsheets/d/13g-Y-v2tDRcbWyHboEIVN7erdOJ4glc9GJT8TnkC-5I/edit?usp=sharing

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
