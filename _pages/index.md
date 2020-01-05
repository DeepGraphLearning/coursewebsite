---
layout: home
title: "Deep Learning and Applications"
permalink: /
nav_order: 0
people:
  - name: Prof. Jian Tang
    avatar: assets/images/jian_tang.jpg
    url: https://jian-tang.com/
    description: Instructor
  - name: Meng Qu
    avatar: assets/images/meng_qu.jpg
    url: https://mnqu.github.io/
    description: Teaching Assistant
  - name: Zhaocheng Zhu
    avatar: assets/images/zhaocheng_zhu.jpg
    url: https://kiddozhu.github.io/
    description: Teaching Assistant
---

Machine Learning II: Deep Learning and Applications
==================================================

Info
----

<!--
- **Instructeur**: [Jian Tang]
- **Trimestre**: Hiver 2020
- **Jours et heures**:
  - **Classe 1**: Jeu: 8:30 - 11:30
  - **Classe 2**: Ven: 15:30 - 18:30
- **Salle enseignant**:
  - [Quebecor, Côte-Sainte-Catherine][Quebecor]
  - **Classe 2 sur 3 / 20**: [BDC, Côte-Sainte-Catherine][BDC]

-----------
-->

- **Instructor**: [Jian Tang]
- **Trimester**: Winter 2020
- **When**:
  - **Class 1**: Thu: 8:30 - 11:30
  - **Class 2**: Fri: 15:30 - 18:30
- **Where**:
  - [Quebecor, Côte-Sainte-Catherine][Quebecor]
  - **Class 2 on 3 / 20**: [BDC, Côte-Sainte-Catherine][BDC]

[Jian Tang]: https://jian-tang.com
[Quebecor]: https://www.hec.ca/campus/edifices/cote_sainte_catherine/1er_etage/salles_cours/quebecor.html
[BDC]: https://www.hec.ca/campus/edifices/cote_sainte_catherine/1er_etage/salles_cours/bdc.html

-----------

Course Objectives
-----------------
- Understand machine learning basics 
- Understand deep learning basics such as feedforward neural networks, convolutional neural networks, and recurrent neural networks
- Know several advanced topics in deep learning, including applications in natural language understanding, graph representation learning, recommender systems, and deep generative models
- Learn to use PyTorch for applying deep learning techniques to solve real-world problems

Prerequisites
-------------
- Linear algebra
- Python programming language
- One of following courses
  - Machine Learning I: Large-scale machine learning and decision making
  - Data Mining

Evaluation
----------
- **Homework**: 20%
- **Presentations**: 10%
- **Projects**: 40% = proposal 5% + poster 10% + report 25%
- **Final Exam**: 30%

-----------

Staff
-----

<ul class="list-style-none">
  {% for person in page.people %}
  <li class="d-inline-block mr-10">
    <table>
      <img src="{{ person.avatar }}" class="p-1" height="140" width="140"/>
    </table>
    <div align="center">
      <a href="{{ person.url }}">{{ person.name }}</a><br>
      {{ person.description }}<br>
    </div>
  </li>
  {% endfor %}
</ul>
