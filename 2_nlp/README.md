# Notebook for the NLP tutorial at M2L 2022

**Authors**: **[Giuseppe Attanasio](https://federicobianchi.io)** and **[Moreno La Quatra](https://mlaquatra.me/)**.

The tutorial is inspired to established walkthrough on the Transformer architecture: [1](http://nlp.seas.harvard.edu/annotated-transformer) and [2](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/JAX/tutorial6/Transformers_and_MHAttention.html#The-Transformer-architecture).


### Introduction

In this tutorial, you will learn the fundamental components of modern Natural Language Processing (NLP) pipelines. 

Specifically, you will implement the Transformer architecture and test it on the *language modeling* and *machine translation* tasks. Along the way, you will learn core concepts such as self-attention, text tokenization, and more.

### Outline

The tutorial is structured as follows:

1. Introduction to the Transformer Architecture and its building blocks
2. Implementing the Core Components: Scaled and Multi-headed Attention, Embeddings, and Positional Encoding
3. Transformer Encoder and Word-Level Language Modeling
4. Fine-Tuning your Language Model for Sentiment Analysis
4. Transformer Decoder and Machine Translation 
5. *Bonus*: Gender Bias in MT

In each section, we will give you additional pointers to dive deeper on the specific topic. Just keep an eye to the 📚 emoji.

### Libraries and Frameworks

You will use [JAX](https://github.com/google/jax) for low level operations and [haiku](https://github.com/deepmind/dm-haiku) to model neural network modules, and [optax](https://github.com/deepmind/optax) for training optimization. In addition, we will use [datasets](https://github.com/huggingface/datasets) and [tokenizers](https://github.com/huggingface/tokenizers) for the data preparation utilities. 

### 📝 Exercises

The sections marked as \[EXERCISE 📝\] contain cells with missing code that you should complete.

### Useful links

+ Tutorial: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/master/2_nlp/NLP_tutorial.ipynb)
+ Solved Tutorial: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/master/2_nlp/NLP_tutorial_solutions.ipynb)

### License

Designed for education purposes. Please do not distribute without permission. Write at organizers@m2lschool.org if you have any question.

You are welcome to reuse this material in other courses or schools, but please reach out to organizers@m2lschool.org if you plan to do so. We would appreciate it if you could acknowledge that the materials come from M2L 2020 and give credits to the authors. Also please keep a link in your materials to the original repo, in case updates occur.

**MIT License**

Copyright (c) 2020 m2lschool

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
