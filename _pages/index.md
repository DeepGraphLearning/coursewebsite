---
layout: home
title: "Machine Learning II: Deep Learning"
permalink: /index.html
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
    description: Teaching Assistant
---

Machine Learning II: Deep Learning
==================================

### Winter 2020 ###

-----------

Course Description
------------------
- Understand machine learning basics 
- Understand deep learning basics such as feedforward neural networks, convolutional neural networks, and recurrent neural networks
- Know several advanced topics in deep learning including applications in natural language understanding, graph representation learning, recommender systems, or deep generative models. 
- Learn to use tensorflow or pytorch for applying deep learning techniques to solve real-world problems

Prerequisites
-------------
- Data Mining
- Machine Learning I: Large-scale machine learning and decision making
- Python programming language
- Linear Algebra
- Machine learning basic

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