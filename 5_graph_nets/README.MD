# Colab for the Graph Nets tutorial at M2L 2022

by Pietro Astolfi and Marco Ciccone, based on the notebook from Lisa Wang and Nikola Jovanović.

**Colab Runtime:**

If possible, please use a GPU hardware accelerator to run this colab. You can choose that under *Runtime > Change Runtime Type*.

**Prerequisites:**
* Some familiarity with [JAX](https://github.com/google/jax), you can refer to this [colab](https://colab.sandbox.google.com/github/google/jax/blob/master/docs/jax-101/01-jax-basics.ipynb) for an introduction to JAX.
* Neural network basics
* Graph theory basics (MIT Open Courseware [slides](https://ocw.mit.edu/courses/civil-and-environmental-engineering/1-022-introduction-to-network-models-fall-2018/lecture-notes/MIT1_022F18_lec2.pdf) by Amir Ajorlou)

**Additional Resources:**
* Michael Bronstein • Joan Bruna • Taco Cohen • Petar Veličković: [Geometric Deep Learning Course 2nd Edition](https://www.youtube.com/playlist?list=PLn2-dEmQeTfSLXW8yXP4q_Ii58wFdxb3C)
* Petar Veličković Lecture: [Theoretical Foundations of Graph Neural Networks Lecture](https://www.youtube.com/watch?v=uF53xsT7mjc&)
* Battaglia et al. (2018): [Relational inductive biases, deep learning, and graph networks](https://arxiv.org/pdf/1806.01261)
* Bronstein et al. (2021): [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478)


**Part 1** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/main/5_graph_nets/GNN_Tutorial_Part1.ipynb)

* Fundamental Graph Concepts
* Graph Prediction Tasks
* Intro to the jraph Library
* Graph Convolutional Network (GCN) Layer
* Build GCN Model with Multiple Layers
* Node Classification with GCN on Karate Club Dataset
* Graph Attention (GAT) Layer
* Train GAT Model on Karate Club Dataset

**[Optional] Part 2** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/main/5_graph_nets/GNN_Tutorial_Part2.ipynb)
* Graph Classification on MUTAG (Molecules)
* Link prediction on CORA (Citation Network)


---
*Copyright 2022 by the Authors.*

*Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at https://www.apache.org/licenses/LICENSE-2.0*

*Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.*

Designed for education purposes. Please do not distribute without permission. Write to organizers@m2lschool.org if you have any question.

You are welcome to reuse this material in other courses or schools, but please reach out to organizers@m2lschool.org if you plan to do so. We would appreciate it if you could acknowledge that the materials come from M2L 2022 and give credits to the authors. Also please keep a link in your materials to the original repo, in case updates occur.
